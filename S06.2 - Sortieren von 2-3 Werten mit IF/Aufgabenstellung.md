# Für Eisteiger
Legen eine Funktion an, die zwei ganzzahlige Parameter mit IF –Verzweigungen in aufsteigender Reihenfolge sortiert: UDF_SORT( 4,3) ergibt (3,4).
Zur Lösung können Sie dieses Grundgerüst einer Funktion nutzen:

'''SQL
CREATE FUNCTION udf_sort_2(iv_wert1 INT,
                           iv_wert2 INT)
RETURNS rv_klein  INT,
        rv_gross  INT
AS BEGIN

   <Hier bitte den eigenen Code einfügen>

END;
'''

# Für Profis
Sortieren Sie drei Werte in aufsteigender Reihenfolge.
CREATE FUNCTION udf_sort_3(iv_wert1 INT,
                           iv_wert2 INT,
                           iv_wert3 INT )
RETURNS rv_klein  INT,
        rv_mittel INT,
        rv_gross  INT
AS BEGIN

   <Hier bitte den eigenen Code einfügen>

END;
