## Прогнозирование оттока клиентов.

**Целью** данного проекта является прогнозирование вероятности прекращения пользования услугами мобильного оператора.

Получены следующие **результаты** исследования: 
- оптимальная модель `LightGBMClassifier` имеет следующие гиперпараметры: количество деревьев `n_estimators=190`, шаг обучения `learning_rate=0.1`
- метрика `roc_auc_score` составляет `0.95`, метрика `f1_score` для отрицательного и положительного класса составляет `0.93` и `0.98` соответственно.

В процессе выполнения проекта были задействованы следующие **библиотеки**: `LightGBMClassifier`,`Pandas`,`Matplotlib`, `Sklearn`, `NumPy`. 

**Статус проекта**: завершен в полном объеме.
