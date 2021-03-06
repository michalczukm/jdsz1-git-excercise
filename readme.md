# Git - ćwiczenie grupowe
# Przedstaw się!
Celem ćwiczenia jest zbudowanie całą drużyną pliku .json który zawiera podstawowe informacje o was.

## Plik
Każda drużyna dostaje jeden plik - odpowiednio `a-team.json`, `b-team.json` itd.

:warning: :warning:	 **Musicie założyć plik dla waszej drużyny** :wink:

Plik jest w formacie:
```
{
   "team": {
      "version": "{your file version}",
      "members": {
         "member": [
            {
               "name": "{your name}",
               "surname": "{your surname}",
               "text": "Michał"
            }
         ]
      },
      "name": "{your team name}"
   }
}
```

Przykładowe uzupełnienie pliku:
```
{
   "team": {
      "version": "3",
      "members": {
         "member": [
            {
               "name": "Michał",
               "surname": "Michalczuk",
               "text": "Michał"
            },
            {
               "name": "Agata",
               "surname": "Agatowska",
               "text": "Aga"
            },
            {
               "name": "Maciej",
               "surname": "Kowalski",
               "text": "Macias"
            }
         ]
      },
      "name": "ISA-MM-1"
   }
}

```

## Zadanie
Waszym zadaniem jest uzupełnić ten plik. Ale jest parę reguł:
* każdy może dodać tylko swoje dane - tj autor commita musi się pokrywać z dodaną osobą
* każda zmiana składu musi być w oddzielnym commicie
* jeśli plik się zmienia (poprzez commit) należy podnieść wersję pliku o 1 - na początku jest 1
* gotowy plik można wrzucić do brancha `master` tylko przez `Pull Request` na GitHub'ie !
* branch zespołu powinien się nazywać `hello-nazwa-zespolu`

### Część A
Wybierzcie czy chcecie pracować na jednym branchu, czy założyć wiele (per user) i wpiszcie członków drużyny wg powyższych reguł.

Które rozwiązanie jest dla was lepsze? Jakie problemy napotkaliście?

### Część B
Wystawcie **jednego** `Pull Requesta` do repozytorium, do brancha master z danymi waszej drużyny.

Pull requesty sprawdzimy wspólnie na koniec i je zmergujemy.

#infoshare-academy/git