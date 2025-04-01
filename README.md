Задание по Git

1) Перенес установку "@types/node" из коммита A в коммит B
Использовал git rebase для открытия интерактивного окно и помечания нужного коммита для изменения
Все нужные изменения перенес из коммита A в коммит B 
Коммит B перенес в ветку development при помощи git cherry-pick
Обновил ветку feature/add-ant-design по development и влил ее туда 

2) Обновить ветку feature/add-ant-design по development, а после влил ее в development
Переходил на нужные ветки с помощью команды git checkout feature/add-ant-design 
И сливал их с веткой development

Слил ветки feature/core, feature/calculator, feature/calculator-actions в development

3) Применил патчи к Calculator.tsx
При помощи команды git apply (имя файла) добавлял патчи в код в нужной последовательности, чтоб не было конфликтов

4) Создал репозиторий на гитхаб и выпустил релиз в формате SemVer 
