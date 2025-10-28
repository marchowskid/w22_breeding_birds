README – Instrukcja obsługi plików GIS i map

-------------------------------------------------------------------------------------------------------
Struktura katalogów

fotopulapki_GIS – lokalizacje rozmieszczenia fotopułapek.

mapy – gotowe mapy i wizualizacje do raportów/opracowań.

miejsce_spalania_GIS – warstwa z lokalizacją miejsca przeznaczonego do spalania biomasy.

siedliska_GIS – warstwy przedstawiające podział siedlisk na wyspach.

stanowiska_ptakow_GIS – dane dotyczące ptaków (lokalizacje gniazd oraz obszary zajęte w siatce 100×100 m).

--------------------------------------------------------------------------------------------------------

Skróty gatunków i grup

CHADUB – sieweczka rzeczna (Charadrius dubius)

CHARHIA – sieweczka obrożna (Charadrius hiaticula)

KACZKI – gatunki z dwóch plemion:

Anatini – krzyżówka (Anas platyrhynchos), płaskonos (Spatula clypeata), krakwa (Mareca strepera), cyranka (Spatula querquedula)

Aythyini – głowienka (Aythya ferina), czernica (Aythya fuligula)

OHAR – ohar (Tadorna tadorna)

OHARY – lokalizacje gniazd w sztucznych skrzyniach lęgowych dla ohara

RYB_RZECZNA – rybitwa rzeczna (Sterna hirundo)

STEALB – rybitwa białoczelna (Sternula albifrons)

SZABLE_GNIAZDA – lokalizacje gniazd szablodzioba (Recurvirostra avosetta)

SZCZUDŁAK – lokalizacja gniazda szczudłaka (Himantopus himantopus)

TRITOT – krwawodziób (Tringa totanus)

VANVAN – czajka (Vanellus vanellus)

--------------------------------------------------------------------------------------------------------------

Dane w siatce 100×100 m

Warstwy siatkowe przedstawiają obszary zajęte przez populacje na wyspach.

Każdy kwadrat ma rozmiar 100 m × 100 m.

W tabeli atrybutów znajduje się kolumna size, która oznacza liczebność par lęgowych w danym kwadracie.

----------------------------------------------------------------------------------------------------------------

Instrukcja wizualizacji w QGIS

1. Otwórz QGIS i wczytaj odpowiednią warstwę siatkową (np. *.shp).

2. Kliknij prawym przyciskiem myszy na warstwie i wybierz Właściwości.

3. W zakładce Styl wybierz tryb wizualizacji Graduated (Skalowane).

4. Jako Kolumna wybierz size.

5. Wybierz schemat kolorystyczny (np. od jasnego do ciemnego koloru).

6. Ustaw liczbę klas (np. 3, 4 lub 5) – QGIS automatycznie podzieli wartości size na przedziały.

7. Zatwierdź – kwadraty siatki zostaną pokolorowane zgodnie z liczebnością par ptaków w danym obszarze.

-----------------------------------------------------------------------------------------------------------------

Słownik kategorii siedliskowych – wyspa W22

drzewa – pojedyncze drzewa rosnące na wyspie, grupy drzew i krzewów, niewielkie skupiska drzew i krzewów, ale bez zwartego charakteru zagajnika.

las – zwarty zagajnik wierzbowy (łęgowy typ sukcesyjny).

nasadzenia – krzewy wierzbowe posadzone sztucznie na wale wyspy, zgodnie z decyzją RDOŚ.

pustynia – obszar pozbawiony roślinności lub z roślinnością bardzo skąpą (nieliczne kępy traw, roślin zielnych).

roślinność – obszar z pokrywą mieszaną: roślinność wysoką (trzcina, drzewa, krzewy) oraz niską (trawy, turzyce, roślinność zielna). Kategoria obejmuje wszystkie typy: trzcina, trawy i las.

trawy – obszar z roślinnością niską: trawy, turzyce, roślinność zielna.

trzcina – obszar porośnięty zwartymi trzcinowiskami.

W22_woda – zbiornik wodny znajdujący się wewnątrz wyspy W22.

wal – wał wzniesiony wokół wyspy (nasyp brzegowy stabilizujący konstrukcję wyspy).




