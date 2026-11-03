# Введение
<br>
<br>
<br>

## Что такое <span v-mark="{ at: 3, color: 'blue', type: 'underline' }">научная</span> <span v-mark="{ at: 1, color: 'orange', type: 'circle' }">&#8203;&#8203;&#8203;визуализация данных</span>?
<br>
<br>
<br>
<br>

<div v-click="2">

### Хорошо продуманные визуализации - это самый быстрый способ загрузки информации в наш мозг.*
<figure>
    <figcaption style="color:#b3b3b3ff; font-size: 18px; position: relative; top: 50px; left: 340px;">________________<br> * Adam Pearce на воркшопе <a href="https://visxai.io">Visualization for AI Explainability (2024)</a>
  </figcaption>
</figure>
</div>

---

# Отличие от инфографики

<br>
<br>

<center>

```mermaid {theme: 'base', scale: 1.4}
graph TD
B(Визуализация данных) -->|Оригинальность| D(Инфографика)
B -->|Воспроизводимость| E(''Научная'' визуализация)
```
</center>

---

# Инфографика

<figure>
  <img src="/infographics_example.jpg" style="width: 580px !important;">
    <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: -50px; left: 640px;">Источник изображения:<br>
    <a href="https://www.behance.net/gallery/10901127/History-of-Life">https://behance.net/gallery/10901127/History-of-Life</a>
  </figcaption>
</figure>

---

# Почему я интересуюсь визуализацией данных?

<div class="grid grid-cols-[5fr_8fr] gap-6">
<div v-click>

### Это увлекательно

<br>
<figure>
  <img src="/strange_histogram_photo_2020-02-28_11-17-55.png" style="width: 250px !important;">
</figure>

</div>
<div v-click>

### ... и красиво

<br>
<figure>
  <img src="/Permissions-type.png" style="width: 600px !important;">
    <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: -60px; left: -400px;">Источник изображения справа:<br>
    <a href="https://www.datylon.com/blog/types-of-charts-graphs-examples-data-visualization">https://datylon.com/blog/types-of-charts-graphs-examples-data-visualization</a>
  </figcaption>
</figure>
</div>
</div>

---

# Почему я интересуюсь визуализацией данных?

### Эффективные визуализации усиливают научный доклад
<br>
<figure>
  <img src="/Moriond_Exotics_talk_example.png" style="width: 670px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: -60px; left: 740px;">Источник: слайды Ellis KAY<br> с конференции <a href="https://indico.in2p3.fr/event/32664/contributions/137079/">Moriond 2024</a>
  </figcaption>
</figure>

<!--
Участвуя во множестве конференций, научных семинарах, защитах и совещаниях, я замечал, что одни докладчики, показывая визуальные материалы, подкрепляют и усиливают основную идею своего доклада, и от этого идея становится запоминающейся. Настолько, что суть некоторых хороших докладов я помню до сих пор. У других докладчиков через визуальные материалы приходилось продираться, они были запутанными, либо несоответствовали произносимым словам. От этого общее впечатление от доклада снижалась, даже если речь была очень хорошей. Такие доклады оказались плохо запомнившимися.
-->

---

# Сколько вы знаете визуализаций?

<br>
<figure>
  <img src="/80_types_of_charts_and_graphs.png" alt="Каталог из 80 типов диаграмм" style="width: 2500px !important;">
  <figcaption class="text-xs text-gray-500 mt-2">Источник: <a href="https://www.datylon.com/blog/types-of-charts-graphs-examples-data-visualization">Datylon, каталог диаграмм</a></figcaption>
</figure>
<br>

---

# Сколько вы знали визуализаций в школе?

<br>
<figure>
  <img src="/80_types_of_charts_and_graphs_school.png" alt="Каталог диаграмм с выделенными типами, знакомыми со школы" style="width: 2500px !important;">
  <figcaption class="text-xs text-gray-500 mt-2">Источник: <a href="https://www.datylon.com/blog/types-of-charts-graphs-examples-data-visualization">Datylon, каталог диаграмм</a></figcaption>
</figure>
<br>

---

# Сколько вы знаете визуализаций в университете?

<br>
<figure>
  <img src="/80_types_of_charts_and_graphs_university.png" alt="Каталог диаграмм с выделенными типами, изученными в университете" style="width: 2500px !important;">
  <figcaption class="text-xs text-gray-500 mt-2">Источник: <a href="https://www.datylon.com/blog/types-of-charts-graphs-examples-data-visualization">Datylon, каталог диаграмм</a></figcaption>
</figure>
<br>

---

# Визуализаций намного больше, чем вы думаете

<br>
<figure>
  <img src="/80_types_of_charts_and_graphs.png" alt="Каталог из 80 типов диаграмм" style="width: 2500px !important;">
  <figcaption class="text-xs text-gray-500 mt-2">Источник: <a href="https://www.datylon.com/blog/types-of-charts-graphs-examples-data-visualization">Datylon, каталог диаграмм</a></figcaption>
</figure>

<br>

> #### Это только малая часть видов визуализаций в 2D!

---
zoom: 0.9
---

