> [!NOTE]
> Pentru a redacta cu ușurință soluția, apasă tasta `.` de pe tastatură sau deschide acest assignment în [github.dev](https://github.dev).

# Beculețe

> Limită timp: 0.1s \
> Limită memorie: 64KB

## Obiectiv
Iarna aceasta, Alina vrea să împodobească bradul de Crăciun cu o ghirlandă formată din beculețe roșii și verzi. Pe Alina nu o interesează ordinea în care sunt aranjate beculețele, atâta timp cât **nu există două beculețe verzi situate unul lângă altul**.
Ea ar vrea să știe, dându-se numărul *n*, lungimea ghirlandei, în câte moduri (modulo $1000000007$) pot fi montate beculețe roșii și verzi pe aceasta (considerând că Alina are la dispoziție oricâte beculețe de oricare fel).

## Input
Se citește din fișierul `input.txt` numărul $n$, numărul de beculețe care pot fi montate pe ghirlandă.

## Output
Se scrie în fișierul `output.txt` numărul $k \mod 1000000007$, numărul de modele diferite ce se pot forma pe ghirlandă, astfel încât să nu existe beculețe verzi adiacente. Două modele se consideră diferite dacă, între ele, diferă culoarea luminii măcar pe o poziție.

## Restricții
* $0 < n < 2000000000$
* pentru 20 pt., $0 < n < 15$
* pentru încă 60 pt., $15 <= n < 100000$

## Exemplul 1
### Input
```
2
```
### Output
```
3
```
### Explicație
Există următoarele posibilități de a configura o ghirlandă cu 2 beculețe:
1. 🔴🔴
2. 🔴🟢
3. 🟢🔴

## Exemplul 2
### Input
```
3
```
### Output
```
5
```
### Explicație
Există următoarele posibilități de a configura o ghirlandă cu 3 beculețe:
1. 🔴🔴🔴
2. 🔴🔴🟢
3. 🔴🟢🔴
4. 🟢🔴🔴
5. 🟢🔴🟢






