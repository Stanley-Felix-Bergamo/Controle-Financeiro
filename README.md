No Vermelho! O Desafio do Controle Financeiro
Linguagem: C# Console

Conteúdos: Variáveis, entrada de dados, operadores aritméticos, operadores relacionais e lógicos, estruturas condicionais (if, else if, else) e cálculos percentuais.

1. Situação-problema
Imagine que você foi contratado para desenvolver um pequeno sistema de controle financeiro pessoal.
Seu cliente, Carlos, está enfrentando dificuldades para administrar seu dinheiro. Embora receba um salário mensal, frequentemente chega ao final do mês sem saber para onde foi seu dinheiro e, em algumas ocasiões, precisa utilizar o cheque especial.
Carlos deseja um programa que analise sua situação financeira, identifique possíveis problemas e apresente orientações para melhorar seu planejamento.
O desafio é desenvolver um sistema que tome decisões com base nos valores informados pelo próprio usuário.

2. Dados que o programa deverá solicitar
Ao iniciar, o programa deverá apresentar uma mensagem de boas-vindas e solicitar as seguintes informações:
Informação						Tipo
Salário líquido mensal				decimal
Gastos com moradia				decimal
Gastos com alimentação				decimal
Gastos com transporte				decimal
Gastos com contas básicas			decimal
Gastos com lazer					decimal
Valor das parcelas de dívidas mensais		decimal
Valor que deseja economizar mensalmente	decimal
Todos os valores deverão ser informados pelo usuário durante a execução do programa, utilizando Console.ReadLine().

3. Regras de negócio
O sistema deverá realizar os cálculos e análises a seguir.
Regra 1: Identificação do saldo mensal
Calcular o total de despesas e subtrair esse valor do salário recebido.
- Se o resultado for negativo, informar que o usuário está gastando mais do que recebe.
- Se o resultado for zero, informar que não há dinheiro disponível.
- Se o resultado for positivo, apresentar o saldo disponível.

Regra 2: Análise do comprometimento da renda
Calcular qual porcentagem do salário está sendo utilizada para pagar as despesas.
Percentual comprometido	Classificação
Até 	50%	Situação confortável
Acima de 	50% 	até 	70%	Situação de atenção
Acima de 	70% 	até 	90%	Situação preocupante
Acima de 	90%	Situação crítica

Regra 3: Análise das dívidas
Verificar o percentual do salário comprometido com as parcelas das dívidas.
Se esse percentual ultrapassar 30%, o sistema deverá emitir um alerta sobre o comprometimento elevado da renda.

Regra 4: Meta de economia
Verificar se o saldo disponível é suficiente para atingir o valor que o usuário deseja economizar.
Se for suficiente, informar quanto ainda restará após separar o dinheiro.
Caso contrário, informar exatamente quanto falta para atingir a meta.

Regra 5: Identificação do maior gasto
O sistema deverá identificar qual das seguintes categorias representa a maior despesa: moradia, alimentação, transporte, contas básicas, lazer ou dívidas.
Em caso de empate, poderá apresentar uma das categorias empatadas.

Regra 6: Recomendação financeira
Com base nos resultados, o programa deverá apresentar uma orientação:
- Se o saldo for negativo, recomendar a revisão das despesas.
- Se o saldo for positivo, mas insuficiente para a meta, recomendar o ajuste de gastos.
- Se o saldo permitir atingir a meta, informar que o planejamento mensal atende ao objetivo de economia.
Os percentuais são critérios didáticos deste exercício, não regras universais de saúde financeira.
