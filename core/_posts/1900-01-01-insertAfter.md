---
title: insertAfter
signature: |
  insertAfter(target) ⇒ self
---

Insere elementos da collection atual, após o elemento alvo no
DOM. Isto é como [after](#after), mas com operandos invertidos.

{% highlight js %}
$('<p>Emphasis mine.</p>').insertAfter('blockquote')
{% endhighlight %}
