---
title: $.isPlainObject
version: 1.0
signature: |
  $.isPlainObject(object) ⇒ boolean
---

Retorna `true` se o objeto é um "simples" objeto JavaScript, o que só é verdade para o objeto
literais e objetos criados com `new Object`.

{% highlight js %}
$.isPlainObject({})         // => true
$.isPlainObject(new Object) // => true
$.isPlainObject(new Date)   // => false
$.isPlainObject(window)     // => false
{% endhighlight %}

