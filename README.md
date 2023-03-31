# Java-Mobile
Atividades de Java / Mobile, para as aulas de PAM

# Linguagem "Java"
## *Tipos de dados (Tipos primitivos)*

1. **byte** -  Um tipo de dado que é representado pelo valor de 8 bits e que é considerado como o dado principal por ser "O PAI DE TODOS". Variaveis do tipo "byte" guardam valores inteiros entre -128 e 127, e é uma alternativa para o tipo de dado "int".

2. **short** - Semelhante ao byte, é um tipo de dado representado pelo valor de 16 bits e que guarda valores inteiros. Variaveis do tipo "short" guarda valores entre -32,768 até 32,767, é uma versão maior que o byte.

3. **int** - É um tipo de dado reperesentado pelo valor de 32 bits e que guarda valores inteiros. Variaveis do tipo "int" guarda valores entre -2³¹ até 2³¹, é uma versão maior do short.

4. **long** - O maior tipo de dados que guarda valores inteiros, representado pelo valor de 64 bits, com valores entre -2⁶³ até 2⁶³.

        *OBS - Todos os tipos de dados acima herdam de um tipo "Integer"* 

5. **float** - É um tipo de dado que é representado por valores aproximados que são de "precisão singular",  ou seja, guarda valores de 32 bits. Sempre que for necessário a utilização de valores *byte* ou *short*, é recomendado usar *float*.

6. **double** - É um tipo de dado que também é representado por valores aproximados que são de "precisão dupla, ou seja, guarda valores de 64 bits. Quando se é utilizado valores decimais, é recomendado colocar o tipo *double*.

7. **boolean** - Um tipo de dado que é representado pelo valor de 1 bit e que podem possuir valores "true" ou "false", ou seja, verdadeiro ou falso, mas seus "tamanhos" não são definidos precisamente.

8. **char** - O último tipo de dado primitivo que é um caractere de 16 bits **Unicode** que tem valor mínimo de "0" e valor máximo de "65,535".

        *OBS2 - "Unicode" é o padrão de caracteres onde se é possível guardar caracteres não-latinos.*

## *Estruturas condicionais*

1. **If/else** - Um tipo de estrutura aonde uma expressão booleana é analisada, fazendo com que caso dita condição seja "true", verdadeira, ela seja executada, no caso do "if". Já no caso do "else", a condição só será executada se ela possuir valor "false", falso.
    
        Sintáxe:

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

        Sintáxe:

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


## *Estruturas de Repetição (Looping)*

1. **While** - É uma das estruturas de repetição, onde caso uma condição imposta pelo programador seja "verdadeira", todas as instruções que estiverem dentro dela serão executadas sem parar, até que a condição seja "falsa".

        Sintáxe:

            while (condição) {
                // Trecho de código a ser repetido
            }
}
