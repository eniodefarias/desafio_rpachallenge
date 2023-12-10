# desafio_rpachallenge
Desafio do site https://rpachallenge.com/ onde deve baixar uma planilhar, fazer a leitura dos dados e preencher o formulario que possui campos em posições randomicas

## Instruções do desafio

1. O objetivo deste desafio é criar um fluxo de trabalho que insira dados de uma planilha nos campos do formulário no site https://rpachallenge.com/;
2. Cuidado! Os campos mudarão de posição na tela após cada envio ao longo de 10 rodadas, portanto o fluxo de trabalho deve identificar corretamente onde cada registro da planilha deve ser digitado a cada vez;
3. A contagem regressiva real do desafio começará assim que você clicar no botão Iniciar, até então você poderá enviar o formulário quantas vezes desejar sem receber penalidades;

## Briefing do projeto

 - abrir o site https://rpachallenge.com/
 - baixar xls no botão "Download Excel"
 - clicar no botão "START" para iniciar o contador do desafio
 - preencher os campos do formulario (atenção: a ordem dos campos é aleatoria)
   - First Name
   - Last Name
   - Company Name
   - Role in Company
   - Address
   - Email
   - Phone Number
 - clicar no botão "SUBIMIT"
 - repetir o ciclo enquanto houver linhas de dados no excel (nesse desafio serão sempre 10 linhas)

# Proposta de desenvolvimento

 - linguagem: python
 - bibliotecas:
   - pandas -> fazer a leitura do excel
   - selenium -> manimulação dos elementos no webdriver
   - chromedriver -> driver para navegação no site
   - idftools -> canivete suiço multiuso para facilitar eventos como log, leitura, criação de webdriver, entre outras facilidades

## estrutura do processo
 - iniciar o webdriver em headless
 - iniciar sequencial de prints do navegador
 - abrir o site
 - baixar o excel
 - fazer a leitura das colunas e armazenar os nomes dos campos para utilizar para identificar os "label" do html
 - armazenar os dados do excel em list>>dict
 - começar a mapear os label do site e preencher com dado correspondente do excel
 - ao fim de cada ciclo de formulario, clicar no botão submit
 - ao fim do SUBMIT correspondente a ultima linha do excel, capturar a informação do tempo do processo e pontução do desafio
 - salvar a ultima tela em pdf para registrar para a posterioridade
 - converter a sequencia de prints das telas em um video para mostrar o resultado

## Documentação

### auto executavel, para windows
 - se quiser apenas o executavel pronto para uso no windows, só baixar no link abaixo:
   - [desafio_rpachallenge.zip](http://ideiadofuturo.com.br/download/desafio_rpachallenge.zip)

### preparando o ambiente e executando

#### linux
 - linux

#### windows
 - windows



