# Определение визуализации данных

<div class="mt-3 bg-blue-50 dark:bg-blue-900 rounded p-3 text-sm">

### 📌 Компьютерные системы **визуализации** создают наглядные представления наборов данных, позволяя людям выполнять задачи более эффективно
</div>
<br>
<v-clicks depth="2">

* Визуализации дополняют человеческие возможности
* Существует множество визуальных идиом (концепций)
  * Создание визуализации
  * Взаимодействие с визуализацией
* Визуализации специфичны для конкретных задач
* С визуализацией связаны ограничения:
	* Человека
	* Компьютера
	* Носителя (экрана / бумаги)
* Визуальные идиомы можно анализировать
</v-clicks>

<!--
* Визуализация подходит, когда необходимо дополнить человеческие возможности, а не заменить людей алгоритмическими методами принятия решений
* Пространство возможных визуальных идиом большое, включает в себя задачи создания визуализаций и взаимодействия человека с визуализациями
* Многие визуализации специфичны для конкретных задач, а для других задач неэффективны
* С визуализацией связаны ограничения:
	* Человека
	* Компьютера
	* Носителя (экрана / бумаги)
* Визуальные идиомы можно анализировать
-->

---

# Как анализировать визуализацию: What–Why–How

<div class="grid grid-cols-3 gap-6 mt-8">
<div class="bg-blue-50 dark:bg-blue-900 rounded p-5">

### What?
**Какие данные?**

Тип набора данных, атрибуты и их семантика

</div>
<div class="bg-green-50 dark:bg-green-900 rounded p-5">

### Why?
**Зачем пользователю визуализация?**

Действие и цель: исследовать, найти, сравнить, обобщить

</div>
<div class="bg-orange-50 dark:bg-orange-900 rounded p-5">

### How?
**Как устроена идиома?**

Метки, каналы, компоновка и взаимодействие

</div>
</div>

<div class="bg-gray-50 mt-18 text-center text-xl">

**Сначала задача и данные — затем выбор конкретного графика**
</div>

<figcaption class="text-sm text-gray-500 mt-4">См. T. Munzner, Visualization Analysis and Design, главы 2–4</figcaption>

---

# Why: как описать задачу пользователя?

<div class="grid grid-cols-[2fr_3fr] gap-10 mt-4">
<div>

- **Цель:** обнаружить новое или представить известное
- **Поиск:** объект и его положение могут быть известны или нет
- **Запрос:** идентифицировать, сравнить или обобщить

</div>
<div>

**Типичные цели анализа**

- Тренды, выбросы и особенности
- Распределение одного атрибута
- Зависимости и корреляции между атрибутами
- Топология сети или форма пространственных данных

</div>
</div>

<div class="mt-6 bg-blue-50 dark:bg-blue-900 rounded p-4">

**Пример:** "Сравните распределения температуры по месяцам" — это задача **сравнения**, цель которой — анализ (сопоставление) **распределений** признака
</div>

---
zoom: 0.9
--- 

# Вопросы, на которые отвечает этот курс

<v-clicks>

* Зачем нужен человек в процессе принятия решений?
* Зачем нужен компьютер?
* Зачем использовать визуализацию как внешнюю память?
* Зачем полагаться именно на зрение?
* Зачем показывать данные в деталях?
* Почему визуальных идиом так много?
* Какие выбрать идиомы визуализации в конкретных задачах?
* Почему многие визуализации неэффективны?
* Зачем беспокоиться об эффективности визуализаций?
* Когда мы сталкиваемся с ограниченными ресурсами?
* Как анализировать визуализации?
* Какие данные могут быть визуализированы?
* Как ИИ влияет на визуализацию данных как область знаний?
</v-clicks>


---
zoom: 0.9
---

# Когда мы впервые встречаемся с визуализацией данных?

<div class="grid grid-cols-[6fr_4fr] gap-16">
<div>
<v-clicks depth="2">

* В каком-то смысле когда начинаем читать
	* Любой текст является знаковой системой

* Чтение музыкального текста
	* Очень близко к рассматриваемым на курсе идиомам визуализации

* В общеобразовательной школе?
	* Например, в 4-м классе<br> на уроке "Окружающего мира"<br>
	(фотография тетради Игоря К.)
</v-clicks>
</div>
<div>
<v-click>
<br>
<figure>
  <img src="/график_температуры_20241103_170125.jpg" alt="Школьный график изменения температуры" style="width: 310px !important;">
</figure>
</v-click>
</div>
</div>

---

# Зачем человек в процессе принятия решений?

<br>
<figure>
  <img src="/human_in_the_loop.drawio.png" style="width: 850px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 40px; left: 10px;">На основе Рис. 1 из <a href="https://link.springer.com/chapter/10.1007/978-3-540-70956-5_7">D. Keim et al, Visual Analytics: Definition, Process, and Challenges (2008)</a>
  </figcaption>
</figure>


---

# Зачем человек в процессе принятия решений?
<v-clicks depth="2">

