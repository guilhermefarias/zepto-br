---
title: prependTo
signature: |
  prependTo(target) ⇒ self
---

Adiciona o elemento da collection atual no início e dentro de cada um dos elementos de destino.
É como o [prepend](#prepend), só que com operandos invertidos.

{% highlight js %}
$('<li>first list item</li>').prependTo('ul')
{% endhighlight %}
