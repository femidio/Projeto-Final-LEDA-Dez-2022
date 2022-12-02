# Projeto-Final-LEDA-Dez-2022

Contem a lista de exercicios do Projeto e os links para as Respostas/Soluçoes para os mesmos.

Projeto foi feito individualmente por Francisco Emidio, PT3021912

Na lista abaixo encontra-se os exercicios propriramente ditos e os links para o REPLIT.COM onde se poderá ler e executar os codigos.

Faremos uma tentativa de upoload dos codigos.


1)	(valor 1,5) Escreva uma biblioteca que implemente uma solução do tipo pilha para as seguintes estruturas:

struct Node {
    int number;
    Node next;
};

struct Stack {
    Node top;
    
    /* Determina a quantidade máxima de itens que a pilha pode comportar */
    int max_items;

    /* Indica a quantidade de elementos presentes na pilha */
    int qty;
};

Em seguida, implemente métodos para:
- Retornar a quantidade de elementos contidos na pilha
- Verificar se a pilha está cheia
- Verificar se a pilha está vazia
- Verificar se um elemento está presente na pilha
- Exibir os elementos presentes na pilha
- Empilhar (inserir) um novo elemento na pilha
- Desempilhar (retirar) um elemento da pilha
- 

https://replit.com/join/cdpcuchkrm-franciscoemidio 

2)	(valor 1,5) Escreva uma biblioteca que implemente uma solução do tipo fila para as seguintes estruturas:

struct Node {
    int number;
    Node next;
};

struct Queue {
    Node head; //Nó inicial da fila
    Node tail; //Nó final da fila
    
    /* Determina a quantidade máxima de itens que a fila pode comportar */
    int max_items;

    /* Indica a quantidade de elementos presentes na fila */
    int qty;
};

Em seguida, implemente métodos para:
- Retornar a quantidade de elementos contidos na fila
- Verificar se a fila está cheia
- Verificar se a fila  está vazia
- Verificar se um elemento está presente na fila
- Exibir os elementos presentes na fila
- Inserir um elemento na fila
- Retirar um elemento da fila
- 
https://replit.com/join/srnyrwyuvp-franciscoemidio 

3)	(valor 1,0) Escreva um programa que crie duas pilhas sequenciais numéricas ordenadas crescentemente a partir do topo. Transfira os elementos dessas pilhas para uma terceira pilha, inicialmente vazia, de modo que ela fique ordenada decrescentemente com o maior valor no topo.

https://replit.com/join/mgikbvaorw-franciscoemidio

4)	(valor 1,0) Escreva uma função que receba três filas, duas já preenchidas em ordem crescente e preencha a última com os valores das duas primeiras em ordem crescente.

https://replit.com/join/obyshkesuq-franciscoemidio 

5)	(valor 1,0) Escreva um programa que cadastre em uma pilha vários números. A entrada deles será finalizada com a digitação de um número menor ou igual a 0 (zero). Posteriormente, o programa deve gerar duas filas, a primeira com números pares e a segunda com os números ímpares. A saída do programa deve apresentar a pilha digitada e as filas geradas. Caso alguma das filas seja vazia, deve-se mostrar uma mensagem.

https://replit.com/join/akwggwsdxd-franciscoemidio 

6)	(valor 4,0) Escolha um dos projetos abaixo e realize o desenvolvimento da solução:


Projeto 01: Adega de vinhos
Imagine um colecionador de vinhos que compra vinhos recentes e os guarda em uma adega para envelhecerem, e que cada ocasião especial abre sempre a sua última aquisição (para poupar os mais antigos). Construa um programa que:
a)	Permita incluir novos vinhos na adega;
b)	Informe qual vinho deve ser aberto sem uma ocasião especial, retirando da adega o vinho adicionado mais antigamente (independentemente de sua safra);
c)	Permite criar estruturas para o armazenamento de vinhos para ocasiões especiais;
d)	Informe qual vinho deve ser aberto em uma ocasião especial;
e)	Relacione as cinco aquisições mais antigas;
f)	Relacione as cinco aquisições mais recentes.
As informações básicas que o registro de vinhos deve conter são: nome do produto, país de origem, tipo de uva e safra.

https://replit.com/join/adxymmaljo-franciscoemidio 

Projeto 02: Agência Bancária
Construa um programa que simule uma agência bancária que possua 3 (três) caixas atendendo uma fila única de clientes, de forma a determinar o tempo médio de espera do cliente na fila, para cada transação realizada (conforme tabela abaixo). À medida que qualquer um dos caixas fique livre, o primeiro cliente da fila o utiliza. Quando o cliente entra na fila, o horário é anotado. Quando ele sai, o horário também é anotado e verifica-se o tempo em que ele aguardou na fila. O tempo que o cliente vai demorar no caixa vai depender da transação a ser realizada. Na simulação, essa transação deverá ser aleatória e escolhida na tabela abaixo. Quando terminar o atendimento, exiba o tempo de espera e atendimento deste cliente. Ao final do expediente (a ser definido pelo usuário), o sistema deverá exibir o tempo médio de espera dos clientes na fila, a quantidade de vezes que cada transação foi realizada, quantos clientes foram atendidos e quantos clientes não foram atendidos (os que estavam na fila na hora que terminou o expediente).
Transação	Código	Tempo (s)
Saldo	0	10
Saque	1	20
Aplicação	2	30
Extrato semanal	3	40
Extrato mensal	4	50
Pagamento de conta em dinheiro	5	60
Pagamento de conta em cheque	6	70
Pagamento de conta com saque	7	80