* Визуализация позволяет анализировать данные, когда конкретные вопросы о них заранее неизвестны
	* Или когда таких вопросов слишком много
	* Вопросы пока остаются прерогативой <span v-mark="{ at: 9, color: 'green', type: 'underline' }">человека</span> ☺️

* Мы можем использовать эволюционно приобретенные **способности к нахождению паттернов** <span v-mark="{ at: 10, color: 'green', type: 'underline' }">нашей</span> зрительной системы
	* Визуализация **дополняет** эти способности

* Визуализация предлагает **исследовательский путь**, нежели алгоритмизированный
	* Тоже <span v-mark="{ at: 11, color: 'green', type: 'underline' }">свойственно человеку</span>

* Визуализации помогают <span v-mark="{ at: 12, color: 'green', type: 'underline' }">человеку</span> контролировать системы и алгоритмы
</v-clicks>

---

# Зачем компьютер в процессе принятия решений?

<br>
<v-clicks depth="2">

* Никто не запрещает создавать визуализации карандашом на бумаге
	* Это очень трудоёмко и медленно для больших наборов данных
		* Некоторые наборы данных изменяются во времени
	* Часто требуется **переиспользовать** созданную визуализацию для других данных

* Данные уже находятся в памяти компьютера

* Иногда компьютерная визуализация использует некоторые аспекты нарисованной от руки графики
</v-clicks>

---

# Зачем компьютер в процессе принятия решений?

<figure>
  <img src="/textbook/visualization-analysis-and-design_fig_1.2.svg" style="width: 790px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 20px; left: 10px;">Источник: <a href="https://www.cs.ubc.ca/~tmm/vadbook/">Рис. 1.2. T. Munzner. Visualization Analysis and Design. A K Peters Visualization Series, CRC Press, 2014</a>
  </figcaption>
</figure>

---
zoom: 0.96
---

# Зачем использовать внешнюю память?

<v-clicks>

