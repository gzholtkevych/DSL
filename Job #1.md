**Припустимо**, що мається множина `whitespaces`, яка містить символи, що розпізнаються як
розділювачі, що не розглядаються як токени.

Також мається змінна `text`, що посилається

- або на рядок,
- або на ім'я текстового файлу.

**Необхідно** написати функцію, яка перетворює текст з `text` на список рядків, такий що

1. всі символи, що не входять у `whitespaces` зустрічають у рядку, який дорівнює
конкатенації рядків вихідного списку, у том ж порядку, що й у вхідному тексті;
1. рядки вихідного списку не містять елементів множини `whitespaces`.

При цьому має бути забезпечено нечутливість коду функції до змін множини `whitespaces`. 
