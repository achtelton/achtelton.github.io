---
layout: post
title:  "Category Theory für Programmierer"
date:   2020-10-18 12:35:12 +0200
categories: Theorie
---

Die letzten Jahre habe ich fleißig die Category Theory Posts von Bartosz Milewski gelesen und hin und wieder seine Videos geguckt:

[Category Theory]( https://bartoszmilewski.com/2014/10/28/category-theory-for-programmers-the-preface)



Bartosz Milewski hat definitiv didaktisches Talent und er passt sich seiner Zielgruppe an. Ich habe als Nichtmathematiker das Gefühl etwas verstanden zu haben.

Was hat es mir als Programmierer gebracht?

Auf jeden Fall etwas Praxis in Haskell und ein tieferes Verständnis von Haskell. Für den Berufsalltag in Java und Javascript recht wenig. Die funktionalen Techniken in Java und Javascript sind auch ohne CT zugänglich, ein gelegentliches flatMap vereinfacht zwar den Code, verwirrt vielleicht aber später einen Kollegen. 

Funktionale Architekturen (Cats/Effects, Free Monads) lassen sich mit CT beschreiben und verstehen, sind aber für mich im Alltag nicht relevant und müssen auch softwaretechnisch gerechtfertigt werden.

CT verhilft zu einem tieferen Verständnis von Computation. Klassische Mathematik ist erstmal für reine und totale Funktionen geeignet (mit Leslie Lamport geht’s weiter). Die sogenannten Effekte (Divergenz, Input/Output, State, Nichtdeterminismus) sind schwieriger mathematisch zu fassen. Der theoretische Ansatz von Moggi (Endofunktoren, Monaden) ist tatsächlich elegant und leistungsfähig. Hier kommt man auch recht schnell zu konkret anwendbaren Theoremen (F-Algebra, Freie Monade, Katamorphismus).

Im Weiteren braucht man eine gewisse Passion für die mathematische Semantik von Computing. Domain Theory / Topos Theorien sind schwer verdauliche Brocken für Nichtmathematiker. 




