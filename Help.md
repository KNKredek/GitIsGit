# O Gicie słów kilka(naście)

## Czym jest git?
Git 

## Instalacja i konfiguracja
Instalacja wygląda inaczej na każdym systemie:
 * Jeśli korzystamy z linuxa, korzystamy z apt:
 ```sudo apt-get update && sudo apt-get install git-core```
 * Jeśli korzystamy z mac os polecam skorzystać z managera paczek o nazwie [homebrew](https://brew.sh/):
 ```brew install git```
 * Jeśli korzystamy z windowsa możemy albo [pobrać instalkę](https://git-scm.com/download/win) albo skorzystać z [konsolowego managera paczek](https://chocolatey.org/): 
 ```choco install git```

Po zainstalowaniu uruchamiamy terminal (w przypadku linuxa oraz mac os) lub git basha (w windowsie). W dalszej części będę się posługiwał słowem terminal. Aby sprawdzić aktualnie używaną wersję gita używamy komendy: 
```
git --version
```
Początkowa konfiguracja gita składa się z podania nazwy naszego użytkownika, maila oraz (opcjonalnie) zmiany naszego edytora tesktowego(służy on do kilku operacji, o których później). Domyslnym edytorem jest vim, ja zmienię go sobie na nano :)
```
git config --global user.name "Jan Kowalski"
git config --global user.email "jan@kowalski.pl"
git config --global core.editor nano
```

## Pierwsze, lokalne repozytorium
Aby stworzyć nasze pierwsze repozytorium potrzebujemy pusty folder. Odpalamy w tym folderze terminal. Teraz, aby zrobić z naszego folderu repozytorium korzystamy z komendy 
```
git init
```
Komenda ta zainicjalizowała nam repozytorium w folderze, w którym się aktualnie znajdujemy. Teraz tworzymy sobie w naszym folderze plik (może byc tekstowy) z jakąs zawartoscią. 

## Zdalne repozytorium i sposoby uwierzytelniania

## Gitignore

## Branche

## Merge i rebase

## Workflow