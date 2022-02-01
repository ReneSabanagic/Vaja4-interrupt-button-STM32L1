# Vaja4-interrupt-button-STM32L1

V Pinout % Configuraton pogledu glede na vašo razvojno ploščico ugotovite, ali lahko uporabite modro tipko za digitalni vhod kot interrupt (GPIO_EXT…). Če da, kateri pin je to? PA0_____ Če ni, uporabite drugi ustrezni pin /___, ki ga boste prožili s pomočjo Pull-UP vezja.

Zapišite naslov izhodnih pinov za zeleno in modro LED: PC9, PC8_

Koliko znaša (v mili sekundah) zapisana zakasnitev, ki jo proizvede zanka for? 10000.

V to zanko dodajte ukaz za zakasnitev z funkcijo Delay iz knjižnice HAL, in sicer pol sekunde: HAL_Delay(500);

Opazujte delovanje (utripanje modre LED). Kaj se zgodi, ko pritisnemo na modro tipko na STM32L1?

Ali pritisk na modro tipko vpliva na utripanje modre LED in zakaj? __ne

Komentar:
Projekt žal ne deluje kakor bi moral.
