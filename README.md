# Отчёт о тестировании приложения "Precision"

## Краткое описание

Было проведено функциональное тестирование  подсчета бонусов в приложении Precision, в результате которого обнаружена неточность суммирования бонусов в переменной totalBonus.
В результате заведен [баг-репорт](https://github.com/Ingask/Homeworkjava0202/issues/1#issue-704423576) и дана рекомендация  добавить в код  выведение  переменной totalBonus типа double  в виде 0,0

## Описание тестов

Проведено функциональное тестирование основного функционала подсчета бонусов и точности отображения результата

## Результаты

1. 100% не успешных тестов
2. [Неточный результат при суммировании бонусов в приложении Precision](https://github.com/Ingask/Homeworkjava0202/issues/1#issue-704423576)

## Общие рекомендации

В коде необходимо добавить выведение  переменной totalBonus типа double  в виде 0,0
