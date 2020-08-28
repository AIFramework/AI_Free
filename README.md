# AIFramework версия 2.1 Free
Публичная версия ИИ фреймворка

* ## [Пакет NuGet](https://www.nuget.org/packages/AI)

* ## [Релиз 16.08.2020](https://github.com/AIFramework/AI_Free/blob/master/Aug2020Free.md)

Презентация [полной версии](https://docs.google.com/presentation/d/1W0DY10chKeZeJ59CCiAnNEdMEtpEc39Khu5tPIPmfCQ), релиз намечен на декабрь 2020г, предрелиз с изменением текущей (урезанной) версии на август 2020г.

* .Net Framework 4.5

# Документация

* ### [Примеры использования](https://github.com/AIFramework/AI_Free/wiki/Examples-of-using-(rus))

* ### Особенности

  * #### Основные типы: 
    * [Векторы](https://github.com/AIFramework/AI_Free/wiki/Vector)
    * [Матрицы](https://github.com/AIFramework/AI_Free/wiki/Matrix)
    * [Тензоры](https://github.com/AIFramework/AI_Free/wiki/Tensor)

  * #### Основные интегральные преобразования:
    * [Фурье](https://github.com/AIFramework/AI_Free/wiki/Furie)
    * [Гильберта](https://github.com/AIFramework/AI_Free/wiki/FastHilbert)
    * [Дискретно косинусное](https://github.com/AIFramework/AI_Free/wiki/DCT)
    * [Быстрая свертка и корреляция](https://github.com/AIFramework/AI_Free/wiki/FastConv)
    * [Корреляционные функции](https://github.com/AIFramework/AI_Free/wiki/Correlation)
    * [Интегрирование и дифференцирование последовательностей](https://github.com/AIFramework/AI_Free/wiki/Functions)

  * #### Классические методы машинного обучения: 
    * **Регрессии**
        * [Экспоненциальное среднее](https://github.com/AIFramework/AI_Free/wiki/ExpMean)
        * [Полиномиальная регрессия](https://github.com/AIFramework/AI_Free/wiki/PolynomialRegression)
        * [Множественная регрессия](https://github.com/AIFramework/AI_Free/wiki/MultipleRegression)
        * [Линейная регрессия](https://github.com/AIFramework/AI_Free/wiki/LinearRegression)
        * [Регрессия на базе функции Гаусса](https://github.com/AIFramework/AI_Free/wiki/RBFGauss)
        * [Регрессия на базе метода ближ. соседей](https://github.com/AIFramework/AI_Free/wiki/kNNReg)
     * **Классификаторы**
        * [Метод эталонов](https://github.com/AIFramework/AI_Free/wiki/NN)
        * [Метод k-ближ. соседей](https://github.com/AIFramework/AI_Free/wiki/kNNCl)
        * [Корреляционный классификатор](https://github.com/AIFramework/AI_Free/wiki/CorrelationClassifier)
     * [Генетические алгоритмы](https://github.com/AIFramework/AI_Free/wiki/Population)

  * ##### Нейронные сети
    * Слои: 
      * [Полносвязный](https://github.com/AIFramework/AI_Free/wiki/FeedForwardLayer)
      * [Линейный без смещения](https://github.com/AIFramework/AI_Free/wiki/LinearLayer)
      * [Сверточный 2D](https://github.com/AIFramework/AI_Free/wiki/ConvolutionLayer)
      * [MaxPooling2D](https://github.com/AIFramework/AI_Free/wiki/MaxPooling)
      * Unpooling
      * [UpSampling с бикубической интерполяцией](https://github.com/AIFramework/AI_Free/wiki/Upsampling2dBicibic)
      * [Flatten](https://github.com/AIFramework/AI_Free/wiki/Flatten)
      * GRU
      * LSTM
      * RNN
      * FilterCell
      * FilterLayer
      * Activation
    * Активационные функции
      * [ReLU и pReLU](https://github.com/AIFramework/AI_Free/wiki/ReLU)
      * [Линейный](https://github.com/AIFramework/AI_Free/wiki/LinearUnit)
      * [Софтмакс](https://github.com/AIFramework/AI_Free/wiki/SoftmaxUnit)
      * [Гиперболический тангенс](https://github.com/AIFramework/AI_Free/wiki/TanhUnit) 
      * [Сигмоидальный](https://github.com/AIFramework/AI_Free/wiki/SigmoidUnit)
      * Арктангенс
      * ElliotSig
      * Гауссова РБФ
      * SQN
      * SQ-RBF
      * PLU
    * Функции ошибки
      * [CrossEntropyWithSoftmax](https://github.com/AIFramework/AI_Free/wiki/CrossEntropyWithSoftmax)
      * [LossMeanSqrSqrt](https://github.com/AIFramework/AI_Free/wiki/LossMeanSqrSqrt)
      * [LossSumOfSquares](https://github.com/AIFramework/AI_Free/wiki/LossSumOfSquares)  
    * Оптимизаторы
      * SGD
      * Nesterov
      * Adagrad
      * Adadelta
      * RmsProp
      * Adam
      * Adamax
 

   * #### Цифровая обработка сигналов
      * [Генерация типовых сигналов](https://github.com/AIFramework/AI_Free/wiki/Signal)
      * [Базовые фильтры](https://github.com/AIFramework/AI_Free/wiki/Filters)
      * [Ких фильтры](https://github.com/AIFramework/AI_Free/wiki/FIRFilter)
      * [Бих фильтры](https://github.com/AIFramework/AI_Free/wiki/IIRFilter)
      * [Амплитудный спектр](https://github.com/AIFramework/AI_Free/wiki/AmplitudeSpectr)
      * [Амплитудная модуляция/демодуляция](https://github.com/AIFramework/AI_Free/wiki/AM)
      * [Частотная модуляция/демодуляция](https://github.com/AIFramework/AI_Free/wiki/FM)

   * #### Визуализация данных
      * [Описание графиков](https://github.com/AIFramework/AI_Free/wiki/Description)
      * [Данные одного графика](https://github.com/AIFramework/AI_Free/wiki/ChartData)
      * [Данные нескольких графиков](https://github.com/AIFramework/AI_Free/wiki/ChartData)
      * [Элемент управления для отрисовки графиков](https://github.com/AIFramework/AI_Free/wiki/ChartVisual)
      * [Тепловые карты](https://github.com/AIFramework/AI_Free/wiki/HeatMapControl)

---
## Разделы

* #### Алгебра - Решение СЛАУ ( [Метод Гаусса](https://github.com/AIFramework/AI_Free/wiki/Gauss), [Метод Крамера](https://github.com/AIFramework/AI_Free/wiki/Kramer))

* #### Дополнительные мат. функции(Поэлементные) ([Функции используемые в нейросетях](https://github.com/AIFramework/AI_Free/wiki/NeuroFunc), [Аналитическая геометрия](https://github.com/AIFramework/AI_Free/wiki/GeomFunc), [Функции распределений](https://github.com/AIFramework/AI_Free/wiki/DistributionFunc), [Математические функции](https://github.com/AIFramework/AI_Free/wiki/MathFunc))

* #### Компьютерное зрение ([Конвертирование и базовые преобразования изображений](https://github.com/AIFramework/AI_Free/wiki/ImgConverter), [Фильтрация изображений](https://github.com/AIFramework/AI_Free/wiki/ImgFilters))

* #### Математическая статистика ([Базовые статистические методы](https://github.com/AIFramework/AI_Free/wiki/Statistic), [Расчет квантилей](https://github.com/AIFramework/AI_Free/wiki/Quantile), [Гистограммы](https://github.com/AIFramework/AI_Free/wiki/Histogramm))

* #### Функции расстояния ([Базовые функции расстояния для метрических методов](https://github.com/AIFramework/AI_Free/wiki/BaseDist))

* #### Анализ алгоритмов ([Оценка точностей классификаторов](https://github.com/AIFramework/AI_Free/wiki/Metrics))


---
* #### [Информация о лицензиях](https://github.com/AIFramework/AI_Free/blob/master/Docs/INFO)

<a rel="license" href="http://creativecommons.org/licenses/by-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nd/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nd/4.0/">Creative Commons Attribution-NoDerivatives 4.0 International License</a>.
