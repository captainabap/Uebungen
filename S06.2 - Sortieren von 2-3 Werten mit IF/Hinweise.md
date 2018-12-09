# Zur Vorgehensweise zum Sortieren mit drei Werten:
Es gibt mindestens zwei Möglichkeiten, die drei Werte zu sortieren:
1.	Alle möglichen Kombinationen der IN-Parameter in einer großen IF/ELSE/ELSE…END-Abfrage abfragen und die Werte in dem jeweiligen Zweig entsprechend zurückgeben. 
2.	Anlegen einer Funktion zum Sortieren von zwei Werten. Diese Funktion kann dann verwendet werden, um die Werte paarweise zu sortieren: 1&2, 1&3, 3&3 
Vielleicht finden Sie aber auch noch eine weitere Möglichkeit zur Lösung des Problems.

#Syntax der IF-Verzweigung:
´´´SQL
IF <Bedingung_1> THEN <Block_1>
[ELSEIF <Bedingung_2> THEN <Block_2>]
...
[ELSE <Block_N>]
END IF;
´´´
