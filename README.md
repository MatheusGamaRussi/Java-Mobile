# Java-Mobile
Atividades de Java / Mobile, para as aulas de PAM

# Linguagem "Java"
## *Tipos de dados (Tipos primitivos)*

1. **byte** -  Um tipo de dado que é representado pelo valor de 8 bits e que é considerado como o dado principal por ser "O PAI DE TODOS". Variaveis do tipo "byte" guardam valores inteiros entre -128 e 127, e é uma alternativa para o tipo de dado "int".

2. **short** - Semelhante ao byte, é um tipo de dado representado pelo valor de 16 bits e que guarda valores inteiros. Variaveis do tipo "short" guarda valores entre -32,768 até 32,767, é uma versão maior que o byte.

3. **int** - É um tipo de dado reperesentado pelo valor de 32 bits e que guarda valores inteiros. Variaveis do tipo "int" guarda valores entre -2³¹ até 2³¹, é uma versão maior do short.

4. **long** - O maior tipo de dados que guarda valores inteiros, representado pelo valor de 64 bits, com valores entre -2⁶³ até 2⁶³.

        OBS - Todos os tipos de dados acima herdam de um tipo "Integer"

5. **float** - É um tipo de dado que é representado por valores aproximados que são de "precisão singular",  ou seja, guarda valores de 32 bits. Sempre que for necessário a utilização de valores *byte* ou *short*, é recomendado usar *float*.

6. **double** - É um tipo de dado que também é representado por valores aproximados que são de "precisão dupla, ou seja, guarda valores de 64 bits. Quando se é utilizado valores decimais, é recomendado colocar o tipo *double*.

7. **boolean** - Um tipo de dado que é representado pelo valor de 1 bit e que podem possuir valores "true" ou "false", ou seja, verdadeiro ou falso, mas seus "tamanhos" não são definidos precisamente.

8. **char** - O último tipo de dado primitivo que é um caractere de 16 bits **Unicode** que tem valor mínimo de "0" e valor máximo de "65,535".

        OBS2 - "Unicode" é o padrão de caracteres onde se é possível guardar caracteres não-latinos.

## *Estruturas condicionais*

1. **If/else** - Um tipo de estrutura aonde uma expressão booleana é analisada, fazendo com que caso dita condição seja "true", verdadeira, ela seja executada, no caso do "if". Já no caso do "else", a condição só será executada se ela possuir valor "false", falso.
    
        Sintaxe:

            if (condição = true) 
            {
                //Instruções
            } 
            else if (condição = true) 
            {
                //Instruções
            } 
            else 
            {
                //Instruções
            }

2. **Switch/case** - Um tipo de estrutura que é utilizada quando é necessário se usar varios "if/else" em um comando e o mesmo irá comparar os valores que estejam dentro do "switch/case".
É importante realçar que, caso alguma das condições sejam verdadeiras, será executada a mesmo, do contrário, a última condição será executada.

        Sintaxe:

            switch (variável) 
            {
                case 1:
                    //Instruções caso a variável seja "1"
                    break;
                case 2:
                    //Instruções caso a variável seja "2"
                    break;
                case 3:
                    //Instruções caso a variável seja "3"
                    break;
                default:
                    //Instruções caso a variável não seja de nenhum valor acima
                    break;
            }


## *Estruturas/Laços de Repetição (Looping)*

1. **While** - É uma das estruturas de repetição, onde caso uma condição imposta pelo programador seja "verdadeira", todas as instruções que estiverem dentro dela serão executadas sem parar, até que a condição seja "falsa".

        Sintaxe:

            while (condição) {
                // Trecho de código a ser repetido
            }

2. **Do While** - Semelhatne ao "While", porém com uma diferença. Enquanto no "While" as instruções serão executadas se e somente se a condição for verdadeira, já no "Do While", mesmo que tal condição seja falsa, ele ira executar a instrução ao menos uma vez.

        Sintaxe

            do {
                // Trecho de código a ser repetido
            } while ()

3. **For** - O "For" por sua vez tem uma sintaxe mais diferente do que os anteriores. Temos três elementos que constituem o "For", *Variável de controle, condicional e incremento/decremento.

    - **Variável de Controle** - Variável local, geralmente chamada de "i".
    - **Condicional** - Uma condição que, enquanto verdadeira, o looping ocorre, sendo que essa condicional é relacionada à variável de controle.
    - **Incremento/Decremento** - Uma resposta à condicional, caso for verdadeira, é adicionado (i++) ou subtraido (i--) da variável de controle


             Sintaxe:

                for (int i = 0 //Variavel de controle; i <= 10 //condicional; i++ //Incremento/Decremento) {
                    // Trecho de código a ser repetido
                }

## Elementos visuais do *Android Studio*

## *Layout* 

- O layout, ou os elementos do layout, são elementos de uma interface em um aplicativo que vão mostrar e definir como é a estrutura da mesma, além de que a maioria dos os elementos de layout estarem "interligados" pelos comandos *"View"* e *"ViewGroup"*.
- Cada elemento possui um ou mais atributos que vão fazer com que eles se diferenciem e os mesmos podem possuir um "ID" para que eles possam ser identificados de maneira exclusiva.

### Elementos do *layout*

- Dentre os muitos elementos, separamos alguns príncipais, sendo eles:

1. **ViewGroup/View** - Elementos considerados como elementos base para criação dos outros elementos e um tipo de "View Básico", ou seja, são componentes básicos. - View é um elemento que pertence a uma Interface de Usuário individual que vai fazer com que o usuário possa ver e interagir. Já o ViewGroup é uma junção de diversos Views, melhor dizendo, um local de amrmazenamento para outros demais elementos Views que serão utilizados.

2. **Pickers** - Elementos de controle de data e hora de maneira separada(hora/minuto/segundo ou dia/mês/ano) que utiliza de caixas de diálogo e que são componentes únicos que fazem com que o usuário possa selecionar os dados a partir de uma outra fonte.

3. **ListView** - Elementos que armazenam uma quantidade grande quantidade de informações e que tem por função de atualizar essas informações, recebendo e enviando os dados presentes em formato, é claro, de listas.

4. **ImageView** - Elementos que irão manipular recursos relacionados à imagens(tratamento, apresentação/exibição, e que irão alterar componentes na imagem, como mudar a tonalidade ou mudar as dimensões da mesma.

5. **Menu** - Elementos que irão compôr a formação de menus, ou seja, listas de ações que vão  mostrar ao usuário as possíveis ações e/ou atividades que ele irá poder fazer, em diversos aplicativos.