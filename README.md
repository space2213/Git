### Klonowanie repozytorium
## Wchodzicie do odpowiednio przygotowanego folderu i kopiujecie repozytorium

``` bash
git clone git@github.com:ALF1-RZIT/Unitree-G1-Prz.git
```
## Utworzenie nowego brancha
``` bash
git branch [nazwa-brancha]
```

## Sprawdzenie na którym branchu jesteś *
``` bash
git branch
```
## Przejście na swojego brancha

``` bash
git switch [nazwa-brancha]
```
## Dodanie plików do brancha (Aby wrzucić coś na gita zaczynamy od tego momentu)
```bash
git add .
```

## Zrobienie commita z komentarzem
```bash
git commit -m "Komentarz"
```

## Zrobienie pusha swojego brancha
```bash
git push origin [nazwa-brancha]
```

## Wykonanie wszystkiego w jdnej komendzie:

```bash
git add .
git commit -m "Dodanie poradników i klucza SSH"
git push
```

## Pobranie zmian z maina do siebie
```bash
git switch main
git pull origin main

```

## Wykonanie clone 

```bash
git clone git@github.com:ALF1-RZIT/ROS2_bridge.git
```
