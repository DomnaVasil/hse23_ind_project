# hse23_ind_project
## Выполнила Васильева Д.Н.
##### Эпи-группа: H3K4me
##### Мой ген: KMT2A
##### Функция белка: Histone modification write
##### Комплексы: MLL-HCF, CHD8, COMPASS-like MLL1,2
##### Экспрессия: головной мозг, яичники, артерии (большеберцовая и аорта)
##### "Белки гистон-лизин-метилтрансферазы 2 (KMT2) образуют мультимерные ферментативные комплексы, которые метилируют лизин 4 на гистоне H3 (H3K4) в элементах регуляции транскрипции в геноме." [Park et al., 2020] (https://www.sciencedirect.com/science/article/abs/pii/S1874939919303475)
##### "KMT2A (MLL1) отвечает за создание моно-, ди- и триметилированного H3K4 посредством домена SET и взаимодействия с кофакторами." [Vallianatos, Iwase, 2015] (https://www.futuremedicine.com/doi/abs/10.2217/epi.15.1)
##### "Из множества белков PHD (plant homeodomain) пальцев только PHD3 KMT2A семейства KMT2 проявляет свойства связывания H3K4." [Bochynska et al., 2018] (https://www.mdpi.com/2073-4409/7/3/17) 

## Выравнивания гистонов
### H2A
![image](https://github.com/DomnaVasil/hse23_ind_project/assets/114879123/3c0bbb1e-e828-43d2-b3f7-243f4a6e85af)
#### Большинство последовательностей одинаковы, но некоторые разнятся. Это может быть связано с мутациями или генетическими вариациями
### H2B
![image](https://github.com/DomnaVasil/hse23_ind_project/assets/114879123/749545db-90d1-425c-92bd-ad1f62a9e47e)
#### Большинство последовательностей одинаковы, но некоторые разнятся. Это может быть связано с мутациями или генетическими вариациями
### H3
![image](https://github.com/DomnaVasil/hse23_ind_project/assets/114879123/7fbfc0b0-d2f0-4530-b365-eb229cac97a1)
#### Здесь последовательности практически идентичны друг другу, что позволяет их считать копиями друг друга
### H4
![image](https://github.com/DomnaVasil/hse23_ind_project/assets/114879123/c29e0e34-45eb-4e0c-be02-10917a9197b5)
#### Здесь последовательности также идентичны другу другу, что говорит о том, что они кодируют один и тот же ген

#### В целом, все представленные гистоны содержат в основном идентичные последовательности, поэтому для анализа можно выбрать любую похожую последовательность

## Таблицы E-value
#### Все махинации проводила в гулг коллабе: https://colab.research.google.com/drive/1dbZw3F01pC6DH8tJPbpj46LFm1f3gQ2f?usp=sharing
#### В мой белок KMT2A содержал 3 изоформы, поэтому взяла изоформу 3 NP_001399526_1 (http://genome.ucsc.edu/cgi-bin/hgc?hgsid=1642295392_uADWrS3RrSKRtfyq3oa1sAH8MzYY&db=hg38&c=chr11&l=118436491&r=118526832&o=118436491&t=118526832&g=ncbiRefSeqCurated&i=NM_001412597.1) с самой большой длиной (4002)  
#### Таблицу значений создавала вручную (это вроде не запрещено и я полный ноль в питоне) с помощью Exel (приложена в папке data)
### Таблица значений E-value
![image](https://github.com/DomnaVasil/hse23_ind_project/assets/114879123/e30693b6-d928-4edd-8446-67b28a127a58)
### Таблица значений -Log(E-value)
![image](https://github.com/DomnaVasil/hse23_ind_project/assets/114879123/50d2b853-02ed-4aa4-b12f-1146b8050fa8)
## Тепловая карта
![image](https://github.com/DomnaVasil/hse23_ind_project/assets/114879123/d205562e-89e4-45de-935b-6a1e429bf100)

#### Вывод: в каком-то виде белок KMT2A уже начинает проявляться у Yeast, однако совсем явно он виден в организмах, начиная с Zebrafish. Таким образом, можем предположить, что данный белок появился в период одноклеточных эукариот. 
