---
layout: post
title:  "Подход к проектированию модульных многоагентных систем"
date:   2016-04-20 15:00:00
categories: slides
---

#### Подход к проектированию модульных многоагентных систем ([PDF][talk-pdf], [Keynote][talk-keynote], [YouTube][talk-youtube])

Доклад с конференции «Ломоносовские чтения» 2016 года ([тезис доклада (PDF)][thesis-pdf]).

Важной составляющей многоагентных систем (МАС) является координация агентов.
Существующие средства разработки МАС предоставляют ограниченные встроенные возможности координации,
вынуждая разработчиков реализовывать такие механизмы самостоятельно для каждой отдельной МАС.
Мы предлагаем использовать полиморфные функции высшего порядка для реализации модульных механизмов координации,
не привязанных к предметной области или способу коммуникации агентов.

[thesis-pdf]:   {{ site.baseurl }}/pdf/modular-mas-design-thesis.pdf
[talk-pdf]:     {{ site.baseurl }}/pdf/modular-mas-design.pdf
[talk-keynote]: {{ site.baseurl }}/keynote/modular-mas-design.zip
[talk-youtube]: https://youtu.be/yuGWULJMgQU
