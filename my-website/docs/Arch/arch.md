---
title: Архитектура
hide_table_of_contents: true
---

import Drawio from '@theme/Drawio'
import diagram1 from '!!raw-loader!./HWmodelc1.drawio';
import diagram2 from '!!raw-loader!./HWmodelc2.drawio';



# Архитектура

:::note
Не буду делать описание архитектуры, буду менять архитектуру ИС там видно будет, внизу просто в качестве примера добавил старые диаграммы C4
:::

## C1

:::note
<Drawio content={diagram1} editable={false} />
:::

## C2

:::note
<Drawio content={diagram2} editable={false} />

:::

## Внешние зависимости

:::note
По интеграциям тоже не понятно, решил убрать огромное кол-во внешних сервисов
:::

| Сервис | Тип интеграции | Описание |
| ------ | -------------- | -------- |
| Создания кошелька      | RESTful API              |  блаблабла        |
| Истории операций      | RESTful API              |  блаблабла        |