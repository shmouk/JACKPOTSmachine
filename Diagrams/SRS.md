# Содержание
1. [Диаграмма прецедентов](#1)<br>
1.1 [Актеры](#1.1)<br>
1.2 [Варианты использования](#1.2)<br>
1.2.1 [Обновить точки](#1.2.1)<br>
1.2.2 [Запустить/приостановить отслеживание  местоположения](#1.2.2)<br>
1.2.3 [Добавить точку](#1.2.3)<br>
    
    
## 1. Диаграмма прецедентов<a name="1"></a> 

![Диаграмма прецедентов](https://github.com/NikitaKapitanov750503/NaviSport/blob/master/%D0%94%D0%B8%D0%B0%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D1%8B/Use%20case/UseCaseDiagram.jpg)


## 1.1 Актёры<a name="1.1"></a>

| Актёр | Описание |
|:--|:--|
| Пользователь | Человек, использующий приложение |

## 1.2 Варианты использования<a name="1.2"></a>

#### 1.2.1 Обновить точки<a name="1.2.1"></a>
**Описание.** Вариант использования "Обновить точки" позволяет пользователю загрузить на карту добавленные точки.

Поток выполнения:
1. Пользователь нажимает на кнопку "Update points".
2. Происходит отображение новых точек на карте.
3. Конец.

#### 1.2.2 Запустить/приостановить отслеживание местоположения<a name="1.2.2"></a>
**Описание.** Позволяет пользователю управлять возможностью работы с геоданными.

Поток выполнения:
1. Пользователь нажимает на кнопку "Get location".
2. Происходит приостановка/запуск отслеживания с последующим удалением/созданием маячка над местоположением пользователя.
3. Конец.

#### 1.2.3 Добавить точку<a name="1.2.3"></a>
**Описание.** Позволяет пользователю добавить новую путевую точку.

Поток выполнения:
1. Пользователь нажимает на кнопку "Add point".
2. Происходит открытие нового окна, в котором пользователю будет предложено выбрать параметры новой точки.
3. Пользователь вводит необходимую информацию.
4. Происходит добавление новой путевой точки в память.
5. Конец.