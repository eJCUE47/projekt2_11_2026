🌯 Comilla Kebab & Grill – LCD Advertising Display

Projekt elektronicznego wyświetlacza reklamowego dla Comilla Kebab & Grill w Ostrzeszowie, zrealizowany na platformie Arduino z wykorzystaniem wyświetlacza LCD 16x2 z interfejsem I2C.

Wyświetlacz automatycznie prezentuje nazwę lokalu oraz przewijane hasła reklamowe, zachęcające klientów do odwiedzenia restauracji.

📸 Opis projektu

Projekt wykorzystuje wyświetlacz LCD 16x2, na którym wyświetlane są dynamiczne komunikaty reklamowe. Teksty przesuwają się po ekranie, tworząc prostą animację.

Głównym celem projektu jest stworzenie niedrogiego, automatycznego wyświetlacza reklamowego, który może pracować bez przerwy po podłączeniu zasilania.

✨ Funkcje
Wyświetlanie nazwy lokalu: Comilla Kebab & Grill Ostrzeszów.
Automatyczne przewijanie tekstu w lewo i w prawo.
Animowane hasła reklamowe.
Regulowana prędkość przewijania napisów.
Automatyczne przełączanie komunikatów.
Podświetlenie wyświetlacza LCD.
Nie wymaga ręcznej obsługi po uruchomieniu.
🛠️ Wykorzystane komponenty
Komponent	Opis
Arduino	Mikrokontroler sterujący projektem
LCD 16x2 I2C	Wyświetlacz tekstowy
Przewody połączeniowe	Połączenie komponentów
Zasilanie	Zasilanie układu
💻 Wykorzystane technologie
Arduino C/C++
Biblioteka Adafruit_LiquidCrystal
Środowisko Arduino IDE
Tinkercad Circuits
🔌 Podłączenie

Wyświetlacz LCD I2C podłączamy do Arduino:

LCD I2C	Arduino UNO
GND	GND
VCC	5V
SDA	A4
SCL	A5
📟 Wyświetlane komunikaty

Projekt prezentuje między innymi następujące hasła reklamowe:

SOCZYSTY KEBAB
ZAPRASZAMY!
SWIEZE MIESO
WYJATKOWY SMAK
FRYTKI I SOSY
PYCHA!
GORACY KEBAB
COMILLA KEBAB
OSTRZESZOW
⚙️ Konfiguracja

Prędkość przewijania tekstu można zmienić za pomocą funkcji delay().

Przykład:

cpp
lcd_1.scrollDisplayLeft();
delay(100);


Przykładowe wartości:

250 – wolne przewijanie
150 – średnia prędkość
100 – szybkie przewijanie
70 – bardzo szybkie przewijanie
🚀 Uruchomienie projektu
Pobierz repozytorium na komputer.
Otwórz plik projektu w Arduino IDE.
Zainstaluj bibliotekę Adafruit_LiquidCrystal.
Podłącz wyświetlacz LCD I2C do Arduino UNO.
Wgraj program na płytkę Arduino.
Podłącz zasilanie i obserwuj działanie wyświetlacza.

Projekt można również przetestować w środowisku Tinkercad Circuits bez konieczności posiadania fizycznych komponentów.

🎯 Cel projektu

Celem projektu jest połączenie podstaw elektroniki, programowania Arduino oraz praktycznego zastosowania technologii w reklamie lokalnego biznesu.

Projekt pokazuje, jak za pomocą prostego mikrokontrolera i wyświetlacza LCD można stworzyć automatyczny system prezentowania komunikatów reklamowych.

Made with ❤️ using Arduino

🌯 Comilla Kebab & Grill – Ostrzeszów
