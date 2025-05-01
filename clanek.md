# Summary of AlphaFold2 IDRs article

**Zvolený článek:** [Systematic identification of conditionally folded intrinsically disordered regions by AlphaFold2](https://www.pnas.org/doi/epub/10.1073/pnas.2304302120)

## Úvod a motivace:
- AlphaFold2 (AF2) výborně predikuje struktury proteinů, ale více než 60 % lidských proteinů obsahuje intrinsicky nestrukturované oblasti (IDRs).
- IDRs se běžně nevyskytují ve stabilních strukturách, ale některé z nich se strukturně zformují až po vazbě na jiný molekulární partner – tzv. podmíněné skládání (conditional folding).
- Cílem studie je prozkoumat, zda a jak AF2 tyto oblasti rozpozná.

## Hlavní zjištění:
- Překvapivě, AF2 predikuje s vysokou důvěrou strukturu až u 15 % lidských IDRs, i když ve většině trénovacích dat tyto oblasti chyběly.
- Tyto predikované struktury často odpovídají „poskládaným" stavům, které IDRs zaujímají při vazbě nebo po modifikaci (např. fosforylaci).
- Přesnost klasifikace podmíněně poskládaných IDRs pomocí skóre důvěry (pLDDT) je až 88 % při 10 % falešně pozitivních případech.
- IDRs s vysokým pLDDT skóre jsou 5× častěji spojeny s nemocemi než běžné IDRs.

## Dílčí analýzy a výsledky:
### IDRs s vysokým pLDDT:
- Mají vyšší evoluční konzervaci.
- Jsou častěji tvořeny alfa-helixy než oblasti s nízkým skóre.
- Mají odlišné složení aminokyselin – více nabité a hydrofobní zbytky.

### NMR analýzy ukazují, že predikované struktury AF2:
- neodpovídají flexibilitě nestrukturovaných IDRs.
- často připomínají stavy vázané na partnery, nikoli samotné IDRs v roztoku.

### Ve srovnání napříč organismy:
- V bakteriích a archeích je až 80 % IDRs pravděpodobně schopných podmíněného skládání.
- V eukaryotech je tento podíl nižší (<20 %) – většina IDRs funguje bez skládání.

## Význam pro výzkum nemocí:
- Mutace v IDRs s vysokým pLDDT skóre jsou výrazně častěji patogenní.
- AF2 predikce mohou pomoci odhalit funkčně významné mutace v těchto oblastech.
- Případová studie ukazuje, že i bez experimentální struktury lze díky AF2 pochopit mechanismus vzniku onemocnění způsobeného mutací v IDR.

## Shrnutí a výhled:
- AlphaFold2 dokáže identifikovat IDRs, které se skládají jen za určitých podmínek.
- Tato schopnost může výrazně rozšířit porozumění funkci IDRs a jejich roli v chorobách.
- Přesto je třeba si uvědomit, že AF2 nepostihuje dynamiku těchto oblastí a poskytuje jen jednu statickou konformaci.
- Autoři navrhují kombinovat AF2 s dalšími metodami (např. NMR), aby bylo možné plně pochopit funkci IDRs.