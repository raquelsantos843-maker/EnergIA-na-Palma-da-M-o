## INSTITUTO BENJAMIN CONSTANT - CURSO TÉCNICO DE NÍVEL MÉDIO EM INTELIGÊNCIA ARTIFICIAL

## DIÁRIO DE DESENVOLVIMENTO DO PROTÓTIPO

## Integrantes:

- Ana Silvia Gomes Ribeiro
- Camila Jeniffer dos Santos Vilaça
- Elizabeth Augusta Batista Rocha
- Pauliana Correia Saraiva
- Raquel Mota dos Santos

## Projeto: EnergIA na Palma da Mão

## Manaus – Amazonas 2026

---

## AULA 01 – Escolha e continuidade do projeto

O grupo iniciou as atividades analisando o documento do projeto de pesquisa. Após uma conversa entre as integrantes, decidimos dar continuidade ao projeto denominado EnergIA na Palma da Mão, que tem como objetivo ajudar os usuários a acompanhar e controlar o consumo de energia elétrica, contribuindo para a economia na conta de luz.

## AULA 02 – Planejamento da aplicação

Nesta aula, começamos a analisar como seria possível colocar em prática a medição do consumo de energia em tempo real. Discutimos a possibilidade de utilizar um dispositivo conectado ao disjuntor para enviar informações diretamente ao aplicativo.

Também avaliamos as dificuldades técnicas e financeiras para desenvolver essa ideia e discutimos se seria possível continuar com a proposta inicial.

## AULA 03 – Desenvolvimento da estrutura inicial do aplicativo

Com a ajuda do professor, conseguimos desenvolver a estrutura inicial da nossa aplicação. Durante essa etapa, realizamos algumas alterações para melhorar o funcionamento e a organização do aplicativo.

## 1ª alteração – Criação da tela de cadastro

Foi adicionada uma aba de cadastro para permitir que o usuário informe seus dados e tenha acesso às funcionalidades do aplicativo.
| | |
|---|---| 
<img width="1381" height="879" alt="tela de cadastro" src="https://github.com/user-attachments/assets/16207998-597d-4290-a696-38905ac397cd" />|


## 2ª alteração – Configuração tarifária e limite mensal planejado

Foram adicionados os seguintes campos:
| | |
|---|---| 
<img width="1235" height="186" alt="calculo de meta finaceira" src="https://github.com/user-attachments/assets/db6b884c-217a-4079-8c5b-14d060c57223" />|

- Tarifa de energia (R$/kWh);
- Bandeira tarifária vigente;
- Limite mensal de consumo (kWh);
- Meta financeira mensal (R$), opcional.

Também foi acrescentado um cálculo na área de meta financeira, permitindo estimar o valor da conta de energia de acordo com a tarifa configurada e a bandeira tarifária selecionada, incluindo a antiga bandeira de escassez hídrica como referência histórica.

## AULA 04 – Alterações na medição do consumo

## 1ª alteração – Simulação do consumo diário
| | |
|---|---| 
<img width="1275" height="662" alt="Alterção medidor no disjuntor" src="https://github.com/user-attachments/assets/2632288a-1bc3-4c31-8476-335e0af06eb0" />|

Inicialmente, tínhamos a ideia de medir o consumo diário por meio de um dispositivo instalado no disjuntor e conectado ao aplicativo.

Entretanto, como não será possível desenvolver essa integração neste momento, decidimos trabalhar com dados simulados. Dessa forma, criamos a proposta de uma barra de progresso que aumenta conforme o consumo diário informado ou simulado pelo sistema.

## 2ª alteração – Tela de cadastro

Realizamos ajustes na tela de cadastro para melhorar a organização das informações e facilitar a utilização do aplicativo pelos usuários.
| | |
|---|---| 
<img width="451" height="633" alt="Nova tela de cadastro" src="https://github.com/user-attachments/assets/ce587831-9599-4e62-9b4b-00a7733a6436" />|

## AULA 05 – Organização das funcionalidades

Nesta aula, começamos a organizar melhor as funcionalidades do aplicativo. Analisamos as telas existentes e verificamos quais informações seriam necessárias para que o usuário pudesse acompanhar seu consumo de energia.

Também discutimos melhorias na apresentação dos dados, buscando deixar o aplicativo mais simples e fácil de utilizar.