* Наша **рабочая память** зависит от задачи и окружающих условий, и **ограничена всего несколькими элементами** ([N. Cowan, 2010](https://pmc.ncbi.nlm.nih.gov/articles/PMC2864034))

* Вместо внутреннего познания и рабочей памяти мы можем использовать **внешнюю память** (**внешние представления**) перцептивной системы

* Внешние представления не ограничиваются визуализацией и могут полагаться на осязание
</v-clicks>
<div class="grid grid-cols-[4fr_5fr_6fr] gap-10">
<div>
<v-click>
<figure>
  <img src="/midjourney_abacus.jpg" style="width: 200px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 5px; left: 0px;">Midjourney 6, запрос "hands and abacus"
  </figcaption>
</figure>
</v-click>
</div>
<div>
<v-click>
<figure>
  <img src="/Quipu_H5400-L292213865_original.jpg" style="width: 248px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 5px; left: 0px;"><a href="https://ru.wikipedia.org/wiki/%D0%9A%D0%B8%D0%BF%D1%83">Кипу</a>. <a href="https://www.invaluable.com/auction-lot/beautiful-large-quipu-552-c-d594d89973">Источник фото</a>. См. также <a href="https://courses.csail.mit.edu/iap/khipu/">курс лекций MIT</a>
  </figcaption>
</figure>
</v-click>
</div>
<div>
<v-click>
<figure>
  <img src="/_MG_5700.jpg" style="width: 450px !important;">
</figure>
  <figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 5px; left: 0px;"><a href="https://www.ville-ge.ch/meg/sql/en/musinfo_public.php?id=053477">Навигационная карта с Маршалловых островов.</a> Фото А.Б.
  </figcaption>
</v-click>
</div>
</div>

<!--
* Использование визуализации позволяет человеку отвлечься от внутреннего познания и применения рабочей памяти в пользу перцептивной системы, используя тщательно разработанные изображения в качестве **внешних представлений**, которые также называют **внешней памятью**

* Похоже, в культуре прослеживается общая тенденция ухода от осязаемых инструментов внешней памяти к зрительным.
-->

---
zoom: 0.96
---

# Зачем использовать внешнюю память?

* Наша **рабочая память** зависит от задачи и окружающих условий, и **ограничена всего несколькими элементами** ([N. Cowan, 2010](https://pmc.ncbi.nlm.nih.gov/articles/PMC2864034))

* Вместо внутреннего познания и рабочей памяти мы можем использовать **внешнюю память** (**внешние представления**) перцептивной системы
<v-clicks depth="3">

* Можно создавать визуализации для поддержки **выводов**
	* Визуализация предполагает использование особого расположения объектов, которое ускоряет их <span v-mark="{ at: 3, color: 'lightblue', type: 'underline' }">поиск</span> и <span v-mark="{ at: 4, color: 'green', type: 'underline' }">распознавание</span>
		* <span v-mark="{ at: 3, color: 'lightblue', type: 'highlight' }">Поиск</span> ускоряется, когда **сгруппированы** все объекты, необходимые для конкретного вывода
		* <span v-mark="{ at: 3, color: 'green', type: 'highlight' }">Распознавание</span> облегчается при **группировке** необходимой информации об объекте рядом с ним, и избегании сопоставления с элементами, хранящимся в рабочей памяти
</v-clicks>

<!--
Однако неоптимальная схема может группировать нерелевантную информацию или поддерживать перцептивные умозаключения, которые не являются полезными для предполагаемого процесса решения проблемы.
-->

---

# Зачем использовать внешнюю память?

<br>
<div class="grid grid-cols-[4fr_4fr] gap-20">
<div>
<figure>
  <img src="/найди_отличия_1.png" style="width: 400px !important;">
</figure>
</div>
<div>

<figure>
  <img src="/найди_отличия_2.png" style="width: 400px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 130px; left: -50px;">Источник: И. Чкаников, Час досуга. Занимательные задачи в рисунках, 1947
  </figcaption>
</figure>
</div>
</div>
<br>

#### В игре "найдите отличия" внешняя память используется ограниченно

---
zoom: 0.95
---

# Почему именно зрение?

<v-clicks depth="3">

* Зрительная система человека является высокоскоростным каналом связи с мозгом
	* Мы можем "просканировать" ("окинуть взглядом") большую область зрения благодаря фоновой обработке информации
		* мы видим все "одновременно"
		* значительная часть обработки происходит <span v-mark="{ at: 11, color: 'orange', type: 'box' }">параллельно</span> и без нашего внимания
* Слух обладает более низкой пропускной способностью и другой семантикой
	* Обзор информации не поддерживается из-за последовательности потока звуковой информации
* Осязание
	* Скромные возможности записи/воспроизведения
* Вкус, запах
	* Отсутствуют хорошие реализации устройств записи/воспроизведения 
</v-clicks>

---
layout: image

image: /ravel_daphnis_et_chloe.png
backgroundSize: 20em 100%
---

<!--
Возможности параллельного восприятия через зрительную систему иллюстрирует то, как дирижёры читают партитуру. Это страница из партитуры 2-й симфонической сюиты из балета «Дафнис и Хлоя» Мориса Равеля. Дирижёру нужно обрабатывать 40 линий одновременно. Время звучания, закодированное на этой странице, меньше 5 секунд.
-->

---
layout: image

image: /ravel_daphnis_et_chloe_marked.png
backgroundSize: 20em 100%
---

<SlidevVideo v-click controls width="200">
  <!-- Anything that can go in an HTML video element. -->
  <source src="/37322_fragment.mp3" type="audio/mp3" />
  <p>
    Your browser does not support videos. You may download it
    <a href="/37322_fragment.mp3">here</a>.
  </p>
</SlidevVideo>

<figure>
  <figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 30px; left: 0px;">Морис Равель<br>
  Cюита для оркестра №2 (1912)<br>
  из балета "Дафнис и Хлоя"<br>
  Королевский Филармонический Оркестр<br> дир. Жан-Клод Казадезюс
  </figcaption>
</figure>

<!--
Цветами обозначены партии, записанные в одном ключе. То есть разным цветам соответствуют разная семантика, то есть одинаковое графическое положение нот будет соответствовать разным звукам.
-->

---
zoom: 0.95
--- 


# Пример: вождение автомобиля

<div class="grid grid-cols-[4fr_4fr] gap-20">
<div>
<br>
<figure>
  <img src="/midjourney_long_distance_driver.jpg" style="width: 390px !important;">
    <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 5px; left: 0px;">Midjourney 6, запрос "long-distance driver"
  </figcaption>
</figure>
</div>
<div>

* Вождение автомобиля требует:
	* "Сканирования" дорожной обстановки
	* Обработку информации в параллельном режиме

* Даже эти когнитивные усилия мозг стремится экономить
<br>
<v-click>

* NB: Если водитель после долгой дороги не устал, то водитель водит машину недостаточно безопасно*

</v-click>
</div>
</div>
<v-click>
<figure>
    <figcaption style="color:#b3b3b3ff; font-size: 14px; position: relative; top: -25px; left: 480px;">________________<br> * См. В. И. Ваганов, А. А. Пинт. Езжу без аварий. М.: 1991, 2009
  </figcaption>
</figure>
</v-click>

---

# Зачем показывать данные в деталях?

* Компьютерные системы **визуализации** создают наглядные <span v-mark="{ at: 1, color: 'orange', type: 'box' }">представления наборов данных</span>, позволяя людям выполнять задачи более эффективно

<v-clicks depth="2">

* Одним из типов задач является поиск закономерностей (паттернов) в данных с целью:
	* Подтвердить ожидаемое
	* Исключить неожиданное

* Data Science специалисты очень любят смотреть на <span v-mark="{ at: 5, color: 'blue', type: 'underline' }">статистические характеристики</span> наборов данных
	* Например, используя `pandas.DataFrame.describe` в Python
	* Статистические характеристики **приводят к потере информации** через **обобщение**
</v-clicks>

---
zoom: 0.75
--- 

# Зачем показывать данные в деталях?

#### В 1973 году Ф. Дж. Энскомб предложил пример
<br>
<div class="grid grid-cols-[4fr_5fr] gap-10">
<div>
<v-click>

| Характеристика                              | Значение        |
|---------------------------------------------|-----------------|
| Среднее значение переменной $x$             | 9.0             |
| Дисперсия переменной $x$                    | 10.0            |
| Среднее значение переменной $y$             | 7.5             |
| Дисперсия переменной $y$                    | 3.75            |
| Корреляция между<br> переменными $x$ и $y$  | 0.816           |
| Прямая линейной регрессии                   | $3 + 0.5 x$     |
| Коэффициент детерминации<br> линейной регрессии | 0.67        |
</v-click>
</div>
<div>
<v-click>
<figure>
  <img src="/Anscombe.svg" alt="Четыре разных набора точек с одинаковыми статистическими характеристиками" style="width: 700px !important;">
  <figcaption class="text-xs text-gray-500 mt-2">Источник: <a href="https://ru.wikipedia.org/wiki/%D0%9A%D0%B2%D0%B0%D1%80%D1%82%D0%B5%D1%82_%D0%AD%D0%BD%D1%81%D0%BA%D0%BE%D0%BC%D0%B1%D0%B0">Квартет Энскомба</a></figcaption>
</figure>
</v-click>
</div>
</div>

---
zoom: 0.75
--- 

# Зачем показывать данные в деталях?

#### В 1973 году Ф. Дж. Энскомб предложил пример
<br>
<div class="grid grid-cols-[4fr_5fr] gap-10">
<div>

<figure>
  <img src="/Anscombe_table.png" alt="Исходные значения четырёх наборов данных квартета Энскомба" style="width: 330px !important;">
</figure>
<br>

$\bar{x} = 9.0, ~~~~\mathbb{V}x = 10.0, ~~~~\bar{y} = 7.5, ~~~~\mathbb{V}y = 3.75$<br>
$r = 0.816, ~~~~y = 3 + 0.5 x, ~~~~R_{\mathrm{reg}}^2 = 0.67$
</div>
<div>

<figure>
  <img src="/Anscombe.svg" alt="Четыре разных набора точек с одинаковыми статистическими характеристиками" style="width: 700px !important;">
  <figcaption class="text-xs text-gray-500 mt-2">Источник: <a href="https://ru.wikipedia.org/wiki/%D0%9A%D0%B2%D0%B0%D1%80%D1%82%D0%B5%D1%82_%D0%AD%D0%BD%D1%81%D0%BA%D0%BE%D0%BC%D0%B1%D0%B0">Квартет Энскомба</a></figcaption>
</figure>
</div>
</div>

---
zoom: 0.95
---

# Зачем показывать данные в деталях?

<div class="grid grid-cols-[4fr_4fr_5fr] gap-10">
<div>
<figure>
  <img src="/dino_1.png" style="height: 150px !important;">
</figure>
</div>

<div>

$\footnotesize~~~\bar{x} = 54.02$<br>
$\footnotesize\mathbb{V}x = 14.52$<br>
$\footnotesize~~~\bar{y} = 48.09$<br>
$\footnotesize\mathbb{V}y = 24.79$<br>
$\footnotesize ~~~r = 0.32$
</div>

<div>
<figure>
  <img src="/dino_2.png" style="height: 150px !important;">
</figure>
</div>
</div>
<br>
<figure>
  <img src="/dino_3.png" style="width: 850px !important;">
    <figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top:5px; left: 710px;">Источники: <a href="https://en.wikipedia.org/wiki/Datasaurus_dozen">[1]</a>, <a href="https://dl.acm.org/doi/10.1145/3025453.3025912">[2]</a>
  </figcaption>
</figure>

---

# Почему так много видов визуализаций?

<br>
<figure>
  <img src="/80_types_of_charts_and_graphs.png" style="width: 2500px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 80px; left: 400px;">Источник изображений:<br>
    <a href="https://www.datylon.com/blog/types-of-charts-graphs-examples-data-visualization">https://www.datylon.com/blog/types-of-charts-graphs-examples-data-visualization</a>
  </figcaption>
</figure>

---
zoom: 0.92
---

# Почему так много видов визуализаций?

* Идиомы визуализации:
	* Создание визуализаций
	* Взаимодействие с визуализациями

* Распространенные виды диаграмм: диаграмма рассеяния, столбчатая, линейная
<div class="grid grid-cols-[4fr_4fr_4fr] gap-10">
<div>
<figure>
  <img src="/scatterplot_1.png" style="height: 250px !important;">
<figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 5px; left: 0px;"><a href = "https://www.datylon.com/blog/types-of-charts-graphs-examples-data-visualization#scatter-plot">Источник изображения</a>
</figcaption>
</figure>
</div>

<div>
<figure>
  <img src="/bar_chart_1.png" style="height: 250px !important;">
<figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 5px; left: 0px;"><a href = "https://www.datylon.com/blog/types-of-charts-graphs-examples-data-visualization#bar-graph">Источник изображения</a>
</figcaption>
</figure>
</div>

<div>
<figure>
  <img src="/line_chart_1.png" style="height: 250px !important;">
<figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 5px; left: 0px;"><a href = "https://www.datylon.com/blog/types-of-charts-graphs-examples-data-visualization#line-chart">Источник изображения</a>
</figcaption>
</figure>
</div>
</div>

<!--
Диаграмма рассеяния показывает значения двух числовых переменных, располагая их в виде точек между горизонтальной и вертикальной осями. Простые одноразмерные метки данных дают четкое представление о расположении каждого наблюдения на плоскости двух переменных. Диаграмма рассеяния часто используется для отображения корреляций между числовыми переменными и выявления закономерностей. Будучи «швейцарским ножом» среди диаграмм, диаграмма рассеяния обычно является первой при исследовании данных. Это график с одним из лучших соотношений данных и пространства. Диаграмма рассеяния также известна своей универсальностью. Она дает много вдохновения дизайнерам инфографики и специалистам по визуализации данных. Ее можно превратить практически в любую диаграмму: тепловую карту, точечную диаграмму, диаграмму пиктограмм, карту плиток или какую-нибудь гибридную диаграмму.

Столбчатая диаграмма - это набор прямоугольников, длина которых пропорциональна значениям, которые они представляют. Каждый прямоугольник - столбик - представляет одну категорию. Столбчатые диаграммы отлично подходят для сравнения. Различия в длине столбиков легче воспринимаются, чем, например, различия в размере и цвете.
Столбчатые диаграммы часто используются из-за своей простоты. Зрителям в основном нужно расшифровывать длину и положение столбиков, что делает столбиковые диаграммы очень простыми для понимания. Практически все взрослые люди способны читать столбчатые диаграммы, поэтому не требуется дополнительных знаний в области визуализации данных. По этой причине столбчатые диаграммы отлично справляются со своей задачей. Поэтому, если структура данных и месседж, который вы пытаетесь донести, позволяют это сделать, вам стоит рассмотреть возможность использования столбчатых диаграмм в визуализации данных.
Стоит отметить, что столбчатые диаграммы отображают столбики как вертикально, так и горизонтально. Если вы повернете их на 90 градусов, то снова получите столбчатую диаграмму.

Линейный график - это тип графика, который очень удобен при отображении общих тенденций или прогресса. Линейные графики - один из старейших типов графиков и до сих пор один из самых популярных. Они универсальны, просты и понятны. Они могут отображать сразу много информации. Что действительно хорошо в линейных диаграммах, так это то, что их можно легко наложить или объединить с другими диаграммами, такими как гистограмма или диаграмма областей. На линейной диаграмме точки данных представляют собой два значения и соединены линией, чтобы показать тенденцию изменения данных. Ось x или независимая ось показывает непрерывную переменную (обычно время), а ось y содержит числовое значение зависимой переменной.
-->

---
zoom: 0.9
---

# Почему так много видов визуализаций?
<v-clicks depth="3">

* Большинство идиом визуализации используют:
	1. Кодирование информации в расположении объектов
		* Абсолютное расположение
		* Относительное расположение
	1. Разделение данных на несколько видов
	1. Сокращение объема отображаемых данных при помощи:
		* Сортировки
		* Агрегирования

* Интерактивные визуализации свободны от показа всей информации сразу и позволяют
	* Исследовать данные с разным уровнем детальности
	* Контролировать представление и обобщение информации
</v-clicks>

---

# Интерактивные визуализации

<div class="grid grid-cols-[2fr_3fr] gap-10">
<div>
<v-plotly style="width: 400px !important; height: 190px !important"
:data="[{
x: Array.from({length: 15}, () => Math.random()*4.5),
y: Array.from({length: 15}, () => Math.random()*0),
type: 'scatter',
mode: 'markers',
marker: {color: 'red', size: 10, opacity: 0.5},
showlegend: false
},
{
x: Array.from({length: 15}, () => Math.random()*4.5+5.5),
y: Array.from({length: 15}, () => Math.random()*0),
type: 'scatter',
mode: 'markers',
marker: {color: 'green', size: 10, opacity: 0.5},
showlegend: false
}]"
:layout="{
xaxis: {zeroline: false},
yaxis: {showticklabels: false, showgrid: false},
margin: {l: 10, r:50, pad: 1}
}"
:config="{displayModeBar: false}"
:options="{}"/>

<v-plotly style="height: 250px; position: relative"
:data="[{
x: Array.from({length: 25}, () => Math.random()*0.5),
y: Array.from({length: 25}, () => Math.random()*0.5),
z: Array.from({length: 25}, () => Math.random()*0.5),
type: 'scatter3d',
mode: 'markers',
marker: {color: 'red', size: 4, opacity: 0.5},
showlegend: false
},
{
x: Array.from({length: 15}, () => Math.random()*0.6+0.5),
y: Array.from({length: 15}, () => Math.random()*0.6+0.5),
z: Array.from({length: 15}, () => Math.random()*0.6+0.5),
type: 'scatter3d',
mode: 'markers',
marker: {color: 'green', size: 4, opacity: 0.5},
showlegend: false
}]"
:layout="{
   scene: {camera: {eye: {x: 1.75, y: -1.25, z:1.05}},
            xaxis: {title: 'x<sub>1</sub>', range: [0.01,1]},
            yaxis: {title: 'x<sub>2</sub>', range: [0.,1]},
            zaxis: {title: 'x<sub>3</sub>', range: [0.,1]}},
   margin: {l: 20, r:20, b:20, t:1, pad: 5},
}"
:config="{displayModeBar: false}"
:options="{}"/>
</div>
<div>
<v-plotly style="width: 400px !important; height: 400px !important"
:data="[{
x: Array.from({length: 25}, () => Math.random()*0.45),
y: Array.from({length: 25}, () => Math.random()*0.45),
type: 'scatter',
mode: 'markers',
marker: {color: 'red', size: 10, opacity: 0.5},
showlegend: false
},
{
x: Array.from({length: 15}, () => Math.random()*0.55+0.5),
y: Array.from({length: 15}, () => Math.random()*0.55+0.5),
type: 'scatter',
mode: 'markers',
marker: {color: 'green', size: 10, opacity: 0.5},
showlegend: false
}]"
:layout="{
xaxis: {title: 'x<sub>1</sub>'},
yaxis: {title: 'x<sub>2</sub>'},
margin: {l: 40, r:20, b:70, t:20, pad: 2}
}"
:config="{displayModeBar: false}"
:options="{}"/>
</div>
</div>

