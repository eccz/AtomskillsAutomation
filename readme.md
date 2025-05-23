# Автоматизация для Atomskills ИСТОК
Утилита автоматизирует рутинные операции при выполнении и проверке конкурсного задания на Atomskills в компетенции инженерное проектирование:
* Создание профиля отчета для CadLib Модель и Архив в соответствии с требованиями КЗ
* Создание профиля импорта параметров в CadLib Модель и Архив
* Создание профиля импорта IFC-модели в CadLib Модель и Архив
* Создание профиля экспорта модели из CadLib Модель и Архив в формат IFC в соответствии с требованиями КЗ
* Создание профилей спецификатора для приложений Model Studio

## Технологии
- [openpyxl](https://pypi.org/project/openpyxl/)
- [pyodbc](https://pypi.org/project/pyodbc/)
- [tkinter](https://docs.python.org/3/library/tkinter.html)
- [xml.etree.ElementTree](https://docs.python.org/3/library/xml.etree.elementtree.html)

## Использование
Софт работает на основе доработанных требований к ЦИМ в формате xlsx. Модифицированное приложение Д находится в директории src, можно использовать для примера.\
Конфигурационный файл config.json находится в директории config.

## Сборка 
Для сборки приложения с помощью PyInstaller:\
```pyinstaller --name "AS_Automation_v1.1" --add-data "config\config.json;." --add-data "readme.md;." --add-data "data\ADD_D_AS_2025_cleaned.xlsx:." app.pyw```

## To do
- [x] Добавить крутое README
- [x] Переработать структуру проекта
- [x] Доработать функционал по созданию спецификатора
- [ ] Добавить тесты
- [ ] Добавить функционал по созданию выборок

## Telegram
- [Степан Пантелеев](https://t.me/panteleevsv/)
