# New Service Projekt: Nowa usługa medyczna

![Logo projektu](assets/logo_projekt.png)

## **Opis**
Projekt koncepcyjny dotyczący wdrożenia usługi telekonsultacji medycznych.
Zawiera analizę procesu, ryzyk oraz plan wdrożenia.

## **Pliki**
- opis_usługi.txt – opis koncepcji usługi, jej zakresu oraz głównych założeń.
- plan_wdrożenia.txt – etapy wdrożenia usługi, w tym przygotowanie, testowanie i uruchomienie.
- ryzyka.txt – identyfikacja potencjalnych zagrożeń (technicznych i organizacyjnych).

## **Instrukcja pracy z repozytorium**

### **Klonowanie repozytorium**
```bash
git clone git@github.com:pd5359-sys/new_service.git
```
### **Przejście do katalogu projektu**
```bash
cd new_service
```
### **Sprawdzenie dostępnych gałęzi**
```bash
git branch
```
### **Przełączenie na inną gałąź**
```bash
git checkout marketing
```
### **Pobranie najnowszych zmian z GitHub**
```bash
git pull
```
### **Dodawanie nowych plików do repozytorium**
```bash
git add .
git commit -m "Opis zmian"
```
### **Wysłanie zmian do repozytorium zdalnego**
```bash
git push
```
### **Przywracanie wcześniejszych wersji**
Wyświetlenie historii commitów:
```bash
git log
```
Przywrócenie wybranego pliku:
```bash
git checkout nazwa_commita -- nazwa_pliku
```
## **Użyte komendy**
- git init – inicjalizacja repozytorium
- git add – dodawanie plików do obszaru staged
- git commit – zapisywanie zmian w historii projektu
- git branch – zarządzanie gałęziami
- git checkout – przełączanie się między gałęziami i wersjami
- git merge – scalanie zmian między gałęziami
- git log – przegląd historii commitów
- git reset – przywracanie wcześniejszych wersji repozytorium
- git merge

## **Napotkane problemy**

Podczas pracy wystąpiły problemy z konfiguracją klucza SSH oraz autoryzacją połączenia z GitHub. Problem został rozwiązany poprzez ponowne dodanie klucza SSH do konta GitHub i konfigurację ssh-agent.
