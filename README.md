# DengAI

Данная работа основана на соревновании: **https://www.drivendata.org/competitions/44/dengai-predicting-disease-spread/**
    
---
    
**Акцент** в исследовании сделан на ***feature engineering***, ***визуализацию признаков и прогнозов для временных рядов***, и ***тюнинг `CatBoostRegressor`***. Также были обучены `Lasso`, `RandomForest`. `SARIMAX` давал плохие прогнозы, поэтому в работе не представлен.
    
---   
    
**Задача**: Можете ли вы, используя данные об окружающей среде, собранные федеральными правительственными агентствами США, **предсказать число случаев лихорадки денге*, регистрируемых каждую неделю** в Сан-Хуане, Пуэрто-Рико, и Икитосе, Перу??
    
---
Метрика качества: ***MAE***

---

Итоговый результат: качество прогнозирования по **`MAE = 21.29`, занятое место = 436 (всего участников 15208**)
