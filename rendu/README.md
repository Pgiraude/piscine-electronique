Header1 J1
pin nom
1 D9 => PB1
2 D8 => PB0
3 D7 => PD7
4 D6 => PD6
5 D5 => PD5
6 D4 => PD4
7 D3 => PD3
8 D2 => PD2
9 GND
10 RST => reset/PC6
11 RXI => PD0
12 TXO => PD1

Header2 J2
1 RAW
2 GND
3 RST => reset/PC6
4 VCC
5 A3 => PC3
6 A2 => PC2
7 A1 => PC1
8 A0 => PC0
9 SCK => PB5
10 MISO => PB4
11 MOSI => PB3
12 D10 => PB2

Header3 J3
1 DTR
2 TXO => PD1
3 RXI => PD0
4 VCC
5 GND
6 GND

BOM
U1 – ATmega328P-AU (1×) – Microcontrôleur
C1, C2 (2×) – Condensateurs 12 pF (pour quartz)
C3, C4, C7 (3×) – Condensateurs 100 nF (découplage)
C6 (1×) – Condensateur 1 µF
D1 (1×) – LED Verte
D2 (1×) – LED Rouge
R1 (1×) – Résistance 330 Ω
R2 (1×) – Résistance (valeur non définie / ~)
R3 (1×) – Résistance 10 kΩ (pull-up reset)
SW1 (1×) – Bouton poussoir (reset)
Y1 (1×) – Quartz 16 MHz
J1, J2, J3 (3×) – Connecteurs (I/O + FTDI)

Éléments exclus du board :
GND1–GND8, VCC1–VCC4 (symboles d’alimentation)
