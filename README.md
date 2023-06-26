# Projeto Eleições São José dos Campos 2022

O projeto tem como objetivo fazer uma análise de dados sobre as eleições de 2022 em São José dos Campos, respondendo algumas perguntas elaboradas por um jornalista e exibir as estatísticas do eleitorado joseense.

Foram feitas coletas dos dados através dos arquivos csv disponibilizados pelos sites do **_TSE_ (Tribunal Superior Eleitoral)** e **_IBGE_ (Instituto Brasileiro de Geografia e Estatística)**. Esses dados serviram para demonstrar faixa etária, escolaridade, média salarial dentre outras informações solicitadas.

Este projeto surgiu inspirado no Projeto Integrador da turma do 1º Semestre de 2022 do curso Desenvolvimento de Software Multiplataforma da FATEC de São José dos Campos. Um dos Projetos finalizados com FRONTEND e o passo a passo do desenvolvimento pode ser visualizado através do seguinte repositório [Projeto Integrador 2021](https://github.com/Equipe-01-DSM-2021/projeto-integrador-2021-1).


### ORIGEM DOS DADOS
Como informado, os dados foram retirados dos órgãos públicos relacionados, seja [TSE](https://dadosabertos.tse.jus.br/dataset/) com dados sobre eleitorado, abstenções ou [IBGE](https://cidades.ibge.gov.br/brasil/sp/sao-jose-dos-campos/pesquisa/38/47001) com informações sobre o salário médio dos anos de 2017 até 2021.

Foi selecionado para este projeto:
+ Para informações sobre o eleitorado [LINK](https://dadosabertos.tse.jus.br/dataset/eleitorado-2022) -- SP - Perfil do eleitorado por seção eleitoral -2022
+ Para informações sobre abstenção [LINK](https://dadosabertos.tse.jus.br/dataset/?groups=comparecimento-e-abstencao)
+ Para acompanhar a evolução do eleitorado [LINK](https://sig.tse.jus.br/ords/dwapr/r/seai/sig-eleicao-eleitorado) -- Menu - Estatística de eleição - Estatística do Eleitorado - Evolução do eleitorado // filtrar por UF: SP e Município: SÃO JOSÉ DOS CAMPOS
+ Para acessar o salário médio do joseense [LINK](https://cidades.ibge.gov.br/brasil/sp/sao-jose-dos-campos/pesquisa/38/47001)

### Instalação / Funcionamento
1. Instalar o Python 3.6 ou superior
2. Instalar as bibliotecas
3. O arquivo _"perfil_eleitor_2022_SP.csv"_ é muito pesado e o github não suporta. Será necessário fazer o download e colocar o arquivo descompactado dentro da pasta data para o correto funcionamento.

#### Bibliotecas
Foram usadas as seguintes bibliotecas:
+ pandas -- para analisar os dados;
+ matplotlib -- para gerar gráficos;
+ os -- biblioteca com comandos do sistema operacional que facilita algumas operações


#### Desenvolvimento : Toni William do Prado - 2º DSM (Estrutura de Dados)
