# Содержание
1. [Диаграмма прецедентов](#1)<br>
1.1 [Актеры](#1.1)<br>
1.2 [Варианты использования](#1.2)<br>
1.2.1 [Сохранить прогресс](#1.2.1)<br>
1.2.2 [Изменить пользователя](#1.2.2)<br>
1.2.3 [Создать пользователя](#1.2.3)<br>
1.2.4 [Играть в Black Jack](#1.2.4)<br>
1.2.5 [Играть в Slots](#1.2.5)<br>
1.2.6 [Играть в Roulette](#1.2.6)<br>
    
    
## 1. Диаграмма прецедентов<a name="1"></a> 

![Диаграмма прецедентов](https://github.com/shmouk/JACKPOTSmachine/blob/master/Diagrams/UseCase/UseCase.png)


## 1.1 Актёры<a name="1.1"></a>

| Актёр | Описание |
|:--|:--|
| Пользователь | Человек, использующий приложение |

## 1.2 Варианты использования<a name="1.2"></a>

#### 1.2.1 Сохранить прогресс<a name="1.2.1"></a>
**Описание.** Вариант использования "Сохранить прогресс" позволяет пользователю сохранить прогресс пользователя.

Поток выполнения:
1. Пользователь нажимает на кнопку "Save".
2. Происходит сохранение пользователя.
3. Конец.

#### 1.2.2 Изменить пользователя<a name="1.2.2"></a>
**Описание.** Позволяет управлять пользователями работы.

Поток выполнения:
1. Пользователь нажимает на кнопку "Change User".
2. Появляется список пользователей из которого можно выбрать интересующего.
3. Конец.

#### 1.2.3 Создать пользователя<a name="1.2.3"></a>
**Описание.** Позволяет пользователю добавить нового пользователя.

Поток выполнения:
1. Пользователь нажимает на кнопку "New user".
2. Происходит открытие нового окна, в котором пользователь вводит необходимую информацию.
3. Происходит добавление нового пользователя в память.
4. Конец.

#### 1.2.4 Играть в Black Jack<a name="1.2.4"></a>
**Описание.** Позволяет запустить игру Black Jack.

Поток выполнения:
1. Пользователь нажимает на кнопку "Black Jack".
2. Запускается игра.
3. Конец.

#### 1.2.5 Играть в Slots<a name="1.2.5"></a>
**Описание.** Позволяет запустить игру Slots.

Поток выполнения:
1. Пользователь нажимает на кнопку "Slots".
2. Запускается игра.
3. Конец.

#### 1.2.6 Играть в Roulette<a name="1.2.6"></a>
**Описание.** Позволяет запустить игру Roulette.

Поток выполнения:
1. Пользователь нажимает на кнопку "Roulette".
2. Запускается игра.
3. Конец.
