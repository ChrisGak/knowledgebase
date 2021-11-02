# knowledgebase
knowledgebase is an available source of questions and answers on IT self development

## Commercial Project Experience
* Проф. увлечения в свободное время
* Какие книги/ресурсы читаете, читали 
* Как представляете себе процесс разработки ПО 

## ООП
* Что такое ООП? Назовите принципы ООП и расскажите о каждом
* Что такое класс, объект?

## HTML & CSS
See [Готовимся к собеседованию по фронтенду: 15 вопросов](https://habr.com/ru/company/ruvds/blog/518512/)
See [Front-end-Developer-Interview-Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions)
* Какая разница между элементами span и div?
>
```
<span> — это строчный (inline) элемент.
<div> — это блочный (block) элемент.
```
> Элементы div нужно использовать для оформления разделов документа. А элементы span — в роли контейнеров для небольших объёмов текста, для изображений и других подобных элементов страниц.

* Основные отличия блочных и строчных элементов?
>Строчные элементы могут содержать только данные или другие строчные элементы, а в блочные допустимо вкладывать другие блочные элементы, строчные элементы, а также данные. Иными словами, строчные элементы никак не могут хранить блочные элементы.
Блочные элементы всегда начинаются с новой строки, а строчные таким способом не акцентируются. Блочные элементы занимают всю доступную ширину, например, окна браузера, а ширина строчных элементов равна их содержимому плюс значения отступов, полей и границ

* Какая разница между селекторами идентификаторов и классов в CSS?

## Javascript
See [Шпаргалка по современному JavaScript](https://tproger.ru/translations/javascript-cheatsheet/)
See [Вопросы и ответы к собеседованию фронтенд-разработчика на JavaScript](https://medium.com/@allaev/%D0%B2%D0%BE%D0%BF%D1%80%D0%BE%D1%81%D1%8B-%D0%B8-%D0%BE%D1%82%D0%B2%D0%B5%D1%82%D1%8B-%D0%BA-%D1%81%D0%BE%D0%B1%D0%B5%D1%81%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D1%8E-%D1%84%D1%80%D0%BE%D0%BD%D1%82%D0%B5%D0%BD%D0%B4-%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D1%87%D0%B8%D0%BA%D0%B0-%D0%BD%D0%B0-javascript-9058a75710a)
* JavaScript  объектоориентируемый язык?
> да

* JavaScript  компилируемый язык?
>нет

* У компилируемых языков программирования что является результатов компиляции?
> байткод, машинный код

* Объясните, как this работает в JavaScript
* Что такое замыкание?

* Расскажите, как работает прототипное наследование
> Этот вопрос очень часто задают на собеседованиях. Все объекты в JavaScript имеют свойство prototype, которое является ссылкой на другой объект. Когда происходит обращение к свойству объекта, и если свойство не найдено в этом объекте, то механизм JavaScript просматривает прототип объекта, затем прототип прототипа и т.д. До тех пор, пока не найдет определенное свойство на одном из прототипов или до тех пор, пока он не достигнет конца цепочки прототипов. Такое поведение имитирует классическое наследование, но на самом деле это скорее делегирование, чем наследование.

* Объявление переменных: var, const, let - в чем разница?
See [Готовимся к собеседованию по фронтенду: 15 вопросов](https://habr.com/ru/company/ruvds/blog/518512/)
> Оператор var. Объявленные с его помощью переменные работают в пределах функции и не доступны вне её.
 Оператор let. Переменные, объявленные с его помощью, имеют блочную область видимости. Кроме того, они не доступны, пока не присвоены и пока их значение нельзя изменить в той же области.
 Оператор const. Переменные, объявленные с его помощью, также имеют блочную область видимости и не доступны до присвоения. Кроме того, их нельзя объявить или заново присвоить в той же области:
 
* Чем отличаются куки-файлы, сессионное хранилище и локальное хранилище?
> Локальное хранилище, как можно понять из его названия, это место, которое браузеры могут использовать для локального хранения данных. В нём может храниться до 10 Мб данных. Сессионное хранилище — это разновидность локального хранилища, которое привязано к сессии и удаляется после её завершения. В сессионном хранилище может храниться до 5 Мб данных.
 Куки-файлы используются для хранения небольших объёмов данных, не превышающих 4 Кб. Ими может пользоваться браузер, их может запрашивать у браузера сервер.
 
* Типы данных в Javascript?
See [Типы данных](https://learn.javascript.ru/types)
> В JavaScript есть 8 основных типов.  
  number для любых чисел: целочисленных или чисел с плавающей точкой; целочисленные значения ограничены диапазоном ±(253-1).
  bigint для целых чисел произвольной длины.
  string для строк. Строка может содержать ноль или больше символов, нет отдельного символьного типа.
  boolean для true/false.
  null для неизвестных значений – отдельный тип, имеющий одно значение null.
  undefined для не присвоенных значений – отдельный тип, имеющий одно значение undefined.
  object для более сложных структур данных.
  symbol для уникальных идентификаторов.
  Оператор typeof позволяет нам увидеть, какой тип данных сохранён в переменной.
  Имеет две формы: typeof x или typeof(x).
  Возвращает строку с именем типа. Например, "string".
  Для null возвращается "object" – это ошибка в языке, на самом деле это не объект.
 
* Какие значения в JavaScript являются ложными?
> В JavaScript ложными являются значения, которые, при преобразовании их к логическому типу, становятся значениями false. Это — следующие значения:
```
 '' 
 0 
 null
 undefined
 NaN
 false
 -0
 0n // значения типа BigInt, при преобразовании их к логическому типу, ведут себя так же, как значения типа Number
```
* Задачка что выведется в консоль?
```
console.log('b'+'a'+ + 'a' + 'a').toLowerCase()
```
* Задачка что выведется в консоль?
```
let obj = {'a': 5};

let f = (o) => o = {'a': 3};

f(obj);
console.log(obj.a);
```
* Как сделать так, чтобы console.log вернул 3, а не 5?
```
let obj = {'a': 5};

let f = (o) => o.a = 3;

f(obj);
console.log(obj.a);
```
> VM197:1 Uncaught TypeError: Cannot read property 'toLowerCase' of undefined
    at <anonymous>:1:34
## TypeScript
See [Собеседование по TypeScript: 20 вопросов и ответов](https://habr.com/ru/company/ruvds/blog/419993/)
* Что такое TypeScript?
> TypeScript is a typed superset of JavaScript created by Microsoft that adds optional types, classes, async/await, and many other features, and compiles to plain JavaScript. Angular built entirely in TypeScript and used as a primary language. You can install it globally as
```
npm install -g typescript
```

## Network, etc.
* Методы HTTP запроса
>See [Methods](https://developer.mozilla.org/ru/docs/Web/HTTP/Methods) 
HTTP определяет множество методов запроса, которые указывают, какое желаемое действие выполнится для данного ресурса. Несмотря на то, что их названия могут быть существительными, эти методы запроса иногда называются HTTP глаголами. Каждый реализует свою семантику, но каждая группа команд разделяет общие свойства: так, методы могут быть безопасными, идемпотентными или кешируемыми.
Метод GET запрашивает представление ресурса. Запросы с использованием этого метода могут только извлекать данные.
HEAD запрашивает ресурс так же, как и метод GET, но без тела ответа.
POST используется для отправки сущностей к определённому ресурсу. Часто вызывает изменение состояния или какие-то побочные эффекты на сервере.
PUT заменяет все текущие представления ресурса данными запроса.
DELETE удаляет указанный ресурс.
CONNECT устанавливает "туннель" к серверу, определённому по ресурсу.
OPTIONS используется для описания параметров соединения с ресурсом.
TRACE выполняет вызов возвращаемого тестового сообщения с ресурса.
PATCH используется для частичного изменения ресурса.

* Что такое REST?
> See [REST: простым языком](https://medium.com/@andr.ivas12/rest-%D0%BF%D1%80%D0%BE%D1%81%D1%82%D1%8B%D0%BC-%D1%8F%D0%B7%D1%8B%D0%BA%D0%BE%D0%BC-90a0bca0bc78)
(REpresentational State Transfer) — это архитектура, т.е. принципы построения распределенных гипермедиа систем, того что другими словами называется World Wide Web, включая универсальные способы обработки и передачи состояний ресурсов по HTTP

## Angular 
See [Angular Interview Questions & Answers](https://github.com/sudheerj/angular-interview-questions#what-is-angular-framework)
* Что такое Angular?
>Angular is a TypeScript-based open-source front-end platform that makes it easy to build applications with in web/mobile/desktop. The major features of this framework such as declarative templates, dependency injection, end to end tooling, and many more other features are used to ease the development.

* Назовите ключевые компоненты Angular
> Angular has the below key components,
Component: These are the basic building blocks of angular application to control HTML views.
Modules: An angular module is set of angular basic building blocks like component, directives, services etc. An application is divided into logical pieces and each piece of code is called as "module" which perform a single task.
Templates: This represent the views of an Angular application.
Services: It is used to create components which can be shared across the entire application.
Metadata: This can be used to add more data to an Angular class.

* Зачем нужна директива ngIf?
> Можете написать пример использования ngIf?
Например, вывести блок, если поле age у user > 18
```
<div *ngIf="user.age > 18">You are not eligible for student pass!</div>
```

* Зачем нужна директива ngFor?
> Можете написать пример использования ngFor (вывод элементов списка li и вывести поле user из массива users ):
```
<li *ngFor="let user of users">
  {{ user }}
</li>
```

* Что такое pipe?
>  pipe takes in data as input and transforms it to a desired output. For example, let us take a pipe to transform a component's birthday property into a human-friendly date using date pipe.
```
import { Component } from '@angular/core';

@Component({
  selector: 'app-birthday',
  template: <p>Birthday is {{ birthday | date }}</p>
})
export class BirthdayComponent {
  birthday = new Date(1987, 6, 18); // June 18, 1987
}
```

## RxJs
* Что такое реактивное программирование? 
> Реактивное программирование — программирование с асинхронными потоками данных
Поток — это последовательность событий, упорядоченная по времени. 
https://tproger.ru/translations/reactive-programming/
* Что такое RxJS?
>RxJS — это библиотека для JS, которая использует паттерн Observable (с англ. “Обозреваемый” / “Наблюдаемый”) для упрощения обработки и компановки асинхронного или callback кода.
 Для того, чтобы начать использовать RxJS в вашем коде необходимо выполнить две вещи: установить при помощи npm и подключить.
> npm install --save rxjs
 // внутри вашего компонента
 import { Observable } from 'rxjs';
See [RxJS с нуля, обзор “Обозреваемого”](https://medium.com/@toshabely/rxjs-%D1%81-%D0%BD%D1%83%D0%BB%D1%8F-%D0%BE%D0%B1%D0%B7%D0%BE%D1%80-%D0%BE%D0%B1%D0%BE%D0%B7%D1%80%D0%B5%D0%B2%D0%B0%D1%82%D0%B5%D0%BB%D1%8F-ca4d8e5fb386#:~:text=RxJS%20%E2%80%94%20%D1%8D%D1%82%D0%BE%20%D0%B1%D0%B8%D0%B1%D0%BB%D0%B8%D0%BE%D1%82%D0%B5%D0%BA%D0%B0%20%D0%B4%D0%BB%D1%8F%20JS,%D0%BF%D1%80%D0%B8%20%D0%BF%D0%BE%D0%BC%D0%BE%D1%89%D0%B8%20npm%20%D0%B8%20%D0%BF%D0%BE%D0%B4%D0%BA%D0%BB%D1%8E%D1%87%D0%B8%D1%82%D1%8C.)
* что такое Observable? 
> Observable — это последовательность событий во времени
>Анатомия Observable:
 ось времени,
 событие (шарик),
 ошибка (крестик),
 конец (вертикальная чёрточка).
> See [Observable в RxJS: краткое введение](https://medium.com/@kosmogradsky/observable-%D0%B2-rxjs-%D0%BA%D1%80%D0%B0%D1%82%D0%BA%D0%BE%D0%B5-%D0%B2%D0%B2%D0%B5%D0%B4%D0%B5%D0%BD%D0%B8%D0%B5-34939ff5f7d7)
* Оператор создания потока из массива.
> from
* Какую функцию надо вызвать, чтобы завершить Observable. 
> complete
* Какой Subject имеет значение по умолчанию. 
> BehaviorSubject
* У какой сущности вызывается метод unsubscribe(). 
> Subscription
* Какой оператор нужно использовать, чтобы взять 10 элементов из потока. 
> take(10)

## Алгоритмы и структуры данных
See [Big O](https://habr.com/ru/post/444594/)
See [10 типов структур данных, которые нужно знать + видео и упражнения](https://habr.com/ru/company/netologyru/blog/334914/)

* Что такое O большое в алгоритмах?
> Нотация О большое — это математическая нотация, которая описывает ограничивающее поведение функции, когда аргумент стремится к определенному значению или бесконечности. ... Типичным алгоритмом со сложностью O(n²) будет алгоритм сортировки выбором

* какие операции имеют сложность O(1)? 
> Корректнее описывать сложность через количество операций, выполняемых для достижения результата, в зависимости от ввода (операций на ввод).
Другими словами: насколько возрастет кол-во операций при увеличении кол-ва входных параметров.
 Для получения результата нужно выполнить одну операцию (взять элемент по индексу). Сколько операций потребуется если элементов массива будет 100? Или 1000? Или 100 000? Все равно нужна только одна операция.
Т.е.: «одна операция для всех возможных входных данных» — O(1).

* А какие операции имеют сложность O(n)? 
> Перебор коллекции это O(n)

* А какие O(n^2)?
> вложенные циклы по той же коллекции это O(n^2)

* Какие структуры данных можете назвать?
>Массив (Array)
Стек (Stack)
Очередь (Queue)
Связный список (Linked List)
Дерево (Tree)
Граф (Graph)
Префиксное дерево (Trie)
Хэш-Таблица (Hash Table)

* Написать сортировку пузырьком по убыванию
~~
function bubbleSort(arr) {
    for (var i = 0, endI = arr.length - 1; i < endI; i++) {
        for (var j = 0, endJ = endI - i; j < endJ; j++) {
            if (arr[j] < arr[j + 1]) {
                var swap = arr[j];
                arr[j] = arr[j + 1];
                arr[j + 1] = swap;
            }
        }
    }
    return arr;
}
~~

* Что будет, если сделать так?
```
function bubbleSort(arr) {
    for (var i = 0, endI = arr.length - 1; i < endI; i++) {
        for (var j = 0, endJ = endI - i; j < endJ; j++) {
            if (arr[i] < arr[j + 1]) {
                var swap = arr[i];
                arr[i] = arr[j + 1];
                arr[j + 1] = swap;
            }
        }
    }
    return arr;
}
```

* Если в массиве лежат числа с плавающей запятой, как лучше их сравнивать (например, касательно сортировки)?

##SQL
> Есть таблица учащихся с колонками ФИО, форма обучения
Написать SQL запрос, который вернет формы обучения и количество учащихся 
```
select form, count(*) from table
group by form
```
 
## Java
* Java Stream API Шпаргалка
https://habr.com/ru/company/luxoft/blog/270383/ 

## Other
* Что такое Паттерны проектирования? Какие можете назвать?

## Fun Questions
* What's a cool project that you've recently worked on?
* What are some things you like about the developer tools you use?
* Who inspires you in the front-end community?
* Do you have any pet projects? What kind?
* What's your favorite feature of Internet Explorer?
See [Fun Questions](https://github.com/h5bp/Front-end-Developer-Interview-Questions/blob/master/src/questions/fun-questions.md)
 
