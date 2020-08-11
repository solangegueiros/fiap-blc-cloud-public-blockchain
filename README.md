# Cloud-Based Public Blockchain
Avaliação da disciplina Cloud-Based Public Blockchain no curso MBA Blockchain - FIAP

## Descrição
Escolha 2 dos 4 exercícios para entregar
Cada exercício vale 5 pontos

## Exercício 1 - AWS Blockchain Template para Ethereum
Crie um ambiente Ethereum na AWS utilizando o WS Blockchain Template para Ethereum

### 1.1 - Montar o ambiente

Enviar um "print" das tela com as configurações para EthStats, EthExplorer e EthJsonRpc

### 1.2 - Executar o EthExplorer

Enviar um "print" das tela do EthExplorer, com alguns blocos

### 1.3 - Executar o EthStats

Enviar um "print" das tela do EthStats, com alguns blocos

### Referências AWS Blockchain Template para Ethereum

https://docs.aws.amazon.com/pt_br/blockchain-templates/latest/developerguide/blockchain-templates-ethereum.html

https://docs.aws.amazon.com/pt_br/blockchain-templates/latest/developerguide/blockchain-templates-dg.pdf

1- Configuração

https://docs.aws.amazon.com/pt_br/blockchain-templates/latest/developerguide/blockchain-templates-setting-up.html

2- Pré-requisitos

https://docs.aws.amazon.com/pt_br/blockchain-templates/latest/developerguide/blockchain-template-getting-started-prerequisites.html

3- Instruções

https://docs.aws.amazon.com/pt_br/blockchain-templates/latest/developerguide/blockchain-templates-create-stack.html


Deploy smart contracts to your private Ethereum blockchain network on AWS:

https://aws.amazon.com/blogs/database/deploy-smart-contracts-to-your-private-ethereum-blockchain-network-on-aws/

Anotações de aula:

https://docs.google.com/document/d/1ZeqoGq1LSj6zRFcYmpGK60rcSoTgcqP_TD3jG-r-n4I/edit?usp=sharing


## Exercício 2 - QLDB - Quantum Ledger Database

Executar o tutorial
https://console.aws.amazon.com/qldb/home#/gettingStarted


Criar uma "ledger" - nome: vehicle-registration

Carregar os dados de exemplo - Load sample data

Enviar "prints" das seguintes tarefas:

### 2.1 Query Vehicle

SELECT v.VIN, r.LicensePlateNumber, r.State, r.City, r.Owners
FROM Vehicle AS v, VehicleRegistration AS r
WHERE v.VIN = '1N4AL11D75C109151'
AND v.VIN = r.VIN

### 2.2 Query Person

SELECT * FROM Person AS p, DriversLicense as l
WHERE p.GovId = l.LicenseNumber
and p.data.LastName = 'Lewis'


### 2.3 Modify documents

https://docs.aws.amazon.com/qldb/latest/developerguide/getting-started-step-4.html

"print" do select final do item 7


### 2.4 View the Modification History for a Document

https://docs.aws.amazon.com/qldb/latest/developerguide/getting-started-step-5.html

"print" do select do item 6

### 2.5 Verify a Document in a Ledger

https://docs.aws.amazon.com/qldb/latest/developerguide/getting-started-step-6.html

"print" do "Verification results card" do item 8


### Referências QLDB - Quantum Ledger Database

https://console.aws.amazon.com/qldb/

https://console.aws.amazon.com/qldb/home?#firstRun


Tutorial

https://console.aws.amazon.com/qldb/home#/gettingStarted



## Exercício 3 - Kaleido


### 3.1 Criar o "Consortium"

https://docs.kaleido.io/using-kaleido/quick-start/first-blockchain/

"print" da tela do "Consortium" criado, onde aparecem os Environments, Contract projects e Members


### 3.2 Deploy de um smart contract

https://docs.kaleido.io/using-kaleido/quick-start/first-contract/

"print" da tela com a mensagem "Complete: Contract Deployed Successfully", como esta:

https://docs.kaleido.io/images/tx_receipt_kafka.png


### 3.3 Execução da função "set"

"print" da tela com do "get", após executar a função "set" com um número arbitrário. Atenção: dois grupos não podem ter o mesmo número no "print"!

### Referências Kaleido

https://kaleido.io/

https://docs.kaleido.io/using-kaleido/quick-start/

Anotações de aula:

https://docs.google.com/document/d/1wTv1qih97mfGthVq89d26DAb4cA9gBQbwPJ0H7G22CY/edit?usp=sharing


## Exercício 4 - Azure Blockchain Workbench
Crie um ambiente no Azure Blockchain Workbench e publique o exemplo Hello, Blockchain!

https://docs.microsoft.com/en-us/azure/blockchain/workbench/create-app#hello-blockchain
https://github.com/Azure-Samples/blockchain/tree/master/blockchain-workbench/application-and-smart-contract-samples/hello-blockchain

### 4.1 Criar o ambiente no Azure Blockchain
Enviar um "print" do ambiente criado

### 4.2 Publicar o exemplo Hello, Blockchain
Enviar um "print" com o deploy de pelo menos 2 instancias de Hello, Blockchain, com mensagens e respostas


### Referências Azure Blockchain Workbench

https://portal.azure.com/


https://docs.microsoft.com/en-us/azure/blockchain/workbench/deploy


Tutorial:

https://docs.microsoft.com/en-us/azure/blockchain/workbench/create-app


Anotações de aula:

https://docs.google.com/document/d/1wlqdR6G_Bwzcxz_xkWaLjXj0ydJILIdm0Wn3xitAQ24/edit?usp=sharing


## Entrega
PDF na plataforma da Fiap

### O que entregar
Um documento em formato PDF com:
nomes dos integrantes do grupo
"Print screen" do resultado de cada exercício
referências / links utilizadas

Fazer upload do PDF na plataforma da Fiap

