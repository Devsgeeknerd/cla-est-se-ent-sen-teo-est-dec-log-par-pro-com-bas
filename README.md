<!-- Título -->
# Estruturas “se-então-senão” — Teoria

***Conteúdo da Aula:***

A estrutura de decisão `se-então-senão` nos ajuda a executarmos ou não um determinado trecho de código.

Quando a utilizamos, nós passamos uma operação de comparação, operação esta que será avaliada pela estrutura.

Se a operação retornar que a expressão é verdadeira, o bloco `então` é executado.

Agora, se ela não for verdadeira, o bloco `senão` será executado, isso se ele existir (o bloco `senão` é opcional na maioria das linguagens).

Vamos imaginar a seguinte situação:

* O usuário de nosso algoritmo digita um número e nós deveremos escrever uma mensagem dizendo se o número é maior ou não do que 10.
  
Perceba que precisamos fazer uma verificação neste algoritmo:

* Ver se o número é maior do que 10 ou não.

A frase que será escrita por nosso algoritmo vai variar de acordo como resultado desta verificação:

* `Se` o número for maior que 10, deveremos escrever **“Número maior que 10”**;
* `Caso contrário`, deveremos escrever **“Número menor ou igual a 10”**.

A única maneira de se resolver esta situação é utilizando a estrutura `se-então-senão`.

A condição relacional a ser avaliada é se o número é maior que 10.

Podemos representar este algoritmo com **pseudo-linguagem**...

Vamos ver abaixo como ele ficaria:

```markdown
escrever "Usuário, digite um número";
numeroDigitado = leitura do número digitado;
se numeroDigitado > 10 então
  escrever "Número maior que 10";
senão
  escrever "Número menor ou igual a 10";
```

Perceba em nosso algoritmo escrito com uma **pseudo-linguagem** que a frase **“Número maior que 10”** só vai ser de fato escrita se a condição `“numeroDigitado > 10”` avaliada na estrutura `se` for **verdadeira**.

Se ela for verdadeira, somente o que estiver dentro do bloco `então` será executado e o bloco `senão` será desprezado.

Agora, se a expressão não for verdadeira, ou seja, se o número digitado for menor ou igual a 10, o bloco `então` será desprezado e o bloco `senão` é que será executado.

É importante sabermos que o bloco `senão` é opcional dentro da estrutura `se-então-senão`.

Poderíamos reescrever o algoritmo acima sem o bloco `senão`...

Ele ficaria da seguinte forma:

```markdown
escrever "Usuário, digite um número";
numeroDigitado = leitura do número digitado;
se numeroDigitado > 10 então
  escrever "Número maior que 10";
```

Acima, o resultado da execução do algoritmo seria ligeiramente diferente...

Se o número digitado fosse maior que 10, o bloco `então` seria executado normalmente.

Agora, se a condição fosse **falsa**, isto é, se o número fosse menor ou igual a 10, o algoritmo não faria nada, já que não existe o bloco `senão`.

Se a condição relacional for **falsa**, o bloco `então` nunca será executado, independente se existe o bloco `senão` ou não.

Nós podemos também combinar os operadores lógicos como expressão de avaliação pela estrutura se-então-senão.

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-est-se-ent-sen-teo-est-dec-log-par-pro-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitante")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-est-se-ent-sen-teo-est-dec-log-par-pro-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-est-se-ent-sen-teo-est-dec-log-par-pro-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-est-se-ent-sen-teo-est-dec-log-par-pro-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-est-se-ent-sen-teo-est-dec-log-par-pro-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-est-se-ent-sen-teo-est-dec-log-par-pro-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")
