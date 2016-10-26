# Interpreter
###Padrão de Desenvolvimento

Este padrão de projeto é utilzado para representar problemas de forma mais simples, criando uma hierarquia de classes. Uma exemplo bastante simples para o entendimento do Interpreter é um algorítimo de calculadora, onde se tem diversos métodos para cada função, somar, subtrair, multiplicar entre outros.

Com o padrão Interpreter, podemos utilizar expressões regulares e ter somente um método para realizar as operações de uma calculadora, isso faz com que o código fique mais otimizado em grandes aplicações.

# Desenvolvendo o Assunto
###Casos de Uso
- Formato das consultas em banco de dados especializados como em SQL;
- Tradução/conversão de linguagens ou símbolos para outra linguagem como números romanos para números decimais;
- Uso em expressões regulares ou XML;
- Uso de interpretação de formato em datas como DD-MM-AAAA ou MM-DD-AAAA.

# Exemplos
### Interpretando uma nota 
![](https://upload.wikimedia.org/wikipedia/commons/5/5c/Interpreter.png)

### Formatando data MySQL
``
DATE_FORMAT(dataHora, '%d/%m/%Y - %H:%i')
``
