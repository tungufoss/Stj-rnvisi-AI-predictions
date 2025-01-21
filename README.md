# Spáum fyrir um framtíð gervigreindar

Þessi geymsla inniheldur glærur sem unnar eru í LaTeX með `hi-beamer` sniðmáti fyrir fyrirlestur Dr. Helgu Ingimundardóttur á viðburði Stjórnvísi um framtíð gervigreindar, haldinn þann 22. janúar 2025.

## Um viðburðinn

**Spáum fyrir um framtíð gervigreindar** er stutt innslag sérfræðinga þar sem vangaveltur um framtíð gervigreindar eru settar fram út frá ólíkum sjónarmiðum. Álitsgjafar munu spá fram í tímann um hvernig staða gervigreindar verður eftir 2 ár og svo aftur eftir 5 ár.

- **Dagsetning:** 22. janúar 2025  
- **Tími:** 09:00 - 10:00  
- **Staðsetning:** Teams  
- **Hlekkur á viðburð:** [Spáum fyrir um framtíð gervigreindar](https://www.stjornvisi.is/is/vidburdir/spaum-fyrir-um-framtid-gervigreindar)

### Álitsgjafar
- **Dr. Helga Ingimundardóttir** - Lektor í iðnaðarverkfræðideild, Háskóli Íslands
- **Tryggvi Thayer** - Aðjunkt í upplýsingatækni, nýsköpun og miðlun, Menntavísindasvið HÍ
- **Róbert Bjarnason** - Tæknistjóri, Citizens Foundation og Evoly
- **Hjálmar Gíslason** - Stofnandi og framkvæmdastjóri, GRID

**Fundarstjóri:** Gyða Björg Sigurðardóttir - sérfræðingur í gagnagreiningu hjá Orkunni og meðeigandi Ráður.

## Um glærurnar

Glærurnar fjalla um áhrif gervigreindar á fræðasamfélagið, siðferðilega notkun og sjálfbærni, auk spádóma um þróun á næstu árum.

### Innihald geymslu
- `slides.tex`: Aðalskjalið með efni glæranna.
- `myndir/`: Mappa með myndum fyrir glærur.
- `output/`: Úttaksskrár (PDF glærur).

## Uppsetning og notkun

Til að búa til PDF-skjal af glærunum þarftu eftirfarandi:
- LaTeX-útgáfu (t.d. TeX Live eða MiKTeX).
- `latexmk` til sjálfvirkrar byggingar.

### Keyrsla með `latexmk`:
```bash
latexmk -pdf slides.tex
```

PDF-skjal verður vistað undir skránni `slides.pdf`.

## Leyfi

Glærurnar eru gefnar út undir [MIT-leyfinu](LICENSE). Heimilt er að nota, breyta og deila efninu með tilvísun til höfundar.

## Hafðu samband

- **Dr. Helga Ingimundardóttir**  
- **Netfang:** [helgaingim@hi.is](mailto:helgaingim@hi.is)  
- **Deild:** Iðnaðarverkfræðideild Háskóla Íslands
