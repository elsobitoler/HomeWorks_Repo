# Туториал по работе с Git

## Начало работы

Для начала работы, необходимо инициализировать сам Git

Для его инициализации введите команду 

```
  git init
```

## Добавление файла

Для добавления файла в Git необходимо воспользоваться командой 

```
git add название файла
```
## Фиксирование изменеия файла
Для сохранения (фиксирования) текущей версии файла после изменений

```
git commit -m "комментарий к изменению"
```
## Выведение необходимой сохраненной версии

```
git checkout код фиксации
```
## Выведение списка сохраненных версий

```
git log
```
# Команды для работы с удаленными репозиториями

## Клонирование внешнего репозитория на локальеный ПК

```
git clone <url-фдрес репозитория>
```
## Получение изменений и слияние с локальной версией

```
git pull
```
## Отправить локальную весрию репозитория на внешний

```
git push
```
## Отображение всех установленных удаленных соеджинений
```
git remote -v
```
## Выделение текста 
*другое слово*

**полужирный**

## Списки

* spisok1
* spisok2
* spisok3

1. spisok11
2. spisok22
3. spisok33

Знаки для оформления тектса:

жирный текст -**

крусивный текст-*

зачеркнутый текст -~

заголовок #- в начале строки

заголовок поменьше-##

нумерация просто цифры

ненумерованные списки * в начале

вложенные списки- выполняем отступы

Показать уровень загловка- подчеркивание знаками = или -



# Туториал (справка) для работы с языком  разметки MarkDown



## Заголовки
Абзацы создаются при помощи пустой строки. Если вокруг текста сверху и снизу есть пустые строки, то текст превращается в абзац.

Чтобы сделать перенос строки вместо абзаца,  
нужно поставить два пробела в конце предыдущей строки.

Заголовки отмечаются диезом `#` в начале строки, от одного до шести. Например:

# Заголовок первого уровня #
## Заголовок h2
### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6

В декоративных целях заголовки можно «закрывать» с обратной стороны.







## Цитаты
Цитаты оформляются как в емейлах, с помощью символа `>`.

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

Или более ленивым способом, когда знак `>` ставится перед каждым элементом цитаты, будь то абзац, заголовок или пустая строка:

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

В цитаты можно помещать всё что угодно, в том числе вложенные цитаты:

> ## This is a header.
>
> 1.   This is the first list item.
> 2.   This is the second list item.
>
> > Вложенная цитата.
>
> Here's some example code:
>
>     return shell_exec("echo $input | $markdown_script");








## Исходный код
В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале каждой строки.

Но в GitHub-Flavored Markdown (сокращенно GFM) есть более удобный способ: ставим по три апострофа (на букве Ё) до и после кода. Также можно указать язык исходного кода.

```python
async def chiter(ctx):
    await ctx.send("Ну здрасте")

```







## Таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM есть.

First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

Для красоты можно и по бокам линии нарисовать:

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

Можно управлять выравниванием столбцов при помощи двоеточия.

| Left-Aligned  | Center Aligned  | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is      | some wordy text |     **$1600** |
| col 2 is      | centered        |         $12   |
| zebra stripes | are neat        |        ~~$1~~ |

Внутри таблиц можно использовать ссылки, наклонный, жирный или зачеркнутый текст.

Для всего остального есть обычный HTML.
