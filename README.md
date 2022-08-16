# job02_Airton - Sistema distribuído cliente/servidor
### Trabalho 02 da disciplina de ADS - Professor Airton
##### Discentes: Clécio / Fredson

## Servidor de banco de dados da implementação
### Apache Cassandra

## Linguagem definida pelo professor da disciplina
### Java

## Observações
### Não é obrigatório o uso de interface gráfica

# Especificações do trabalho

#### Do lado cliente

Deve ser capaz de gerar e salvar N arquivos de tamanho Z automaticamente e enviar de forma <em>sequencial</em>, configurando a taxa de envio (arq/segundos). Três parâmetro para serem configurados.

O sistema deverá ser monitorado em termos de três métricas, de preferência salvando em arquivo de log, mas pode usar algum tipo de script para:
    ## Tempo médio de reposta (MRT)
    ## Consumo de memória
    ## Consumo de CPU.
# Apresentação

>> No dia da apresentação deverão mostrar um <em>gráfico</em> com resultados e como foi que fizeram o salvamento, coleta etc...
>> Qualquer dúvida que altere esta especificação geral ou características adicionais ao projeto, deverá ser informado no grupo da disciplina.


# CONFIGURAÇÕES DE TESTE E DESCRIÇÃO DAS AÇÕES PARA O TRABALHO 02 DA DISCIPLINA

### Teste 01: Simulação de duas máquinas clientes e um servidor principal virtualizadas localmente.

##### Ambiente de experimento 1:

  > Configuração do virtualBox com um servidor e duas máquinas clientes;
  > Preparação do ambiente java nas máquinas clientes para executar o software em java para solicitação de conexão e envio dos arquivos;
  > Preparação do ambiente java na máquina servidor para executar o software java e receber as requisições de conexão e envio dos arquivos pelas máquinas clientes
### Teste 01: Simulação de duas máquinas clientes e um servidor principal virtualizadas localmente.


##### Ambiente de experimento 2:

  > Configuração de uma máquina em nuvem para instalação e configuração de um servidor Apache Cassandra em nuvem;
  > Preparação do ambiente java nas máquinas clientes remotas (dispositivos móveis qualquer) para envio das requisições de conexão e arquivos;
  
  Nos dois ambientes de experimento a coleta das informações serão feitas no lado servidor como dito em aula pelo professor da disciplina.
