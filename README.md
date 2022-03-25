# hse_hw3_chromhmm

Так как клеточной линии, которую я использовала в дз2 не было в таблице, то я выбрала клеточную линию Osteobl.

[colab-notebook со всеми командами](https://colab.research.google.com/drive/1vUVa9o7EZP6d-b6xrtaqpp1xyKqaaOWv?usp=sharing)

Список меток:

| Метка | Имя файла |
| ------------- |:------------------:|
| H2afz	| wgEncodeBroadHistoneOsteoblH2azStdAlnRep1.bam	|
|	H3k27ac	| wgEncodeBroadHistoneOsteoblH3k27acStdAlnRep1.bam	|
|	H3k27me3 | wgEncodeBroadHistoneOsteoH3k27me3AlnRep1.bam	|
|	H3k36me3	| wgEncodeBroadHistoneOsteoblH3k36me3StdAlnRep1.bam	|
|	H3k4me1	| wgEncodeBroadHistoneOsteoblH3k4me1StdAlnRep1.bam	|
|	H3k4me2	| wgEncodeBroadHistoneOsteoblH3k4me2StdAlnRep1.bam	|
| H3k4me3	| wgEncodeBroadHistoneOsteoH3k04me3AlnRep1.bam	|
|	H3k9me3	| wgEncodeBroadHistoneOsteoblH3k9me3StdAlnRep1.bam	|
|	Ctcf	| wgEncodeBroadHistoneOsteoblCtcfStdAlnRep1.bam	|
|	H4k20me1	| wgEncodeBroadHistoneOsteoH4k20me1AlnRep1.bam |
| Control | wgEncodeBroadHistoneOsteoblControlStdAlnRep1.bam |

[ссылка на cellmarkfiletable.txt](https://github.com/adriadar/hse_hw3_chromhmm/blob/main/cellmarkfiletable.txt)

[папка с выдачей ChromHMM](https://github.com/adriadar/hse_hw3_chromhmm/tree/main/ChromHMM_output) (файл Osteobl_10_dense.bed весил больше 25Mb, поэтому пришлось его заархивировать)

Все картинки из выдачи ChromHMM:

<img src=https://github.com/adriadar/hse_hw3_chromhmm/blob/main/ChromHMM_output/Osteobl_10_RefSeqTES_neighborhood.png width="400"> <img src=https://github.com/adriadar/hse_hw3_chromhmm/blob/main/ChromHMM_output/Osteobl_10_RefSeqTSS_neighborhood.png width="400">

<img src=https://github.com/adriadar/hse_hw3_chromhmm/blob/main/ChromHMM_output/transitions_10.png width="350"> <img src=https://github.com/adriadar/hse_hw3_chromhmm/blob/main/ChromHMM_output/Osteobl_10_overlap.png width="350"> <img src=https://github.com/adriadar/hse_hw3_chromhmm/blob/main/ChromHMM_output/emissions_10.png width="350">

+ ~~Список 10-ти гистоновых меток (и соотв имен файлов) , для которых был сделан анализ~~
+ ~~Файл cellmarkfiletable.txt~~
+ ~~Папку с выдачей ChromHMM~~
+ Картинки из выдачи ChromHMM
+ Табличка с номерами эпигенетических типов, их характерные эпигенетические метки и другие свойства, а также присвоенные им названия
+ Одну или несколько картинок из UCSC GenomeBrowser, показывающих различные участки генома и соответствующие эпигенетические типы (и, желательно, профили эпигенетических меток)
+ ~~Список всех запущенных команд~~
+ Результат бонусного задания (если есть)
