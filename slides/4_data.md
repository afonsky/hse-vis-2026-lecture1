---
zoom: 0.9
---

# Что такое данные?

<br>

<div class="grid grid-cols-[5fr_5fr] gap-10">
<div>
<v-clicks depth="2">

* Совокупность наблюдений и их признаков
* Признак - это свойство или характеристика объекта
  * Примеры: рост, цвет глаз человека, температура и т.д.
  * Признак также известен как атрибут, переменная, поле, характеристика или свойство
* Набор признаков описывает наблюдение
  * Наблюдение также известено как объект, запись, точка, случай, образец, сущность
</v-clicks>
</div>

<div>
<br>
<br>
<v-click at="2">
<figure>
  <img src="/data_matrix.png" style="width: 600px !important;">
</figure>
</v-click>
</div>
</div>

---

# Что мы визуализируем?
<br>
<div class="grid grid-cols-[5fr_2fr] gap-15">
<div>
<figure>
  <img src="/textbook/fig_2.1_1.svg" style="width: 650px !important;">
  <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: -60px; left: 620px;">Источник:<br> <a href="https://www.cs.ubc.ca/~tmm/vadbook/">Рис. 2.1. T. Munzner. Visualization Analysis and Design.<br> A K Peters Visualization Series, CRC Press, 2014</a>
  </figcaption>
</figure>
</div>
<div>
<figure>
<br>
<img src="/textbook/fig_2.1_2.svg" style="width: 150px !important;">
</figure>
</div>
</div>

---
zoom: 0.94
--- 

# Типы наборов данных

<br>

<div class="grid grid-cols-[4fr_4fr] gap-10">
<div>

* Набор записей
  * Матрица данных
  * Текстовые данные
  * Данные транзакций
<br>

* Графы
  * Социальные, Интернет
  * Молекулярные структуры
</div>
<div>
<br>
<br>

* Упорядоченные данные
  * Пространственные данные
  * Временные ряды
  * Последовательные данные
  * Данные секвенирования генома
</div>
</div>

---

# Матрица данных

* Если объекты данных имеют одинаковый фиксированный набор числовых атрибутов и каждое измерение представляет отдельный признак 

* Такой набор данных можно представить в виде матрицы $n \times p$, в которой есть $n$ строк, по одной для каждого объекта, и $p$ столбцов, по одному для каждого признака


<center>
<figure>
  <img src="/data_matrix_1.png" style="width: 600px !important;">
</figure>
</center>

---

# Текстовые данные

### (Один из способов представления)
<br>

* Каждый текст становится вектором уникальных "слов"
  * Каждое слово является компонентом (признаком) вектора
  * Значение каждого компонента - сколько раз соответствующее слово<br> встречается в тексте
<br>
<br>

<center>
<figure>
  <img src="/document_data.png" style="width: 700px !important;">
</figure>
</center>

---

# Данные транзакций

### Особый тип наборов записей, в котором каждая запись (транзакция) включает в себя набор элементов

<br>
<br>
<br>
<br>

<center>
<figure>
  <img src="/transaction_data.png" style="width: 400px !important;">
</figure>
</center>

---

# Графы

### Примеры: простой граф и граф ранжирования сайтов в поисковой выдаче Google Search

<br>

<div class="grid grid-cols-[3fr_5fr] gap-50">
<div>
  <br>
  <br>
<figure>
  <img src="/graph_1.png" style="width: 200px !important;">
</figure>
</div>

<div>
<figure>
  <img src="/PageRanks-Example.png" style="width: 300px !important;">
</figure>
</div>
</div>
<br>

#### Графы используются для представления географических, социальных, данных, торговых и прочих данных

---

# Молекулярные структуры

#### Пример: Молекулярная структура `{Nd[(2,6-Me2C6H3-O)2PO2]3[(2,6-Me2C6H3-O)2PO2H]3}`
<br>
<figure>
  <img src="/Molecular-structure.png" style="width: 350px !important;">
    <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 10px; left: 400px;">Источник изображения: DOI:
    <a href="https://link.springer.com/article/10.1007/s11224-018-1132-2">10.1007/s11224-018-1132-2</a>
  </figcaption>
</figure>

---

# Упорядоченные данные

### Пример: последовательность аминокислот в ДНК
<br>
<br>
<figure>
  <img src="/AMY1gene.png" style="width: 600px !important;">
      <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 60px; left: 500px;">Источник изображения:<br>
    <a href="https://en.wikipedia.org/wiki/Nucleic_acid_sequence">https://en.wikipedia.org/wiki/Nucleic_acid_sequence</a>
  </figcaption>
</figure>

---

# Упорядоченные данные

### Пример: Пространственно-временные данные
<br>
<br>

<div class="grid grid-cols-[3fr_6fr] gap-50">
<div>
<br>
<br>
<br>

#### Среднемесячная температура на Земле
</div>

<div>
<figure>
  <img src="/World_ERAI_T2_scycle.gif" style="width: 600px !important;">
      <figcaption style="color:#b3b3b3ff; font-size: 11px; position: relative; top: 20px; left: 100px;">Источник изображения: <a href="https://climatereanalyzer.org/clim/animations/">https://climatereanalyzer.org/clim/animations/</a>
  </figcaption>
</figure>
</div>
</div>