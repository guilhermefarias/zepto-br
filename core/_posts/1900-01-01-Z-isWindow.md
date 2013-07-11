---
title: $.isWindow
version: 1.0
signature: |
  $.isWindow(object) ⇒ boolean
---

Retorna `true` se o objeto é um objeto `window`. Isto é útil para iframe onde cada um
tem sua própria janela, e onde esses objetos falham na checagem `obj === window`.
