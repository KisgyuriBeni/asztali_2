Megvalósítittuk a MainFrame osztályban az ablakot;
A student array-ben tárolódnak a felvett tanulók nevei;
MEgszámoljuk a tanulókat és kiválasztunk 4-et;
Felvettük 2 gombot és egy panel-t;

Meghívtuk a BorderLayout-ot a java.awt.BorderLayout csomagból, mivel a vsc nem tudja magától beimportálni!!!
Ennek funciója az, hogy NORTH, CENTER, SOUTH-al tudjuk pozicíonálni a frame-en az elemeinket;

Az initFrame-ben inicializáljuk az elemeket és meghívjuk a MainFrame metódusban amit futtatunk majd az APP.java-ban;
Egy Jcheckbox elemet felveszünk és átadjuk neki a MAX_STUDENT Állandót;
Egy for ciklussal beolvassuk a studentArray[i] i-edik elemét átadjuk neki;
Így megjelennek a checkboxok mellett a nevek, akik a tömbben szerepelnek;
