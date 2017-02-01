# Locadora_De_Veiculos
Locadora

Você foi contratado para criar um sistema para gerenciar uma locadora de veículos na

linguagem de programação C. O sistema deve gerenciar as atividades dos clientes de aluguel de

carros, custos da locação, local de entregue (sabendo que o cliente pode entregar o carro em

qualquer filial da empresa). Além disso, o sistema deve apresentar a opção de listar todos os carros

disponíveis e os locados. A seguir será detalhado cada uma das operaçẽos que devem ser

implementadas.

-Cadastro de novos clientes

-Cadastro de novos veículos

-Locação de carros

-Cadastro de novas filias

-Movimentar carros

Tais funções deverão estar presentes no menu principal do programa. Funcionalidades adicionais

são bem vindas, mas não será adicionado novos valores além do contratado (nota!). No entanto,

funções não atendidas, representarão redução no valor pago (na nota!). Se nada estiver funcionando,

nada será pago.

Função de cadastro de novos clientes

O sistema deve armazenar as informações de cada cliente conforme descrito a seguir:

• Primeiro Nome : É constituído por um conjunto de caracteres alfabéticos. Ex: João, Maria e

Francisco.

• Último Nome: É constituído por um conjunto de caracteres alfabéticos. Ex: Silva, Souza e

Paiva.

• CPF: deve ser verificado se o número de CPF é válido.

• Número do cadastro: Identificador da conta. É constituído por um conjunto de 5 dígitos.

Onde os 4 primeiros são a base e o último é um dígito verificador. Ex: 23425, 63496. O

dígito verificador corresponde ao resto da divisão por 11 do somatório da multiplicação de

cada algarismo da base respectivamente por 9, 8, 7, 6, se o resto for 10 o dígito verificador é

0.

Exemplo caso o número base fosse 3451 o número da conta seria:

3x9 + 4x8 +5x7 + 1x6 = 100.

100/11 = 9, resto 1, então o número da conta é 34511.

• Senha: Necessária para realizar qualquer operação em um terminal remoto (web). É

constituído de 6 dígitos.

• Endereço: composto por uma string de no máximo 100 carateres.

Função de cadastrar novos veículos

Cada veículo novo que será utilizado para locação deve ser cadastrado no sistema. As seguintes

informações devem ser armazenadas:

• Placa do veículo

• Modelo do carro

• Ano de fabricação

• Estado do carro

• Quilometragem atual

Função de Locação de carros

Esta funcionalidade deve implementar o processo de locação de um veículo. Por exemplo, o cliente

escolhe o carro utilizando uma placa através de um atendente, e o carro é vinculado a conta do

cliente. Note que um mesmo carro não pode estar locado ao mesmo tempo por dois clientes. Ou

seja, uma vez que um cliente faz uma locação, o mesmo veículo não pode ser disponibilizado pelo

sistema para uma segunda locação. Ao realizar uma locação, o sistema deve armazenar informações

referentes ao custo, quilometragem inicial, data de locação.

Cadastro de novas filias

A locação de veículos pode ser realizada em uma filial da empresa e o carro pode ser devolvido em

outra filial. Sabendo disso, o sistema deve permitir que novas filias sejam incorporadas. O sistema

deve gerenciar onde que cada carro se encontra a cada momento. Uma filial pode ficar sem nenhum

carro em uma situação atípica.

Movimentar carros

O sistema deve possibilitar que carros sejam transferidos de uma filial a outra pela administração.

Tal situação será simulada (alguém fisicamente irá levar o veículo de um local a outro), no entanto,

o sistema deverá permitir que a localização de um veículo seja alterado. A função movimentar

carro deve receber a placa do veículo

Recursos da Linguagem C obrigatórios no projeto:

Funções - as operações detalhadas neste trabalho devem ser feitas com funções da Linguagem C.

Vetores - estruturas de vetores precisam estar presentes no trabalho.

Ponteiros - pelo menos um ponteiro no sistema.
