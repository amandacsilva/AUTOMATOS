 [1.0 pt] Implemente AFDs, em uma linguagem de programação à sua escolha, que aceitem
as seguintes cadeias:
a) Todas as cadeias em {0,1}* que representam cada 1 seguido imediatamente de dois 0.
b) Todas as cadeias em {a,b}* de modo que o último símbolo seja b e o número de
símbolos a seja par.
2. [1.0 pt] Implemente um autômato finito que reconheça todas as ocorrências da palavra
computador no texto T. O programa deve apontar em quais posições ocorreram o casamento
exato da palavra.
T = “O computador é uma máquina capaz de variados tipos de tratamento automático de
informações ou processamento de dados. Entende-se por computador um sistema físico que realiza
algum tipo de computação. Assumiu-se que os computadores pessoais e laptops são ícones da era da
informação. O primeiro computador eletromecânico foi construído por Konrad Zuse (1910–1995).
Atualmente, um microcomputador é também chamado computador pessoal ou ainda computador
doméstico.”
3. [1.0 pt] Implemente um transdutor finito (máquina de Moore ou Mealy) que, dada uma
sequência de moedas de 25 e 50 centavos e de 1 real, forneça uma lata de refrigerante
quando a sequência totalizar 1 real ou mais. Cada moeda inserida deverá corresponder a
uma de duas saídas: 0, se uma lata não pode ser (ainda) liberada, ou 1, se uma lata deve ser
liberada. Exemplo:
Entrada: 50 25 50 100 25 50 100 ...
Saída: 0 0 1 1 0 1 1 ...
Instruções para a entrega do trabalho
Desenvolva um relatório técnico, em formato PDF, contendo para cada questão, o código
fonte do autômato finito que reconheça sentenças da linguagem especificada e um conjunto de
testes experimentais. A tabela abaixo apresenta um conjunto de palavras que devem ser testadas em
cada questão.
