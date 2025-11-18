# Taxicab-Linear-Regression
Этот учебный проект следует [ноутбуку](http://www.overleaf.com) с домашним заданием с курса ["Машинное обучение 1"](https://github.com/esokolov/ml-course-hse/tree/master/2020-fall) Е. Соколова и соотвествующего соревнования на [Kaggle](https://www.kaggle.com/c/nyc-taxi-trip-duration/overview) в котором нужно было предсказать длительность поездки на такси по имеющимся данным.

В этом проекте использовалась *линейная регрессия*
$a(x) = w \cdot x$ и лучший результат получился с $L_2$ регуляризацией. Основная работа пришлась на доработку признаков которые описаны более детально в [description.pdf]([https://github.com/CunningNobleman/library/blob/main/pylint_report.txt](https://github.com/CunningNobleman/Taxicab-Linear-Regression/blob/main/description.pdf)).
В результате оценка качества RMSE после логарифмирования таргета вышла: \
$$RMSE_{test} = 0.478,$$ \
на обучающей выборке: \
$$RMSE_{train} = 0.451.$$ \
Для сравнения RMSE для константного предсказания — среднего значения на тестовой выборке: \
$$RMSE_{mean} = 0.797,$$ \
лучшее RMSLE в соревновании  \
$$RMSLE_{top} = 0.289.$$ \
В самом соревновании используется метрика RMSLE.
