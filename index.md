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


# Туториал для работы с языком разметки Markdown

## Заголовки

# Заголовок первого уровня #
## Заголовок h2
### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6

## Списки

Для разметки неупорядоченных списков можно использовать или `*`, или `-`, или `+`:

- элемент 1
- элемент 2
- элемент ...

Вложенные пункты создаются четырьмя пробелами перед маркером пункта:

* элемент 1
* элемент 2
    * вложенный элемент 2.1
    * вложенный элемент 2.2
* элемент ...

Упорядоченный список:

1. элемент 1
2. элемент 2
    1. вложенный
    2. вложенный
3. элемент 3
4. Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.

На самом деле не важно как в коде пронумерованы пункты, главное, чтобы перед элементом списка стояла цифра (любая) с точкой. Можно сделать и так:

0. элемент 1
0. элемент 2
0. элемент 3
0. элемент 4

Список с абзацами:

* Раз абзац. Lorem ipsum dolor sit amet, consectetur adipisicing elit.

* Два абзац. Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.

* Три абзац. Ea, quis, alias nobis porro quos laborum minus sed fuga odio dolore natus quas cum enim necessitatibus magni provident non saepe sequi?

    Четыре абзац (Четыре пробела в начале или один tab).

## Горизонтальная черта


`hr` создается тремя звездочками или тремя дефисами.

***

## Ссылки

Это встроенная [ссылка с title элементом](http://example.com/link "Я ссылка"). Это — [без title](http://example.com/link).

А вот [пример][1] [нескольких][2] [ссылок][id] с разметкой как у сносок. Прокатит и [короткая запись][] без указания id.

[1]: http://example.com/ "Optional Title Here"
[2]: http://example.com/some
[id]: http://example.com/links (Optional Title Here)
[короткая запись]: http://example.com/short