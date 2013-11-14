---
title: toggleClass
signature: |
  toggleClass(names, [setting]) ⇒ self
  toggleClass(function(index, oldClassNames){ ... }, [setting]) ⇒ self
---

Alterna os nomes das classes indicadas (separadas por espaços) em cada elemento da collection.
O nome da classe é removido se estiver presente em um elemento, caso contrário, ele é adicionado.
Se `setting` está presente, este método se comporta como [addClass](#addClass) se definindo
como verdadeiro ou [removeClass](#removeClass) se não for verdadeiro.