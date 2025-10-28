README – User Guide for GIS Files and Maps
Directory Structure

----------------------------------------------------------------------------------------------------------

fotopulapki_GIS – locations of camera traps.

mapy – ready-to-use maps and visualizations for reports or studies.

miejsce_spalania_GIS – layer showing the location designated for biomass burning.

siedliska_GIS – layers representing habitat division on the islands.

stanowiska_ptakow_GIS – bird-related data (nest locations and occupied grid areas, 100×100 m).

------------------------------------------------------------------------------------------------------------

Species and Group Abbreviations

CHADUB – Little Ringed Plover (Charadrius dubius)
CHARHIA – Ringed Plover (Charadrius hiaticula)

KACZKI – ducks (two tribes):

Anatini: Mallard (Anas platyrhynchos), Northern Shoveler (Spatula clypeata), Gadwall (Mareca strepera), Garganey (Spatula querquedula)

Aythyini: Common Pochard (Aythya ferina), Tufted Duck (Aythya fuligula)

OHAR – Common Shelduck (Tadorna tadorna)
OHARY – nest locations in artificial nest boxes for the Common Shelduck

RYB_RZECZNA – Common Tern (Sterna hirundo)
STEALB – Little Tern (Sternula albifrons)

SZABLE_GNIAZDA – nest locations of the Pied Avocet (Recurvirostra avosetta)
SZCZUDŁAK – nest location of the Black-winged Stilt (Himantopus himantopus)

TRITOT – Common Redshank (Tringa totanus)
VANVAN – Northern Lapwing (Vanellus vanellus)

----------------------------------------------------------------------------------------------------------------

100×100 m Grid Data

The grid layers represent areas occupied by bird populations on the islands.
Each grid cell has a size of 100 m × 100 m.
The attribute table includes the column size, which indicates the number of breeding pairs within each grid cell.

-----------------------------------------------------------------------------------------------------------------

Visualization Instructions in QGIS

Open QGIS and load the appropriate grid layer (e.g., .shp).

Right-click the layer and select Properties.

In the Symbology tab, choose Graduated style.

Set Column to size.

Choose a color scheme (e.g., from light to dark shades).

Set the number of classes (e.g., 3, 4, or 5) – QGIS will automatically divide size values into intervals.

Confirm – grid squares will be colored according to the number of breeding pairs in each area.

-----------------------------------------------------------------------------------------------------------------


Habitat Category Glossary – Island W22

drzewa (trees) – individual trees growing on the island, groups of trees and shrubs, or small clusters without a compact woodland structure.

las (forest) – dense willow thicket (riparian-type successional stand).

nasadzenia (plantings) – willow shrubs planted artificially along the island’s embankment according to the Regional Directorate for Environmental Protection (RDOŚ) decision.

pustynia (bare ground) – area without vegetation or with very sparse vegetation (scattered grass or herb patches).

roślinność (mixed vegetation) – area with a mixture of tall vegetation (reeds, trees, shrubs) and low vegetation (grasses, sedges, herbs). This category includes all vegetation types: reed, grass, and forest.

trawy (grasses) – area covered with low vegetation such as grasses, sedges, and herbs.

trzcina (reed) – area covered with dense reedbeds.

W22_woda (water) – waterbody located inside island W22.

wal (embankment) – artificial embankment surrounding the island (shoreline structure stabilizing the island).

