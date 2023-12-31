#### Чертане на долната част на диаманта

Рисуването на долната част е доста подобна на рисуването на горната част. Разликите са, че вместо да намаляваме **`leftRight`** с 1 към края на цикъла, ще увеличаваме **`leftRight`** с 1 в началото на цикъла. Също така, **цикълът ще е от 0 до `(n - 1) / 2`**.   

![](/assets/chapter-6-images/10.Diamond-01.png)

<table><tr><td><img src="/assets/alert-icon.png" style="max-width:50px" /></td>
<td><b>Повторението на код се смята за лоша практика</b>, защото кодът става доста труден за поддръжка. Нека си представим, че имаме парче код (напр. логиката за чертането на ред от диаманта) на още няколко места и решаваме да направим промяна. За целта би било необходимо да минем през всичките места и да направим промените. Нека си представим, че трябва да използвате код не 1, 2 или 3 пъти, а десетки пъти. Начин за справяне с този проблем е като се използват <b>методи</b>. Можете да потърсите допълнителна информация за тях в Интернет, или да прегледате <a href="chapter-10-methods.md">глава “10” (Методи)</a>.</td>
</tr></table>

Ако сме написали всичко коректно, задачата ни е решена.

#### Тестване в Judge системата

Тествайте решението си тук: [https://judge.softuni.org/Contests/Practice/Index/512#9](https://judge.softuni.org/Contests/Practice/Index/512#9).