# Codon-bias
This project is aimed to reproduce some plots from [Palidwor GA, Perkins TJ, Xia X (2010) A General Model of Codon Bias Due to GC Mutational Bias. PLoS ONE 5(10): e13431.](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0013431#abstract0)

В файле dataset.ipynb создаются таблицы df_proc_relfreq.csv и df_plant_relfreq.csv, использующиеся потом для построения всех графиков. 
В файле heatmaker.ipynb строятся две теплокарты корреляции между G/C составом и GC3 для каждого динуклеотида для бактерий и растений (соответствуют теплокартам с рисунка 1 в статье).
В файле y_model.py содержится единственная функция y_model(codon), по кодону определяющая, какая теоретически у него должна быть зависимость GC3 от GC (соответственно мат. модели из статьи). Функция возвращает вектор из значений функции предполагаемой зависимости.
В файле 


