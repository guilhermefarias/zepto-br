---
title: Eventos de toque
---

O módulo de "toque", acrescenta os seguintes eventos, que podem ser usados ​​com [on](#on) e [off](#off):

* `tap` — dispara quando o elemento é tocado.
* `singleTap` and `doubleTap` — este par de eventos pode ser utilizado para detectar dois toques simples ou apenas um toque no mesmo elemento (se você não precisa de detecção de toque duplo, use `tap`).
* `longTap` — dispara quando um elemento é tocado e o dedo mantém pressionado por mais de 750ms.
* `swipe`, `swipeLeft`, `swipeRight`, `swipeUp`, `swipeDown` — dispara quando o dedo é arrastado sobre o elemento (opcionalmente, na direcção dada)

Todos estes eventos também estão disponíveis através de métodos de atalho em qualquer collection Zepto.

{% highlight html %}
<style>.delete { display: none; }</style>

<ul id=items>
  <li>List item 1 <span class=delete>DELETE</span></li>
  <li>List item 2 <span class=delete>DELETE</span></li>
</ul>

<script>
// Mostra o botão delete ao deslizar o dedo
$('#items li').swipe(function(){
  $('.delete').hide()
  $('.delete', this).show()
})

// Deleta a linha ao tocar no botão delete
$('.delete').tap(function(){
  $(this).parent('li').remove()
})
</script>
{% endhighlight %}
