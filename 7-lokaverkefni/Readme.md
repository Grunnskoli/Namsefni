## Undirbúningur

Viðfangsefni lokaverkefnisins er frjálst en það þýðir ekki að það eigi að vera skipulagslaust og innihald eintómt bull (_dummy texti_). Við eigum að nota allt sem við höfum lært í vefhönnun sem að gagni getur komið í lokaverkefninu.

### Viðfangsefni

Lýsið í stuttu máli um hvað lokaverkefnið er í **Verkefni 7, README.md** skránni.

Hér er dæmi um umfjöllunarefni

> Lokaverkefnið er bloggsíða sem fjallar um Anime teiknimyndasögur. Á forsíðu eru greinar um myndasögurnar sem allir geta lesið. Það er hægt að skrá sig inn á spjallrás þar sem notendur geta spjallað saman um teiknimyndasögurnar. Ekki er hægt að komast á spjallrásina nema innskráðir notendur.

### Flæðirit

Búið til flæðirit sem lýsir skipulagi og virkni sem á að vera í vefnum. Flæðiritið getur verið í textasniði og skráð eins og hér er sýnt.

```
    index ('/') innihald kemur úr (?) gagnagrunni og / eða (?) API endpoint
    |
    |_ innskráning ('/login') - Firebase authentication
    |   |_ spjallrás ('/blog') lokuð með _session_
    |   |   |_ skrifað í fb gagnagrunn ('/write')
    |   |   |_ breyta grein í fb gagnagrunn ('/update')
    |   |   |_ eyða grein í fb gagnagrunn ('/delete')
    |   |   |_ útskráning (session log out)
    |   |_ innskráning mistókst ('/login_error')
    |
    |_ nýskráning ('/register')- Firebase authentication
        |_ spjallrás ('/blog') lokuð með _session_          
        |   |_ sama virkni og lýst er hér að ofan    
        |_ nýskráning mistókst ('/register_error')

```
(?) Ykkar tenging

### Niðurstaða 

Lýsið í stuttu máli hvað gekk vel að leysa og hvað vantar upp á að verkefnaáætlunin hafi staðist í **Verkefni 7, README.md**. 
