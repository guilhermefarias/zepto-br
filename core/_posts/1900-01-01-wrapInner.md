---
title: wrapInner
signature: |
  wrapInner(structure) ⇒ self
  wrapInner(function(index){ ... }) ⇒ self [v1.0]
---

Envolve o _conteúdo_ de cada elemento separadamente numa estrutura. Estrutura pode ser
um único elemento ou vários elementos aninhados, e pode ser passado como uma string
HTML ou nó DOM, ou como uma função que é chamada para cada elemento e retorna um dos
primeiros dois tipos.

{% highlight js %}
// Envolve o conteúdo de cada link de navegação em um span:
$('nav a').wrapInner('<span>')

// Elvolve o conteúdo de cada item da lista em um paragrafo com ênfase:
$('ol li').wrapInner('<p><em /></p>')
{% endhighlight %}
