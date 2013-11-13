---
title: insertBefore
signature: |
  insertBefore(target) ⇒ self
---

Insere elementos da collection atual antes de cada um dos elementos-alvo
no DOM. Isto é como [before](#before), mas com operandos invertidos.

{% highlight js %}
$('<p>See the following table:</p>').insertBefore('table')
{% endhighlight %}
