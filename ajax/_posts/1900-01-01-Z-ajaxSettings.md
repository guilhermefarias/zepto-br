---
title: $.ajaxSettings
---

Objeto que contém a configuração padrão para as requisições Ajax. A maioria das
configurações são descritas em [$.ajax](#$.ajax). Os que são úteis quando definido
globalmente são:

* `timeout` (default: `0`): define um valor diferente de zero para especificar um
tempo limite padrão para requisições Ajax em milissegundos
* `global` (default: true): define como falso para evitar disparar eventos do Ajax
* `xhr` (default: XMLHttpRequest factory): define para a função que retorna
instancias de XMLHttpRequests (ou um objeto compatível)
* `accepts`: MIME types para as requisições do servidor em um valor
`dataType` específico:
  - script: "text/javascript, application/javascript"
  - json:   "application/json"
  - xml:    "application/xml, text/xml"
  - html:   "text/html"
  - text:   "text/plain"
