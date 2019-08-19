---
layout: post
title: Tarea 1: Introducción al modelo de aprendizaje PAC
date: 2015-07-06 07:59:00
mathjax: true
---

En clase, iniciamos la definición del esquema de aprendizaje PAC
(Probably Approximately Correct). Bajo ciertas simplificaciones,
dado un parámetro de confianza $\delta$ y un error $\epsilon$,
encontramos el número mínimo de datos de entrenamiento en $S$
tal que el error de generalización $L_{(D,f)}(h_S)$ para el
predictor $h_S$ resultado de ERM$_H$ satisface $L_{(D,f)}(h_S)<\epsilon$
con probabilidad $1-\delta$.