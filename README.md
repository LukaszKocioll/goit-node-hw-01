# Kontakty

Aplikacja Kontakty umożliwia zarządzanie listą kontaktów poprzez dodawanie, wyświetlanie, usuwanie i pobieranie informacji kontaktowych.


### Wyniki

#### Lista

Wyświetlanie listy

1. Aby wyświetlić listę wszystkich kontaktów użyj polecenia:

2. node index.js --action list

![list](/images/list.png "List")

#### Otrzymywanie kontatków

Filtrowanie

1. Aby pobrać szczegółowe informacje o konkretnym kontakcie użyj polecenia wraz z jego ID:

2. node index.js --action get --id ""

![get](/images/get.png "Get")

#### Dodawanie

Dodawanie kontaktu

1. Aby dodać nowy kontakt użyj polecenia:

2. node index.js --action add --name Jan --email jan@kowalski.com --phone 123-12-12

![add](/images/add.png "Add")

#### Usuwanie

Usuwanie kontaktów

1.  Aby usunąć kontakt na podstawie jego ID użyj polecenia:

2. node index.js --action remove --id " "

![remove](/images/remove.png "Remove")



