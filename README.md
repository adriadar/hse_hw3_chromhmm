# hse_hw3_chromhmm

Так как клеточной линии, которую я использовала в дз2 не было в таблице, то я выбрала клеточную линию Osteobl.

[colab-notebook со всеми командами](https://colab.research.google.com/drive/1vUVa9o7EZP6d-b6xrtaqpp1xyKqaaOWv?usp=sharing)

##### Список меток:

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

##### Все картинки из выдачи ChromHMM:

<img src=https://github.com/adriadar/hse_hw3_chromhmm/blob/main/ChromHMM_output/Osteobl_15_RefSeqTES_neighborhood.png width="500"> <img src=https://github.com/adriadar/hse_hw3_chromhmm/blob/main/ChromHMM_output/Osteobl_15_RefSeqTSS_neighborhood.png width="500">

<img src=https://github.com/adriadar/hse_hw3_chromhmm/blob/main/ChromHMM_output/transitions_15.png width="270"> <img src=https://github.com/adriadar/hse_hw3_chromhmm/blob/main/ChromHMM_output/Osteobl_15_overlap.png width="270"> <img src=https://github.com/adriadar/hse_hw3_chromhmm/blob/main/ChromHMM_output/emissions_15.png width="270">

##### Табличка с номерами эпигенетических типов, их характерные эпигенетические метки и другие свойства, а также присвоенные им названия:
| Состояние | Название | Метки | Расположение |
| ------------- |:------------------:|:------------------:| ------------- |
| 1 | Active Promoter | H3k9me3	| laminB1lads	|
|	2 | Weak Promoter | -	| Genome, laminB1lads	|
|	3 | Inactive/poised Promoter | H3k27me3 | laminB1lads	|
|	4 | Strong enhancer | -	| Genome	|
|	5 |Strong enhancer | H3k36me3	| RefSeqTES, RefSeqGene	|
|	6 | Weak/poised enhancer | H3k36me3, H4k20me1	| RefSeqTES, RefSeqGene	|
| 7 | Weak/poised enhancer | H4k20me1		|  RefSeqGene	|
|	8 | Insulator | H3k4me2, H3k4me1	| RefSeqTES, RefSeqGene	|
|	9 | Transcriptional transition | H3k4me2, H3k27ac, H3k4me1	| RefSeqGene	|
|	10 | Transcriptional elongation | H3k27ac	| RefSeqGene |
|	11 | Weak transcribed | H3k4me1	| laminB1lads |
|	12 | Polycomb-repressed | H2afz	| laminB1lads |
|	13 | Heterochromatin; low signal | H3k4me2, H3k4me3, H2afz| CpGIsland, RefSeqExon, RefSeqTSS, RefSeqTSS2kb |
|	14 | Repetitive/Copy Number Variation | H3k27ac, H3k4me2, H3k4me3, H2afz| CpGIsland, RefSeqExon, RefSeqTSS, RefSeqTSS2kb |
|	15 | Repetitive/Copy Number Variation | Ctcf	| laminB1lads |

##### Картинки из UCSC GenomeBrowser:
<img src=https://github.com/adriadar/hse_hw3_chromhmm/blob/main/img/gen_browser_pic1.png>
<img src=https://github.com/adriadar/hse_hw3_chromhmm/blob/main/img/gen_browser_pic2.png>
<img src=https://github.com/adriadar/hse_hw3_chromhmm/blob/main/img/gen_browser_pic3.png>

##### Бонус

Код находится в конце ноутбука, картинки выше, [ссылка на отредактированный файл](https://github.com/adriadar/hse_hw3_chromhmm/blob/main/Osteobl_15_dense.zip)
