---
title: "$.camelCase"
version: 1.0
signature: |
  $.camelCase(string) ⇒ string
---

Transforma uma string que possui hífen em "camel case".
Não afeta as strings que já estão em camel case.

{% highlight js %}
$.camelCase('hello-there') //=> "helloThere"
$.camelCase('helloThere')  //=> "helloThere"
{% endhighlight %}
