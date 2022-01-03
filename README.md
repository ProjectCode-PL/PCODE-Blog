# PCODE Blog

Jest to oficjalne repozytorium postów [bloga ProjectCode](https://blog.projectcode.pl).

# Jak edytować posta
Zauważyłeś błąd i chcesz go poprawić? Wystarczy, że naniesiesz poprawki, zrobisz pull request oraz poczekasz na akceptację. 

# Jak napisać własnego posta
Posiadasz jakąś wiedzę, którą chcesz się podzielić? Możesz napisać <b>własnego posta</b>. W tym celu wystarczy, że zrobisz pull request z odpowiednim plikiem.
## Struktura pliku
Podczas pisania posta musisz zachować <b>odpowiednią strukturę oraz rozszerzenie pliku</b>. Wpis należy zapisać w rozszerzeniu <u>.md</u>. Poniżej template do skopiowania:
```
---
id: post-id
title: Post title
categories:
- category 1
- category 2
- category 3
authors:
- author 1
- author 2
- author 3
---

post content here...
```

| id | title | categories | authors |
| :-: | :-: | :-: | :-: |
| Jest to unikalne ID posta. Zostanie ono wyświetlone w <b>linku w przeglądarce</b>. | Tytuł posta | Lista kategorii do jakich zaliczach swój post | Nazwa użytkowników na GitHubie osób, które uczestniczyły w powstawaniu wpisu. Ważne, aby nick zgadzał się z twoimi danymi z GitHuba. |