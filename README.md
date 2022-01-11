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
introduction: Brief introduction to the post
date: 2022-01-01 00:00:00
image: images/foo/image.png
categories:
- category1
- category2
- category3
authors:
- author1
- author2
- author3
---

post content here...
```

| id | title | introduction | date | image | categories | authors |
| :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Jest to unikalne ID posta. Zostanie ono wyświetlone w <b>linku w przeglądarce</b>. | Tytuł posta. | Wpisz tutaj krótkie wprowadzenie do posta. | Należy tutaj wpisać datę powstania posta. Format daty znajduję się wyżej: ROK-MIESIĄC-DZIEŃ GODZINA:MINUTA:SEKUNDA. UWAGA! Zły format daty, lub zła data spowoduje odrzucenie prośby. | Link do zdjęcia posta, które zostanie wyświetlone w jego podglądzie. Można tutaj wpisać zarówno pełny link, jak i ścieżkę do obrazka z repozytorium. | Lista kategorii do jakich zaliczach swój post. | Nazwa użytkowników na GitHubie osób, które uczestniczyły w powstawaniu wpisu. Ważne, aby nick zgadzał się z twoimi danymi z GitHuba. |
