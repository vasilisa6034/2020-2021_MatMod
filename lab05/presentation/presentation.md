---
## Front matter
lang: ru-RU
title: "Отчет по лабораторной работе 5"
author: |
	Vasilisa Mikhajlovna Kryuchkova\inst{1}
institute: |
	\inst{1}RUDN University, Moscow, Russian Federation
date: 10 March, 2021 Moscow, Russian Federation

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# **Прагматика выполнения лабораторной работы**

## Зачем?

Математика -- царица наук!

Каждый, занимающийся математическим моделированием, должен уметь:

* Использовать математический аппарат для решения задач
* Моделировать задачи

# **Цель выполнения лабораторной работы**

## Цель

Построить модель Лотки-Вольтерры типа "хищник -- жертва" с помощью Python.

# **Задачи выполнения лабораторной работы**

## Задание. Вариант 41

Для модели «хищник-жертва»:

$$
\begin{cases}
    \frac{\partial x}{\partial t} = -0.58x(t)+0.048x(t)y(t)
    \\
    \frac{\partial y}{\partial t} = 0.38y(t)-0.028x(t)y(t)
\end{cases}
$$

Постройте график зависимости численности хищников от численности жертв, а также графики изменения численности хищников и численности жертв при следующих 
начальных условиях: $x_0 = 7, y_0 = 15$. Найдите стационарное состояние системы.

# **Результаты выполнения лабораторной работы**

## График колебаний изменения числа популяции хищников и жертв

![](image/1.png){ #fig:001 width=70% } 

## График зависимости изменения численности хищников от изменения численности жертв

![](image/2.png){ #fig:002 width=70% }

## Выводы

Построила модель Лотки-Вольтерры типа "хищник -- жертва" с помощью Python.

## {.standout}

Спасибо за внимание!
