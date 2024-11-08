# Discord Crime Manager BOT
Jest to prosty w użyciu bot Discord głównie do pomocy przy serwerach FiveM, który ułatwi Ci prowadzenie serwera crime. Bot posiada zaawansowany system organizacji. BOT pozwoli głowie organizacji dodawać i usuwać członków jego organizacji oraz dodawać i usuwać zarząd organizacji. Dla opiekunów crime bot ma możliwość tworzenia, ostrzegania i zawieszania organizacji.

## Spis Treści
- [Instalacja](#instalacja)
- [Konfiguracja](#konfiguracja)
- [Użycie](#użycie)
- [Licencja](#licencja)
- [Autor](#autor)

## Instalacja
```
git clone https://github.com/Bartolinski4/Discord-Crime-Manager-Bot.git
cd crime_bot
npm install
```

## Konfiguracja
Aby ustawić bota pod swój serwer wejdz w plik [Config.js](config.js) i ustaw wszystkie rzeczy pod własne preferencje.


## Użycie
Bota używa się za pomocą poniższych komend:

- `/dodajczlonka <oznaczenie>` - Nadaje rolę organizacji oznaczonej osobie.
- `/dodajzarzad <oznaczenie>` - Nadaje oznaczonej osobie zarząd organizacji.
- `/usunczlonka <oznaczenie>` - Usuwa rolę organizacji oznaczonej osobie.
- `/usunzarzad <oznaczenie>` - Usuwa oznaczonej osobie zarząd organizacji.
- `/opuscorg` - Usuwa aktualną rolę organizacji (komenda dostępna dla wszystkich).
- `/orginfo` - Wyświetla listę i ilość osób na roli organizacji.
- `/utworzorg <nazwa org> <założyciel org>` - Tworzy organizację na Discordzie dla danej osoby.
- `/warn <organizacja> <powod> <dowod>` - Ostrzega organizację.
- `/zawias <organizacja> <czas> <powod/dowod>` - Zawiesza organizację na określony czas.


## Licencja
Ten projekt jest licencjonowany na warunkach licencji MIT - zobacz plik [LICENSE](LICENSE) po więcej informacji.


## Autor
Utworzono przez [Bartolinski](https://github.com/Bartolinski4). 

Jesli masz jakies problemy zglos sie do mnie w wiadomosci prywatnej na discodzie: [.bartolinski](https://discord.com/users/717048566396354582)
