---
title: serializeArray
signature: |
  serializeArray() ⇒ array
---

Serializa o formulário em um array com objetos contendo os dados das propriedades `name` e `value`.
Elementos do formulário que estiverem desabilitados, botões ou radio buttons/checkboxes
que não estiverem marcados serão ignorados.
O resultado não inclui os dados que estiverem em `inputs` do tipo `file`.

{% highlight js %}
$('form').serializeArray()
//=> [{ name: 'size', value: 'micro' },
//    { name: 'name', value: 'Zepto' }]
{% endhighlight %}
