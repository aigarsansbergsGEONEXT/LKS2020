# LKS2020 — programmas lejupielādes un atjauninājumu manifests

Šis repozitorijs satur SIA GeoNEXT programmas „LKS92 → LKS2020 pārrēķins” publicējamos failus.
Avots: `Downloads\0izdruka\LKS2020\programmdownload\` (pildīts no `LKS2020\publicet\<versija>\`).

    laidiens.json                    parakstīts manifests (versija, datums, failu URL un SHA-256, Ed25519 paraksts)
    lejupielade/LKS2020_<ver>.zip    lejupielādes pakotne lapas pogai: abi .exe + LASI_MANI.md + Latvia2020.TM.xml
    lejupielade/LKS2020_parrekins.exe, LKS2020_cmd.exe   atsevišķie .exe atjauninātājam
    lejupielade/Latvia2020.TM.xml    AutoCAD Map 3D / Civil 3D koordinātu sistēmas definīcija

Programma lasa `https://www.lks2020.lv/laidiens.json` un failus no `https://www.lks2020.lv/lejupielade/`,
tāpēc šī repozitorija saturs serverī jānonāk lapas saknē blakus `index.html` (vai manifestā jāmaina URL).
Nosaukumus nemainīt: .exe nosaukumus lasa atjauninātājs pēc manifesta.