---

# Зачем нужна интерактивность?

<div class="grid grid-cols-2 gap-10 mt-6">
<div>

### Возможности

- Показать сначала обзор, затем детали
- Фильтровать данные и менять точку зрения
- Связывать несколько представлений
- Исследовать вопросы, которые заранее неизвестны

</div>
<div>

### Издержки

- Время на изучение интерфейса и действия пользователя
- Необходимость быстрого отклика и понятной обратной связи
- Риск скрыть важное начальное состояние
- Более сложные воспроизведение и проверка результата

</div>
</div>

<div class="mt-6 text-center text-xl">

**Интерактивность оправдана задачей, а не сама по себе**
</div>

---

# Почему так много видов визуализаций?

<br>
<br>
<div class="grid grid-cols-[8fr_4fr] gap-10">
<div>
<figure>
  <img src="/textbook/Figure_8.3.png" style="height: 280px !important;">
<figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 40px; left: 0px;">Источник:<br> <a href="https://www.cs.ubc.ca/~tmm/vadbook/">Рис. 8.3 (b,c). T. Munzner. Visualization Analysis and Design. A K Peters Visualization Series, CRC Press, 2014</a>
</figcaption>
</figure>
</div>

<div>
<figure>
  <img src="/Australian_Census_2011_demographic_map.png" style="height: 280px !important;">
<figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 40px; left: 0px;">Источник:<br><a href = "https://en.wikipedia.org/wiki/Choropleth_map">https://en.wikipedia.org/wiki/Choropleth_map</a>
</figcaption>
</figure>
</div>
</div>

---
zoom: 1.2
---

# Для чего фокусировать применение визуализации на конкретных задачах?
<br>
<br>

* Визуализация, хорошо подходящая для одной задачи, может не подходить для другой задачи, даже если применяется **для одного и того же набора данных**
	* В другой задаче могут интересовать иные аспекты данных

---

# Для чего стремиться к эффективным визуализациям?

### Фокус на эффективности является следствием того, что визуализация важна для принятия решений
<v-clicks depth="2">

* Корректность, точность и истинность играют в визуализации первостепенную роль
	* Корректное изображение не означает отсутствия искажений

* Акценты в визуализации отличаются от других областей, которые также связаны с созданием изображений:
	* В изобразительном искусстве акцент делается на передаче эмоций, эстетическом наслаждении или стимулировании размышлений
	* В кинематографе аналогично + на развертывании повествования
	* В рекламе - на создании настроения или формировании интереса к продукту
</v-clicks>

---
zoom: 0.86
---

# Корректное изображение не означает отсутствия искажений

<center>
<figure>
  <img src="/Worlds_animate.gif" style="width: 480px !important;">
<figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 20px; left: 0px;">Соотношения между площадью каждой страны в проекции Меркатора и истинной площадью. Источник:
<a href = "https://ru.wikipedia.org/wiki/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%86%D0%B8%D1%8F_%D0%9C%D0%B5%D1%80%D0%BA%D0%B0%D1%82%D0%BE%D1%80%D0%B0">https://ru.wikipedia.org/wiki/Проекция_Меркатора</a>
</figcaption>
</figure>
</center>

---

# Акценты в изображениях

<div class="grid grid-cols-[4fr_4fr_4fr] gap-10">
<div>
<v-click>	
<figure>
  <img src="/Portræt_af_den_venezianske_maler_Giovanni_Bellini.jpg" style="height: 350px">
<figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 5px; left: 0px;"><a href = "https://ru.wikipedia.org/wiki/%D0%91%D0%B5%D0%BB%D0%BB%D0%B8%D0%BD%D0%B8,_%D0%94%D0%B6%D0%BE%D0%B2%D0%B0%D0%BD%D0%BD%D0%B8">Джованни Беллини. Автопортрет (1511-12)</a>
</figcaption>
</figure>
</v-click>
</div>

<div>
<v-click>	
<figure>
  <img src="/Pickpocket-Still-1-aspect-ratio-1000-1250-2.jpg" style="height: 350px">
<figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 5px; left: 0px;"><a href = "https://ru.wikipedia.org/wiki/%D0%9A%D0%B0%D1%80%D0%BC%D0%B0%D0%BD%D0%BD%D0%B8%D0%BA_(%D1%84%D0%B8%D0%BB%D1%8C%D0%BC)">Робер Брессон. "Карманник" (1959)</a>
</figcaption>
</figure>
</v-click>
</div>

<div>
<v-click>	
<figure>
  <img src="/Heinz_ad.jpg" style="height: 350px">
<figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 5px; left: 0px;">Реклама кетчупа. McCann Erickson (~2010)
</figcaption>
</figure>
</v-click>
</div>
</div>

---
zoom: 0.95
---

# Для чего стремиться к эффективным визуализациям?

<v-clicks depth="3">

* ### Для достижения целей эмоционального вовлечения и сохранения повествовательной нити **преднамеренное искажение** и даже **подтасовка фактов** часто вполне уместны в других областях, связанных с созданием изображений, но **не в визуализации данных**
<br>

* ### Художественная свобода создателя визуализации сильно ограничена
<br>

* ### Задание "сделайте красивые картинки" может оказаться ложной целью создателя визуализации, если достигнутый результат красив, но не эффективен при восприятии
</v-clicks>

---
zoom: 0.9
---

# В изобразительном искусстве тоже есть исключения

<figure>
  <img src="/40552.jpg" style="height: 500px">
<figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: -100px; left: 720px;">Алессандро Спекки.<br> "Площадь и храм Санта Мария делла Ротонда,<br> некогда древний Пантеон".<br> Лист из серии римских видов (1693).<br> Офорт из собрания М. Б. Атаянца
</figcaption>
</figure>

---
zoom: 0.9
---

# Когда мы сталкиваемся с ограниченными ресурсами?

<br>

<div class="grid grid-cols-[3fr_4fr] gap-6">
<div>

* Ограничения человека
	* Время
	* Память
	* Внимание
</div>
<div>

* Ограничения компьютера
	* Время выполнения вычислений
	* Память
</div>
</div>

<br>

* Ограничения носителя (экрана/бумаги)
	* Каждый пиксель ценен
	* **Плотность информации** - доля занятого информацией пространства относительно всей доступной площади визуализации
		* Компромисс между загромождением и пустой тратой пространства
		* Задача - найти оптимальный вариант между плотным и разреженным пространством

---
zoom: 0.9
---

# Для чего анализировать визуализации?

<br>
<div class="grid grid-cols-[4fr_4fr] gap-10">
<div>

* Помогает структурировать большое пространство вариантов

* Большинство визуализаций неэффективны для конкретного сочетания задачи и данных

* Анализ существующих визуализаций является основой к разработке новых
</div>
<div>
<figure>
  <img src="/textbook/Figure_3.8.png" style="width: 480px !important;">
<figcaption style="color:#b3b3b3ff; font-size: 12px; position: relative; top: 40px; left: 90px;">Источник изображений:<br> <a href="https://www.cs.ubc.ca/~tmm/vadbook/">Рис. 3.8 и 3.9. T. Munzner. Visualization Analysis and Design. 2014</a>
</figcaption>
</figure>
</div>
</div>
<br>
<figure>
  <img src="/textbook/Figure_3.9.png" alt="Сравнение альтернативных визуальных идиом" style="width: 560px !important;">
</figure>

---
zoom: 0.85
---

# Как проверить, что визуализация подходит?

#### Рассмотрим цепочку из 4 уровней:<br>
<div class="grid grid-cols-2 gap-4 mt-4 text-base">
<div class="bg-blue-50 dark:bg-blue-900 rounded p-4">

### 1. Ситуация в предметной области
Правильно ли поняты люди, их работа и вопросы?

**Методы:** наблюдение, интервью
</div>
<div class="bg-green-50 dark:bg-green-900 rounded p-4">

### 2. Абстракция задачи и данных
Верны ли **What** и **Why**, нужны ли производные данные?

**Методы:** обсуждение с пользователями, анализ задач
</div>
<div class="bg-orange-50 dark:bg-orange-900 rounded p-4">

### 3. Визуальная идиома и взаимодействие
Работает ли **How** лучше альтернатив?

**Методы:** сравнение вариантов, эксперименты с пользователями
</div>
<div class="bg-purple-50 dark:bg-purple-900 rounded p-4">

### 4. Алгоритмы
Хватает ли скорости и памяти компьютера для отзывчивости?

**Методы:** замеры ресурсов, анализ сложности
</div>
</div>

<figcaption class="text-sm text-gray-500 mt-2">См. T. Munzner, Visualization Analysis and Design, глава 4</figcaption>
<div class="mt-4 text-center text-lg">

<br>

> #### **Ошибку на верхнем уровне не исправить идеальной реализацией на нижнем**
</div>

