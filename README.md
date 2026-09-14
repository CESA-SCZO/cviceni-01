# Cvičení 1

**Klonování repozitáře:**
- Klávesa Windows + R -> cmd -> Enter
```
mkdir c:\SCZO_2026
cd C:\SCZO_2026
git clone https://cesta.ke.forked.git.repozitari
```

**Úkol 1:**
- Načtěte obraz initial_image.jpg do prostředí Python a zobrazte jej. 
- Všimněte si, z kolika matic je obraz složen a jaký má rozměr? Kolik bitů má obraz?

**Úkol 2:**
- Do jednoho okna (figure) zobrazte jednotlivé barevné složky obrazu zvlášť.
- Pro každou barevnou složku vytvořte histogram a zobrazte jej pod obraz daného kanálu
- Převeďte původní barevný obraz na šedotónový a zobrazte jej spolu s jeho histogramem.
- Zobrazte vedle sebe histogram zvektorizovaného barevného obrazu a histogram šedotónového obrazu. Pozorujte rozdíly a diskutujte. 

**Úkol 3:**
- Podkvantujte šedotónový obraz na 3 bity. 
- Podkvantujte barevný obraz tak aby celkem měl 3 bity. Jaký bude kvantizační krok? 
- Zobrazte v jednom okně původní šedotónový obraz a oba podkvantované obrazy spolu s jejich histogramy.

**Úkol 4:**
- Převeďte obraz initial_image.jpg do HSV prostoru, zobrazte jednotlivé složky a odpovídající histogramy. 
- V jaké aplikaci by bylo výhodné využít převod do HSV místo RGB?


**Závěr cvičení:**
```
git add .
git commit –m „message“
git push origin main
```