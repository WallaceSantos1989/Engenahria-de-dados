PUC RJ - MPV - Sprint: Engenharia de Dados
Wallace Euzébio dos Santos
Objetivo: Analisar o desempenho de diferentes escolas na prova do ENEM de acordo com dados históricos.
O dataset deste trabalho foi retirado do site pertencente ao Governo Federal, com informações do intervalo de anos de 2005 a 2015, material disponível no caminho: https://www.gov.br/inep/pt-br/acesso-a-informacao/dados-abertos/microdados/enem-por-escola

O trabalho foi apresentado na plataforma databricks, onde é possível verificar os gráficos e um ambiente mais acolhedor: 

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2070709557830338/1588732065841684/936246517549823/latest.html


Catálogo de dados:
NU_ANO - Ano da edição do ENEM por Escola.

CO_UF_ESCOLA - Código da Unidade da Federação da escola.

CO_MUNICIPIO_ESCOLA - Código do município da escola - Categorias: 1º dígito: Região; 1º e 2º dígitos: UF; 3º, 4º, 5º e 6º dígitos: Município; 7º dígito: dígito verificador.

NO_MUNICIPIO_ESCOLA - Nome do município da escola.

CO_ESCOLA_EDUCACENSO - Código da Escola. Número gerado como identificador da escola no Educacenso.

NO_ESCOLA_EDUCACENSO - Nome da Escola no Educacenso do ano anterior.

TP_DEPENDENCIA_ADM_ESCOLA - Tipo da dependência administrativa da entidade (Escola) do Educacenso - 1 - Federal, 2 - Estadual, 3 - Municipal, 4 - Privada.

TP_LOCALIZACAO_ESCOLA - Tipo de Localização da escola - 1 - Urbana, 2 - Rural.

NU_MATRICULAS - Número de alunos matriculados no Censo Escolar na 3ª e 4ª do Ensino Médio. Anos de 2005 a 2015.

NU_PARTICIPANTES_NEC_ESP - Número de Participantes do Enem que cumprem os requisitos de participação no cálculo da média e possui necessidade especial. Anos de 2013 a 2015.

NU_PARTICIPANTES - Número de Participantes do Enem que cumprem os requisitos de participação no cálculo da média. Anos de 2005 a 2015.

NU_TAXA_PARTICIPACAO - A taxa de participação é o número total de participantes no ENEM da escola dividido pelo número de matriculados nos anos finais do Ensino Médio da escola, informado no Censo Escolar. Anos de 2009 a 2015.

NU_MEDIA_CN - Média das notas de Ciências da Natureza do Ensino Médio Regular. Anos de 2009 a 2015.

NU_MEDIA_CH - Média das notas de Ciências Humanas do Ensino Médio Regular. Anos de 2009 a 2015.

NU_MEDIA_LP - Média das notas de Linguagens e Códigos do Ensino Médio Regular. Anos de 2009 a 2015.

NU_MEDIA_MT - Média das notas de Matemática do Ensino Médio Regular. Anos de 2009 a 2015.

NU_MEDIA_RED - Média das notas de Redação do Ensino Médio Regular. Anos de 2008 a 2015.

NU_MEDIA_OBJ - Média da prova objetiva do Ensino Médio Regular. Ano 2008.

NU_MEDIA_TOT - Média Total (Redação e Prova Objetiva) Ensino Médio Regular corrigida pelo número de participantes. Anos 2005 a 2007.

INSE - Indicador de Nível Socioeconômico da escola - Para melhor descrever o nível socioeconômico das escolas, foram criados seis grupos, de forma que o Grupo 1 congrega as escolas com Inse médio mais baixo e o Grupo 6, com mais alto. (Edição 2015) – Categorias: Grupo 1, Grupo 2, Grupo 3, Grupo 4, Grupo 5, Grupo 6. Ano 2015.

PC_FORMACAO_DOCENTE - Indicador de Adequação da Formação Docente da escola para lecionar no Ensino Médio. Anos 2013 a 2015.

NU_TAXA_PERMANENCIA - Indicador de Permanência na Escola para o Ensino Médio. Anos 2014 e 2015.

NU_TAXA_APROVACAO - Taxa de aprovação dos alunos no Ensino Médio. Anos 2005, 2007 a 2015.

NU_TAXA_REPROVACAO - Taxa de reprovação dos alunos no Ensino Médio. Anos 2005, 2007 a 2015.

NU_TAXA_ABANDONO - Taxa de abandono dos alunos no Ensino Médio. Anos 2005, 2007 a 2015.

PORTE_ESCOLA - O indicador de porte da escola defini o tamanho da escola pelo número de alunos matriculados no último ano do Ensino médio. Categorias: De 1 a 30 alunos, De 31 a 60 alunos, De 61 a 90 alunos, Maior que 90 alunos. Anos de 2005 a 2015.

Nota:

Até 2008 a escala das notas do Enem variavam de Zero a 100 (Cem). Nos demais anos a escala varia de zero a 1.000 (um mil).

Até a edição de 2008 não foi exigido taxa de participação para divulgação dos resultas. Das edições de 2009 e 2010 a taxa mínima era de apenas 2%, e a partir de 2011 a taxa mínima passou a ser 50%.

Informações sobre os Indicadores são apresentadas em Nota Técnica específica disponível no Portal do Inep.

Apenas o ano de 2015 tem o indicador INSE. Esta versão era a mais atual até o fechamento do produto.

O ENEM (Exame Nacional do Ensino Médio) é uma prova padronizada aplicada pelo Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (INEP) no Brasil. Criado em 1998, o ENEM foi inicialmente concebido para avaliar a qualidade do ensino médio no país, mas ao longo dos anos, sua finalidade se expandiu. Aqui estão alguns pontos chave sobre o ENEM:

Objetivos do ENEM
Avaliação de Desempenho:

Avaliar o desempenho dos estudantes ao final do ensino médio, proporcionando um diagnóstico sobre a qualidade da educação básica no Brasil.
Acesso ao Ensino Superior:

Serve como um dos principais meios de ingresso em universidades públicas e privadas. Muitas instituições utilizam a nota do ENEM no processo seletivo, seja como única forma de ingresso, seja como parte do processo (complementando o vestibular tradicional).
Programas Governamentais:

A nota do ENEM é utilizada em diversos programas governamentais, como o Sistema de Seleção Unificada (SiSU), o Programa Universidade para Todos (ProUni), o Fundo de Financiamento Estudantil (FIES), e o Programa de Acesso à Educação Técnica e Emprego (Pronatec).
Autoavaliação:

Proporciona aos estudantes uma forma de autoavaliação, ajudando-os a identificar suas forças e fraquezas em diversas áreas do conhecimento.
