# Домашняя работа №2
## Часть 1
Ответы на вопросы представлены в colab'е.  
Ссылка: https://colab.research.google.com/drive/1TDvHjvSpR-IOhPff9wkw7OksSb7QVu_g
### 1. FastQC отчеты
Подрезание чтений понадобилось только для ENCFF000BFT, остальные неплохие.
**ENCFF644SSR:**  
<img src="/img/10.png"/>
<img src="/img/11.png"/>
<img src="/img/12.png"/>

**ENCFF000BFT (до):**  
<img src="/img/1.png"/>
<img src="/img/2.png"/>
<img src="/img/3.png"/>

**ENCFF000BFT (trimmed):**  
<img src="/img/4.png"/>
<img src="/img/5.png"/>
<img src="/img/6.png"/>

**ENCFF066LYG (контроль):** 
<img src="/img/7.png"/>
<img src="/img/8.png"/>
<img src="/img/9.png"/>

### 2. Таблица со статистикой
|Образец                 |ENCFF001FMA|ENCFF000BFT (trimmed)|ENCFF066LYG|
|:-----------------------|:---------:|:---------:|:--------------------:|
|Reads total             |18758297          |6013825	   |17162591              |
|Unique reads aligned    |996862(5.31%)	    |326781 (5.43%)	    |776945 (4.53%)	                |
|Non-unique reads aligned|3164797 (16.87%)    |1128820 (18.77%)	    |1866440 (10.88%)	               |
|Not aligned             |14596638 (77.81%)   |4558224 (75.80%)   |14519206 (84.60%)               |

**Почему процент выравнивания получился именно таким?** 
Потому что мы взяли всего одну хромосому небольшого размера.

### 3. Диаграмма Венна
**Как можно объяснить различия в количестве пересечений?**
Диаграмма Венна показывает количество пересечений среди выявленных нами пиков и пиков из ENCODE. Неодинаковы значения из-за того, что некоторые позиции пиков неуникальны.
<img src="/img/v1.png"/>
<img src="/img/v2.png"/>
<img src="/img/v3.png"/>
<img src="/img/v4.png"/>

## Часть 2

<img src="/img/21.png"/>

<img src="/img/22.png"/>
