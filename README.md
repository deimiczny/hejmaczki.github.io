# MeinKraft - hejmaczki

Tutaj znajdziecie kilka ważnych informacji o naszym serwerze - adresy, pluginy i tak dalej. Generalnie to takie Readme hejmaczków.

## Adresy
- **Serwer:** hejmaczki.pl, (porty: java 20207, bedrock 32144)
- **Mapa:** <https://mapa.hejmaczki.pl>
- **Status serwera:** <https://status.hejmaczki.pl> (info czy ded + ile graczy obecnie gra)
- **Statystyki serwera:** <https://stats.hejmaczki.pl> (trzeba założyć usera i potwierdzić kodem w grze)
- **Dokumentacja:** <https://docs.hejmaczki.pl>
- **Discord:** <https://discord.gg/HU2K8shQ>

## Ogólne zasady

Garść ważnych zasad obowiązujących na serwerze plus kilka protipów:
- operatorzy to **deimiczny** oraz **WuJery13**
- obowiązuje whitelista - żeby zagrać, musisz zostać dodany/a. Skontaktuj się z opami.
- gramy w survivalu
- generalnie robimy co chcemy - budujemy, zwiedzamy, grillujemy i kochamy
- jesteśmy dla siebie mili. To nasz safespace.
- serwer obsługuje Bedrocka i Java Edition

## Pluginy

Na serwerze śmiga kilka przydatnych pluginów. Najważniejsze z nich:

### 🪢 Geyser

Umożliwia granie z Bedrocka. Jak? Po prostu w Bedrocku wpisujesz adres serwera, plus dedykowany port (znajdziesz w pierwszej sekcji tego dokumentu) i dołączysz do gry. Przy pierwszym dołączeniu gra poprosi Cię o weryfikację Twojego konta Microsoft/Minecraft.

### 🪧 Easy BlueMap Sign Markers

Umożliwia dodawania znaczników na mapie poprzez ustawianie znaków w grze. Tutaj więcej info: <https://modrinth.com/plugin/easy-bluemap-sign-markers>

#### Jak stawiać markery?

- Ustawiasz znak w grze, dowolny materiał
- W pierwszej linii wpisujesz `[costam]` - to definiuje marker jak i ustawia ikonkę. Lista ikonek dostępna tutaj: https://github.com/deimiczny/easy-bmapmarkers/blob/main/README.md#marker-names. Jak wpiszesz nazwę, która nie istnieje - i tak zadziała, będzie fallback (pinezka; nazwa `map`)
- W drugiej linii wpisujesz dowolny tekst albo nic
- W trzeciej linii wpisujesz dowolny tekst albo nic
- W czwartek linii wpisujsz dowolny tekst albo nic
- Jeśli **przynajmniej** w jednej linii od 2 do 4 znalazł się tekst - marker **zostanie** dodany na mapie (https://mapa.hejmaczki.pl). 
- Jeśli **każda** linia od 2 do 4 jest **pusta** - znak zostanie dodany w grze, ale marker **nie zostanie** dodany na mapie.


### 🧭 TeaWaypoints
Umożliwia ustawianie waypointów do szybkiego "teleportowania" się między nimi, coś jak fast travel w innych gierkach. Tutaj więcej info: <https://modrinth.com/plugin/teawaystones>

#### Receptura na waypoint

Potrzebne będą:
- 4x Obsidian
- 3x Redstone
- 1x Glowstone Dust
- 1x Compass

![waypoint](waystone_recipe.png)

#### Komendy

`/tw setname <name>` - ustawia nazwę dla waypointu. Komendę trzeba wykonać celując w dany waypoint.

### 🪑 GSit

Prosty, kosmetyczny plugin. Umożliwia siadanie, leżenie i inne akrobacje. Więcej info: <https://hangar.papermc.io/Gecolay/GSit>

#### Komendy

- `/sit` - siadanie
- `/crawl` - czołganie się
- `/lay` - leżenie
- `/bellyflop` - plaskacz na glebę
