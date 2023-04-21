# Custom Exceptions Java
Este é um projeto desenvolvido durante uma aula prática do curso de Java ministrado pelo professor Nelio Alves. O objetivo deste projeto é apresentar a implementação de exceções personalizadas em Java.

## Problema
Este projeto aborda o problema de como lidar com exceções em um programa de reservas de quartos de hotel.

O projeto apresenta três soluções diferentes para tratar este problema: uma solução muito ruim, uma solução ruim e uma solução boa.

## Solução muito ruim
A solução muito ruim apresenta a lógica de validação diretamente no programa principal, não delegando a reserva. Isso torna o código difícil de ser mantido e difícil de ser entendido.

## Solução ruim
A solução ruim apresenta um método que retorna uma string, prejudicando a semântica da operação. Além disso, não é possível tratar exceções em construtores e não há auxílio do compilador, tornando a lógica estruturada em condicionais aninhadas.

## Solução boa
A solução boa apresenta o tratamento de exceções, permitindo que o código seja mais organizado e fácil de ser mantido. As exceções personalizadas ajudam a identificar problemas específicos no código, tornando mais fácil de entender e corrigir os erros.

## Como executar o projeto
Para executar este projeto, você precisará ter o Java instalado em sua máquina.

Faça o download do projeto ou clone o repositório usando o seguinte comando:

git clone https://github.com/pablovvoliveira/custom-exceptions-java.git
Abra o projeto em sua IDE preferida (Eclipse, IntelliJ, etc.).

Execute o programa principal.

## Como contribuir
Se você gostaria de contribuir com este projeto, sinta-se à vontade para enviar uma pull request.

## Licença
Este projeto é distribuído sob a licença MIT. Para mais informações, leia o arquivo LICENSE.
