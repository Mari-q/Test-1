**1**. Умыться
**2**. Помыться
**3**. Позавтракать.
# Инструкция по работе с GIT![GIT](tl1hxlu6ufwx0kbhpzim.webp) 
## Основные команды Git ##

* **git init** – инициализация локального репозитория

* **git status** – получить информацию от git о его текущем состоянии

* **git add** – добавить файл или файлы к следующему коммиту

* **git commit -m “message”** – создание коммита.

* **git log** – вывод на экран истории всех коммитов с их хеш-кодами

* **git checkout** – переход от одного коммита к другому

* **git checkout master** – вернуться к актуальному состоянию и продолжить работу

* **git diff** – увидеть разницу между текущим файлом и закоммиченным файлом

## Синтаксис языка ***Markdown*** ## 

*Ссылка на*
 [Справочник по Markdown от Microsoft](https://docs.microsoft.com/ru-ru/contribute/markdown-reference) 

* **# Заголовок** – выделение заголовков. Количество символов *“#”* задаёт уровень заголовка  (поддерживается 6 уровней).

* **= или -** – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки  *первого (“=”)* и *второго (“-”)* уровней.

*  ** **Полужирное начертание** ** или __ __Полужирное начертание__ __

*   **Курсивное начертание* * или _ _Курсивное начертание_ _

* *** ***Полужирное курсивное начертание*** ***

* ~~ ~~Зачёркнутый~~ текст ~~

*  _*_  Строка – ненумерованные списки, символ **“*”** в начале строки

* **1, 2, 3 …** – нумерованные списки

## Оповещения ("Примечание", "Совет", "Важно!", "Внимание!", "Предупреждение")

## Краткое руководство по стилю документации

### Дополнительные рекомендации по стилю:
* Не отделяйте действия от комментариев или дополнительных пояснений.
* Для действий, содержащих фрагменты кода, вставляйте дополнительные сведения о действии в код в качестве комментариев. Это сокращает объем текста, который пользователи должны прочесть. Кроме того, ключевые сведения копируются в проект кода в качестве напоминания о задачах этого фрагмента, когда пользователям нужно будет вернуться к нему в будущем.
* Все заголовки нужно писать с большой буквы и без точки в конце.
* Используйте "войти" или "войти в систему" вместо альтернативных вариантов.
* Дополнительные рекомендации см. в руководстве по стилю написания документации Майкрософт.
## Столбцы
Таблица в Markdown может использоваться для представления сравнений данных пользователем.

Для создания таблицы в Markdown мы используем тире (-) и вертикальные полосы (|) для разделения строк и столбцов.

| Заголовок  | Заголовок   |
| ---------- | ----------- |
| Текст      | Текст       |
| Текст      | Текст       |

 ## Работе с удаленными репозиториями
 **git clone <url-адрес репозитория>** – клонирование внешнего репозитория на  локальный ПК

 **git pull** – получение изменений и слияние с локальной версией

**git push** – отправляет локальную версию репозитория на внешний.
