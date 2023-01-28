# Contador-Desafio
Projeto de um contador para treinar controle de fluxo e exceções customizadas em java.

Projeto proposto no módulo de controle de fluxo da formação Java Developer da [DIO](https://web.dio.me/), com o objetivo de simular um contador onde o usúario informa dois parâmetros, e o sistema é encarregado de diminuir o primeiro pelo segundo e contar até o resultado. 

Por exemplo, se você passar os números 12 e 30, logo teremos uma interação com 18 ocorrências para imprimir os números: "Imprimindo o número 1", "Imprimindo o número 2" e assim por diante.

A classe ParametrosInvalidosException representa a exceção de negócio no sistema, onde pude aplicar meus conhecimentos em tratamento de exceções em java. Nessa exceção foi tratada a hipotese do usúario inserir o primeiro parâmetro maior que o segundo, fazendo com que o contador não possa funcionar. Nessa situação, a mensagem "O primeiro parametro deve ser menor do que o segundo!" aparece para o usúario. 
