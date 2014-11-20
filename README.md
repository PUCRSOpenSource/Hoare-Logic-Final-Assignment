#Second Assignment
##Formal Methods course

The assignment specification, which we received from the professor, can be found
below in portuguese.

###Team

* Diego Jornada
  * [github](https://github.com/djornada)
  * [bitbucket](https://bitbucket.org/djornada)
* Matthias Nunes
  * [github](https://github.com/execb5)
  * [bitbucket](https://bitbucket.org/execb5)

---



##Objetivos:

Prova da correção de programas (algoritmos) imperativos, utilizando os conceitos
da lógica de Hoare.

##Algoritmos

Considere:

```

Algoritmo 01(inteiro positivo x)
  begin
  variaveis locais
    inteiros i; j;
    i := 1;
    j := 4;
    while i != x
      j := j + 2 * i + 3;
      i := i + 1
    end
  end
end

Algoritmo 02 (inteiros x, y; numero natual n)
  begin
    variaveis locais
    inteiros i; j;
    i := 0;
    j := x;
    while i != n
      j := j * y;
      i := i + 1;
    end
  end
end

```

Para cada algoritmo, fazer:

1. Explicar em detalhes qual a função que o algoritmo computa.
2. Apresentar a tripla de Hoare do Algoritmo.
3. Definir e provar por indução invariante do laço.
4. Com a invariante definida acima, provar a correção parcial da tripla com uma
   prova de dedução natural na lógica de Hoare

-

##Sobre o Artigo da Tarefa

Na apresentação da tarefa, deve ser utilizado o modelo da SBC (Sociedade
Brasileira da Computação) para a construção do artigo. Neste artigo, além das
definições e demonstrações colocadas acima, você deve incluir:

1. Uma fundamentação teórica sobre o assunto tratado nesta tarefa.
2. Uma apresentação detalhada de todas as demonstrações e discussões pedidas.
3. Bibliografia utilizada.

##Sobre a Pontuação do Trabalho

A seguinte pontuação será utilizada para avaliar a tarefa:


| Ítem          | Pontuação     |
|:------------- |:-------------:|
| Provas        | 7 pontos      |
| Discussão     | 1 ponto       |
| Apresentação  | 2 pontos      |

##Sobre a Entrega do Trabalho

1. A tarefa deve ser realizada individualmente ou em dupla.
2. Na submissão da tarefa enviar o arquivo PDF nomeado como *NomeSobrenome*.
