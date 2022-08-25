# Disponibilização validação ANEW-Br
Disponibilização das normas brasileiras do ANEW-Br (Kristensen et al. 2011) em
formatos .csv e .Rdata.

## Motivação
As normas brasileiras para o _Affective Norms_ americano são apresentadas por
Kristensen et al. (2011) após um importante trabalho de tradução e validação.
Contudo, as normas são apresentadas apenas em tabelas anexadas no artigo, em formato pdf, dificultando seu uso.

## Etapas

1. Conversão das tabelas do Anexo 1 de Kristensen et al. (2011) para formato .xlsx
pelo site ilovepdf.com (arquivo `anew_words_raw.csv`).
2. Reorganização dos dados para formato longo em R (arquivo `disponibilizacao.qmd`). O formato final da tabela conta com as colunas PALAVRA, DIMENSAO (valência e ativação/alerta), MÉDIA e DP.
3. Exportação dos dados nos formatos .csv (dados completos, apenas valência e apenas ativação) e no formato .Rdata


Kristensen, C. H., Gomes, C. F. de A., Justo, A. R., & Vieira, K. (2011). Normas brasileiras para o Affective Norms for English Words. Trends in Psychiatry and Psychotherapy, 33(3), 135–146. https://doi.org/10.1590/S2237-60892011000300003

