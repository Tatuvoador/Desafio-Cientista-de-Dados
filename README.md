
##Desafio Cientista de dados - Manutençao preventiva
##Autor: Lucas Morales

Nota: o projeto foi realizado em R Markdown, portanto, para seu funcionamento é necessário ter a ultima versão do R e do Rstudio instalado em seu computador.

Descrição de Arquivos:
- Teste.RMD - Script realizado em R Markdown com todo o projeto.
- requirements.R - Script em R com a instalação dos pacotes necessários para o projeto.
- EDA.HTML - Script e saídas convertidos para HTML.
- desafio_manutencao_preditiva_teste.csv - Base de dados na qual será realizada a previsão de erro.
- desafio_manutencao_preditiva_treino.csv - Base de dados ultilizada para criação do modelo.
- Resultados.csv - Arquivo com número da coluna e erro previsto de acordo com o modelo elaborado.


Instruções:
1 - Primeiro, instale os pacotes necessários para o projeto iniciando e rodando o arquivo "requirements.r" disponivel no repositório.

2 - Faça o download dos arquivos "desafio_manutencao_preditiva_teste.csv", "desafio_manutencao_preditiva_treino.csv" e "Teste.Rmd" e certifique-se de coloca-los no mesmo diretório em seu computador.

3 - Para executar o projeto, abra o arquivo "Teste.rmd" no R Studio. A partir desse passo, temos 2 opções principais para roda-lo:

3a - Utilize a função "Knit" presente no RStudio para exportar o projeto inteiro para oformato HTML. Esta opção lhe dará um arquivo .HTML com o script e os retornos, além de um arquivo denominado  "resultados.csv", que contém o número da coluna e o erro previsto.

3b - Execute os chunks individualmente ou em conjunto dentro do próprio RStudio. Atente-se a ordem dos blocos durante sua execução. Caso queria pular a EDA e ir direto a modelagem preditiva, certifique-se de rodar primeiro os chunks da seção 0 "Carregando pacotes e dados necessários". Ao final, teremos também um arquivo "resultados.csv" com o número da coluna e erro previsto.
