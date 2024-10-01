# Problemstellung

## Modul 1
Ich habe das Projekt jetzt analysiert und erkläre es jetzt kurz. Im Projekt von Modul 1 
gibt es 7 Klassen und eine Klasse vom Typ Enum. Die Klasse Medium ist dabei die 
wichtigste, denn die Klassen Cartridge, Buch und VHS erben von Medium.

## Modul 2
Es werden die zentralen Konzepte vorgstellt:
- Vererbung
- Subtyping
- Ersetzbarkeit
- Polymorophe Variablen

Das Dome Beispiel speichert Details zu CDs und DVDs und es erlaubt später
nach Infos zu suchen oder Listen auszugeben.

Das Dome Beispiel wird dann erklärt, es hat eine Datenbanklasse mit zwei ArrayLists. Eine
ArrayList vom Typ DVD und eine vom Typ CD.

Danach wird der Quellcode gezeigt und erkärt. Kritik am Beispiel ist, dass Code Duplizierung auftritt.
Deshalb kommt die Vererbung zum Einsatz, um die Duplizierung zu reduzieren. Man muss also eine Superklasse ertsellen
und die gemeinsamen Attribute definieren. Die Subklassen erben danach die Attribute der Superklasse.

Danach kommt das Subtyping.
Zuerst hatten wir:
public void erfasseCD (CD dieCD)
public void erfasseDVD(DVD dieDVD)

Jetzt haben wir:
public void erfasseMedium (Medium das Medium)
Danach wird die Hirachie von Subtyping erklärt.

Ersetzbarkeit: Objekte von Subklassen können verwendet werden, wo Objekte eines
Supertyps erwartet werden.

Objektvariablen in Java sind polymorph. Sie können Objekte vom deklarierten Typs halten.

deklarierter Typ einer Variable ist ihr statischer Typ.
Typ eines Objekts ist sein dynamischer Typ.

Methoden können in einer Subklasse überschrieben werden.

Durch Zugriff protected wird die engere Vererbungsbeziehung unterstützt.say


Im dritten Video geht es um Vererbung, Überschreiben, Ersetzbarkeit und dynaimscher Bindung.
Dort habe ich fast alles verstanden, da wir eigentlich alles schon im Unterricht durchgemacht haben.