# __I'm learning Markdown markup language__
## Lesson one <br>
### Contents: <br>
#### - *Introductory section* <br>
#### - *Syntax contents* <br>
#### - *Rules of use*

## Lesson two <br>
### Contents: <br>
#### - *Create document* <br>
#### - *Modify document* <br>
#### - *Delete a document*
***
***

## заголовки с 1 по 6 уровней

# New Document
## New Document
### New Document
#### New Document
##### New Document
###### New Document


## ненумерованный список

* New Document
- New Document
+ New Document

## нумерованный список

1. New Document
1. New Document
1. New Document


33. New Document
33. New Document
33. New Document

## чекбоксы

* [x] New Document
* [ ] New Document


## курсив

*New Document*

_New Document_



## жирный

**New Document**

__New Document__


## жирный курсив

***New Document***

___New Document___


## выделить фрагмент внутри слова

New *Document*, **New** Docu*ment*, New ***Document***


## зачеркнутый

~~New Document~~


## подчеркнутый

<u>New Document</u>


## разделители

***
---
___

**  *  ***


## цитаты

New Document
> New Document
>> New Document
>>> New Document
>
New Document

## ссылки

[New Document](https://jbt.github.io/markdown-editor/) без подсказки

[New Document](https://jbt.github.io/markdown-editor/ "всплывающая подсказка") с подсказкой


## сноски на ссылки

[New Document][1]


[New Document_code][code]

[1]: https://jbt.github.io/markdown-editor/ "всплывающая подсказка"

[code]: https://jbt.github.io/markdown-editor/


## картинки

[кот псих](https://www.google.ru/imgres?q=кот%20псих&imgurl=https%3A%2F%2Fwww.m24.ru%2Fb%2Fd%2FnBkSUhL2hFYnnMe-JL6BrNOp2Z318Ji-mijFnuWR9mOBdDebBizCnTY8qdJf6ReJ58vU9meMMok3Ee2nhSR6ISeO9G1N_wjJ%3DURzjlfmSHE-1ptig4pTBsw.jpg&imgrefurl=https%3A%2F%2Fwww.m24.ru%2Farticles%2Fnauka%2F04122021%2F158922&docid=PC3BtiD56ts2uM&tbnid=-9ksXYb4koTC-M&vet=12ahUKEwjc9_fGoKKLAxVT1wIHHWO9OaIQM3oECBoQAA..i&w=1200&h=900&hcb=2&ved=2ahUKEwjc9_fGoKKLAxVT1wIHHWO9OaIQM3oECBoQAA "кот псих")

## вставка кода

Функция `print (x)` выводит содержимое переменной ```x```.

```
#include <stdio.h>
int main() {
   printf("Hello, World!");
   return 0;
}
```

	let x = 12;
	let y = 6;
	console.log(x + y);
    
    
Если обрамлять код тремя обратными апострофами, то после первой тройки можно указать язык программирования — тогда Markdown правильно подсветит элементы кода.
    
 ```python
if x > 0:
	print (x)
else:
	print ('Hello, World!')
```

```c
#include <stdio.h>
int main() {
   printf("Hello, World!");
   return 0;
}
```

```javascript
let x = 12;
let y = 6;
console.log(x + y);
```

## таблицы


|Столбец 1|Столбец 2|Столбец 3|
|-|--------|---|
|Длинная запись в первом столбце|Запись в столбце 2|Запись в столбце 3|
|Кртк зпс| |Слева нет записи|

**Выравнивание:**
Чтобы выровнять весь столбец по правому краю, в строке с дефисами сразу после дефисов можно поставить двоеточие :. Чтобы выровнять содержимое по центру, надо поставить двоеточия с обеих сторон.

|Столбец 1|Столбец 2|Столбец 3|
|:-|:-:|-:|
|Равнение по левому краю|Равнение по центру|Равнение по правому краю|
|Запись|Запись|Запись|
