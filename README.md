# Предсказание объёма запасов нефти в новых скважинах

В добывающей компании необходимо оценить планируемые места размещения новых скважин:

  1. Предсказать объёмы нефти;
  2. Определить регион с максимальной суммарной прибылью.
  
Предоставлены пробы нефти в трёх регионах. Характеристики для каждой скважины в регионе уже известны. 

  1. Проведена предобработка данных и подготовка их к обучению (удаление дубликатов, разделение на обучающую и валидационную выборки, проведено масштабирование) (pandas)
  2. Проведен анализ и сравнение данных по трем регионам, изучены корреляции. (pandas, seaborn)
  3. Обучена модель линейной регрессии. (Sklearn)
  4. Проведен анализ прибыли и рисков (pandas, scipy): <br>
    - рассчитан достаточный объем прибыли для безубыточной разработки новой скважины;<br>
    - с помощью техники bootstrap рассчитана возможная прибыль;<br>
    - определен 95% доверительный интервал для средней прибыли по региону;<br>
    - рассчитаны риски убытков.<br>
  

_*Датасет предоставлен Яндекс.Практикумом в целях обучения._
