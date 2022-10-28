# aprendiz_tech_python

**sobre INDENTAÇÃO**

Basicamente indentar é um termo utilizado para escrever o código do programa de forma hierárquica, facilitando assim a visualização e o entendimento do programa. O exemplo abaixo mostra um código indentado.


**Erros de sintaxe**
O parser repete a linha inválida e apresenta uma pequena ‘seta’ apontando para o ponto da linha em que o erro foi detectado. O erro é causado (ou ao menos detectado) pelo símbolo que precede a seta: no exemplo, o erro foi detectado na função print(), uma vez que um dois-pontos (':') está faltando antes dela. O nome de arquivo e número de linha são exibidos para que você possa rastrear o erro no texto do script.

while True print('Hello world')
  File "<stdin>", line 1
    while True print('Hello world')
                   ^
SyntaxError: invalid syntax

