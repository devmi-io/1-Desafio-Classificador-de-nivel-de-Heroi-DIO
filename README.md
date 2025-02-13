Classificador de Nível de Herói em JavaScript

Descrição do Projeto:

Já se perguntou qual seria o nível do seu personagem em um RPG?  Com este projeto simples e divertido, você pode descobrir o nível de um herói baseado na sua quantidade de experiência (XP)! ⚔️

Desenvolvido em JavaScript, este classificador de nível de herói analisa a pontuação de experiência (XP) de um herói e o categoriza em diferentes níveis hierárquicos, desde o iniciante Ferro até o supremo Radiante.  É uma forma lúdica e prática de aplicar lógica de programação e estruturas condicionais em JavaScript. ⚡️

Funcionalidades

Classificação Automática de Nível: O código processa a quantidade de XP de um herói e determina automaticamente o nível correspondente.
Múltiplos Níveis: Suporta uma ampla gama de níveis, permitindo classificar heróis com diferentes quantidades de experiência.
Simples e Interativo: Fácil de entender, modificar e usar como base para projetos mais complexos.
Desenvolvido em JavaScript: Utiliza uma linguagem de programação amplamente utilizada e acessível.
Como Funciona

O coração deste projeto é um script JavaScript que segue os seguintes passos:

Define uma lista de heróis:  O código começa com um array (heroes) contendo objetos. Cada objeto representa um herói e possui duas propriedades:

nome: O nome do herói (string).
xp: A quantidade de experiência (XP) do herói (number).
Itera sobre a lista de heróis: Utilizando um loop for...of, o código percorre cada herói dentro do array heroes.

Determina o nível de cada herói: Para cada herói, o código utiliza uma série de estruturas condicionais if...else if...else para verificar a quantidade de XP (heroi.xp) e atribuir o nível apropriado (nivel) de acordo com a seguinte tabela:

Ferro: XP menor que 1.000
Bronze: XP entre 1.001 e 2.000
Prata: XP entre 2.001 e 5.000
Ouro: XP entre 5.001 e 7.000
Platina: XP entre 7.001 e 8.000
Ascendente: XP entre 8.001 e 9.000
Imortal: XP entre 9.001 e 10.000
Radiante: XP maior que 10.000
Exibe o resultado:  Para cada herói, o código utiliza console.log() para exibir uma mensagem formatada no console, informando o nome do herói e o nível em que ele foi classificado.

Níveis de Herói

A experiência (XP) do herói determina o seu nível, seguindo a progressão abaixo:

Nível	Faixa de XP
Ferro	XP &lt; 1.000
Bronze	1.001 &lt;= XP &lt;= 2.000
Prata	2.001 &lt;= XP &lt;= 5.000
Ouro	5.001 &lt;= XP &lt;= 7.000
Platina	7.001 &lt;= XP &lt;= 8.000
Ascendente	8.001 &lt;= XP &lt;= 9.000
Imortal	9.001 &lt;= XP &lt;= 10.000
Radiante	XP > 10.000

Exemplo de Saída

Ao executar o código JavaScript, você verá a seguinte saída no console:

Exemplo de saída do classificador de nível de herói no console, mostrando o nome de cada herói e seu respectivo nível

O Herói de nome devmi-io 1 está no nível de Ascendente
O Herói de nome heymi 2 está no nível de Prata
O Herói de nome loolfor 3 está no nível de Radiante
Tecnologias Utilizadas

JavaScript: Linguagem de programação principal para a lógica do classificador.
