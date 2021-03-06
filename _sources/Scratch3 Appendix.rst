Shtesë
==========

.. include:: blocks.txt

.. include:: icons.txt

.. infonote::

  |intro11s|

Funksionet bllok
--------------------

Në Scratch, forma e një blloku siguron që, kur blloqet janë të lidhura, ato mund të formojnë vetëm shkrime, të cilat janë sintetike të sakta. Ka blloqe të pavarura dhe blloqe funksionimi. Blloqet e pavarura (blloqet e kapelave, blloqet e pirgut, blloqet C dhe blloqet e kapakëve) korrespondojnë me komandat gjuhësore. Blloqet e funksioneve (reporterët dhe blloqet logjike) ruajnë vlerat e blloqeve të pavarura. Në mësimin 3, ne folëm për llojet e ndryshme të blloqeve, dhe tani do të prezantojmë funksionet e grupeve kryesore të bllokut dhe disa prej grupeve të vendosura në pjesën Zgjatjet.

Blloqet e lëvizjes
~~~~~~~~~~~~~~~~~~~~

.. sidebar:: |motion_blocks| Lëvizja
    
   |fig11_1|
 
.. |fig11_1| image:: ../_images/11/fig11_1.png
    
   
Komandat e caktuara në këto blloqe mund të ekzekutohen vetëm nga sprites. Faza është pa lëvizje, për këtë arsye nuk mund të ekzekutojë komanda lëvizjeje. Ekzistojnë 18 blloqe në grupin *Motion*, një më shumë sesa në versionin Scratch 2.0. Blloku |glide_to| u shtua.

Për t'i bërë ato më të lehtë në përdorim, blloqet që kryejnë funksione të ngjashme qëndrojnë pranë dhe formojnë nëngrupe. Funksionet e nëngrupeve janë këto:

1. lëvija e sprite në një vijë të drejtë ose në një rreth,

2. lëvija e sprite në një pozicion të specifikuar,

3. derjtimi i sprite drejt diçkaje,

4. zhvendosja e sprite duke ndryshuar koordinatat e saj,

5. mbajtja e sprite brenda kufijve të fazës,

6. vendosjen e stilit të rrotullimit të sprites,

7. ruajtja e koordinatave aktuale të sprite.

Blloqet që i përkasin gjashtë grupeve të para janë blloqe rafte, ndërsa grupi i shtatë përfaqëson reporterët, funksioni i të cilëve është ruajtja e të dhënave. Ata nuk mund të qëndrojnë më vete; ato futen në fushat hyrëse të blloqeve të tjera, duke specifikuar kështu veprimet e tyre.

Blloqet nga grupi i parë kryejnë lëvizje, lëvizje relative në lidhje me pozicionin dhe drejtimin aktual. Për dallim prej këtyre blloqeve, ato nga grupi i dytë e zhvendosin rrjedhën në një pikë të caktuar në skenë, pavarësisht nga pozicioni i saj aktual. Ky lloj lëvizjeje quhet lëvizje absolute.

Disa lloje të të dhënave mund të futen në fushat hyrëse të blloqeve të lëvizjes: vlerat e koordinatave të destinacionit, këndi i rrotullimit, numri i hapave ose kohëzgjatja e lëvizjes. Një hap i përgjigjet një pixel. Koha shprehet në sekonda, dhe këndet në shkallë.

Në disa prej blloqeve, destinacioni zgjidhet nga lista rënëse e bllokut. Ky mund të jetë treguesi i miut, disa sprite të tjera që marrin pjesë në projekt, si dhe një pikë, koordinatat e së cilës gjenerohen në mënyrë të rastësishme.

Blloku |rotation_style| ka tre opsione të stilit të rrotullimit: *të gjithë rreth*, *majtas-djathtas* dhe *nuk rrotullohen*. Opsioni i parë do të thotë që sprite mund të përballet me cilindo nga 360 gradë. *Majtas-djathtas* do të thotë që sprite mund të përballet vetëm majtas ose djathtas, dhe çdo drejtim tjetër është i paaftë. Mundësia e fundit do të thotë që sprite gjithmonë përballet drejt.

Blloqet nga grupi *Motion* janë shtjelluar në mësimin 2 të këtij praktiku.

.....

Blloqet Looks
~~~~~~~~~~~~~~~

.. sidebar:: |looks_blocks| Looks
    
   |fig11_2|
 
.. |fig11_2| image:: ../_images/11/fig11_2.png

Blloqet nga ky grup kontrollojnë shfaqjen e sprites. Shtatë nga 21 blloqe nga ky grup kontrollojnë shfaqjen e skenës.
Njëzet blloqe janë të dukshme kur sprite është në fokus dhe tre nëngrupe blloku kur faza është në fokus. Blloku |Switch_backdrop_wait|, i cili mundëson që sfondi të ndryshojë dhe të presë derisa të ndodhë kjo mund të shihet vetëm kur faza është aktive (nuk është e dukshme kur sprite është në fokus). Blloqet e mbetura që mund të ngjiten në skenë gjithashtu mund të shihen në këtë rast. Funksionet e nëngrupeve janë si më poshtë:

1. shfaqja e asaj që po thotë të folurit e të menduarit,

2. ndryshimi i kostumit të sprite dhe sfondi i skenës,

3. ndryshimi i madhësisë së sprite,

4. duke punuar me efekte grafike që mund t'i bashkëngjiten sprites dhe skenës,

5. duke treguar ose fshehur sprite,

6. vendosja e sprite në shtresën e specifikuar të figurës,

7. reporterët që tregojnë kostumin aktual dhe madhësinë e sprite, si dhe sfondin aktual të skenës.

Efektet grafike, të cilat mund të shtohen në sprite, janë:

.. hlist::
    :columns: 1

    * color - ndryshon ngjyrën e sprite,
    * fisheye - jep përshtypjen e një sprite që shihet përmes një lente me kënd të gjerë,
    * whirl - kthesë rrëshqitje rreth pikës së saj qendrore,
    * pixelate - pikselon sprite,
    * mozaic - krijon imazhe të shumëfishta më të vogla të sprite,
    * brightness - ndryshon shkëlqimin e sprite, dhe
    * ghost - ndryshon transparencën e sprite.


Ndryshimi i ngjyrës, për shembull, mund të japë iluzionin se sprite po shpreh emocione ose ndezje, mund të duket sikur u shfaq një gjë krejtësisht e re. Nëse përdorni ndryshimin e ngjyrave me komandën ``stamp``, mund të bëni modele tërheqëse, për shembull, ylber.

Duke përdorur efektin fisheye, ju mund të jepni një iluzion që sprite po lëviz drejt ose larg nga ekrani, duke u bërë më i trashë dhe të ngjashme. Mund të përdoret si një tranzicion midis kostumeve.

Efekti i vorbullës mund të simbolizojë udhëtimin në kohë, teleportation, vertigo, vjellje.

Efekti i pixelation bën që sprites të duken si ato në versionet e para të lojërave kompjuterike, kur monitorët kishin rezolucion të ulët; ai gjithashtu mund të përdoret për të censuruar ose bllokuar spërkatjen në skenë.

Efekti mozaik përdoret për shumëzimin e sprites pa klonim.

Duke ndryshuar shkëlqimin e sprite, ajo mund të japë përshtypjen e ndezjes, ose mund të bëhet më e errët, dhe efekti fantazmë mund ta bëjë sprite të padukshëm për përdoruesin, por spritat e tjerë ende mund ta zbulojnë atë në skenë.

Blloqet |goto_layer| dhe |go_layers| janë të ndryshme nga blloqet që kryenin funksione të ngjashme në versionin e mëparshëm të Scratch.

Kur faza është në fokus, mund të shihni 8 blloqe të ndara në 3 nëngrupe: për ndryshimin e sfondit, për vendosjen e efekteve grafike për sfondin dhe raportuesin që tregon sfondin aktual. Sfondi ``Emri i sfondit``, i cili ekzistonte në versionin Scratch 2.0, nuk është përfshirë në versionin e ri.

Blloqet nga grupi *Show* janë shtjelluar në mësimin 3 të këtij kursi.

.....

Blloqet Sound
~~~~~~~~~~~~~~~

.. sidebar:: |sound_blocks| Sound 
    
   |fig11_3|
 
.. |fig11_3| image:: ../_images/11/fig11_3.png

Dy projekte tingujsh mund të përdoren në projekte: tinguj dhe shënime. Blloqet nga ky grup mund të përdoren për të punuar me tinguj, dhe blloqet nga shtesa *Music* për të punuar me shënime. Tinguj janë të arritshëm vetëm duke importuar, regjistruar ose nga një bibliotekë e integruar e tingujve. Ata janë luajtur duke përdorur blloqet e tingullit, të cilat kontrollojnë vëllimin, tempo dhe më shumë. Grupi i blloqeve *Sound* është modifikuar në mënyrë të konsiderueshme, në krahasim me mënyrën se si është organizuar në versionin Scratch 2.0. Disa nga blloqet e këtij grupi u zhvendosën në shtesën *Music*. Grupi *Sound* ka 9 blloqe, të cilat ndahen në 3 nëngrupe. Ato mund të aplikohen për të dy sprites dhe sfondin.

Funksionet e nëngrupeve janë këto:

1. fillimi, ndalimi dhe interpretimi i tingujve,

2. aplikimi i efekteve të tingullit,

3. kontrollin e vëllimit.

**Fillimi, Ndërprerja dhe Dëgjimi i Tingujve**

Blloku |play_until| luan një tingull specifik, duke ndalur skenarin deri sa të mbarojë. Për dallim nga ky bllok, blloku |start_sound| interpreton një tingull pa e ndalur skenarin. Kjo është arsyeja pse blloku ``start sound`` zakonisht përdoret për të shpallur një veprim, për të informuar një sprint se është arritur një qëllim, ose të nxjerrë në pah ngjarje të caktuara.

Nga ana tjetër, blloqet ``play up`` zakonisht përdoren për të luajtur "muzikë në sfond". Ky bllok vendoset në bllokun ``forever`` dhe muzika e duhur luhet gjatë gjithë ekzekutimit të programit. Mund të përdoret gjithashtu për ndaljen e ekzekutimit të skenarit në vend të bllokut të kontrollit ``wait``.

Blloku ``stop sounds`` do të ndalojë të gjithë tingujt që janë duke u luajtur aktualisht - të të gjitha sprites dhe skenës. Për shembull, nëse projekti ofron mundësinë e muzikës, ky bllok përdoret për të fikur muzikën. Shtë gjithashtu e zakonshme që të gjithë tingujt të ndalen përpara se projekti të kalojë në skenën tjetër, dhe të ngjashme.

**Aplikimi i efekteve të tingullit**

Blloqet që vendosin dhe ndryshojnë efektet e zërit u prezantuan në Scratch 3.0. Edhe pse redaktori i ri i tingullit siguron më shumë efekte tingujsh (shihni më poshtë në seksionin e redaktorit të tingullit), blloqet mbështesin vetëm dy: vendosjen dhe ndryshimin e katranit, dhe zhvendosjen e zërit në të majtë ose të djathtë.

**Kontrolli i vëllimit**

Këto blloqe ndikojnë vetëm në degëzimin (ose sfondin) të cilit i janë caktuar. Për shembull, duke klikuar në sprite mund të kthehet vëllimi nëse sprite po bëhet më i vogël, duke u shfaqur kështu sikur Sprite po largohet nga përdoruesi. Gjithashtu, nëse përdoren blloqe nga shtesa *Music*, disa pjesë të përbërjes mund të dëgjohen më të zëshme dhe të tjera më të qeta.

Tetë nga këto blloqe janë blloqe rafte, dhe një është një reportazh, i cili ruan informacionin mbi vëllimin e tingullit.

.....

Blloqet Event
~~~~~~~~~~~~~

.. sidebar:: |events_blocks| Events
    
   |fig11_4|
 
.. |fig11_4| image:: ../_images/11/fig11_4.png

Blloqet në këtë grup përdoren për të shkaktuar drejtimin e skenarit dhe dërgimin dhe pranimin e mesazheve. Në këtë grup ka 9 blloqe dhe ato ndahen në 3 nëngrupe. Meqenëse në këtë version të Scratch, sensacioni i videos është zhvendosur në pjesën e shtesave, është hequr nga menyja drop-down e bllokut |when_greater|.

Funksionet e nëngrupeve janë këto:

1. skriptet nxitëse me një aktivitet specifik të kryer nga përdoruesi,

2. Shkrimet e nxitjes kur një ekzekutim i veçantë ishte përmbushur gjatë ekzekutimit të projektit,

3. duke mundësuar transmetimin dhe pranimin e mesazheve.

**Ndjekja e shkrimeve me aktivitete të kryera nga përdoruesi**

Përdoruesi mund të fillojë ekzekutimin e projektit duke klikuar butonin |g_flag|, një nga sprites që merr pjesë në projekt, në sfond ose duke shtypur një nga tastet e tastierës. Projekti zakonisht nxitet kur klikohet flamuri i gjelbër, kjo është kur të gjitha skriptet, të cilat fillojnë me këtë bllok, do të aktivizohen. Këto janë skriptet që kryejnë inicializime të ndryshme, dhe pastaj ia dorëzojnë menaxhimin shkrimeve të tjera. Për shembull, ata fshijnë të gjithë elementët e listës, rivendosin variablat, vendosin skena duke treguar ose fshehur sprites dhe duke ndryshuar kostumet e tyre, fshijnë çdo gjë të tërhequr në skenë, fillojnë muzikën në sfond, etj. Ndërsa është plotësisht e mundur të krijoni projekte pa përdorur këtë bllok, nuk rekomandohet. E vetmja mënyrë se si mund të fillohet një projekt pa përdorur këtë bllok do të ishte aktivizimi i skripteteve që fillojnë me ndonjë bllok tjetër nga kjo nëngrup. Në këtë rast, projekti do të zgjaste vetëm derisa të përfundonin skriptet që varen nga skriptet fillestare.

Shënim. Blloku |clicked_stage| është e dukshme vetëm kur faza është në fokus.

**Shkrimet e shkëputjes kur u plotësua një kusht specifik gjatë ekzekutimit të projektit**

Disa nga ngjarjet që mund të shkaktojnë mbarimin e skripteteve duke filluar me një nga blloqet nga ky grup janë ndryshimi i sfondit, skadimi i një periudhe specifike kohore ose rritja e vëllimit përtej një niveli të caktuar.

**Transmetimi dhe pranimi i mesazheve**

Transmetimi i mesazheve është mekanizmi kryesor për koordinimin e sjelljes së sprites që marrin pjesë në një projekt, dhe mund të përdoret gjithashtu për realizimin e procedurave. Transmetimi përdoret për të thirrur skriptet që duhet të aktivizohen kur plotësohen kushte të caktuara. Skriptet që fillojnë me bllokun |when_receive| do të thirret pasi të jetë transmetuar mesazhi i specifikuar. Nëse transmetohet i njëjti mesazh ndërsa skenari është akoma duke ekzekutuar, ekzekutimi aktual do të ndalet, dhe skenari do të fillojë të ekzekutohet përsëri nga fillimi. Prandaj, nëse vendosim bllokun, i cili transmeton mesazhin të cilit po i përgjigjet skenari, në skenarin që fillon me bllokun ``when receive``, kemi një situatë kur skenari po thërret vetë. Kjo quhet **rekursion**, dhe mund të përdoret për krijimin e fraktaleve, sythe përgjithmonë dhe të ngjashme.

.....

Blloqet Control
~~~~~~~~~~~~~~~~

.. sidebar:: |control_blocks| Control
    
   |fig11_5|
 
.. |fig11_5| image:: ../_images/11/fig11_5.png

Blloqet nga ky grup kontrollojnë ekzekutimin e shkrimeve. Ato mundësojnë degëzim, përsëritje dhe punë me klone sprite, dhe ato mund të ndalojnë mbarimin e shkrimeve. Gjithsej janë 11 blloqe, një është një bllok (kapelë) fillestar, dy janë blloqe kapele, tre janë blloqe rafte, pesë janë blloqe C, dhe ``if else then`` është një bllok në formë E. Ata janë të ndarë në pesë nëngrupe, funksionet e të cilave janë këto:

1. bllok për pritje (duke ndalur skenarin),

2. blloqe përsëritje,

3. blloqe me degë,

4. bllok për përsëritjet e kushtëzuara,

5. bllok për ndalimin e skenarit,

6. blloqe që përdoren për të punuar me klone.

Funksionet e këtyre blloqeve janë shtjelluar në mësimet 5, 6 dhe 7 të këtij praktiku.

**Puna me klone**

Klonimi është një veçori që lejon që sprite të krijojë një kopje të vetvetes ndërsa projekti po funksionon. Çdo klon (kopje) ka të njëjtat kostume, tinguj dhe shkrime si origjinali, por është ndryshe i pavarur. Klonimi është vulosje me forma të ndryshme sepse klonet janë sprites individuale që mund të drejtojnë skriptet dhe të sillen sipas atyre shkrimeve. Ato janë gjithashtu të ndryshme nga spritet e krijuara me opsionin e dublikimit sepse kopjimet e zakonshme janë të përhershme dhe paraqiten në listën sprite, ndërsa klonet jo, dhe ato zhduken kur projekti ka mbaruar.

Klonimi përdoret sa herë që një projekt ka sprites të ngjashëm që bëjnë gjëra të ngjashme. Meqenëse klonet janë bërë nga projekti, dhe jo nga përdoruesi, klonimi çliron përdoruesin të bëjë të njëjtat ndryshime në secilën nga shumë sprites. Për shembull, klonimi mund të përdoret për krijimin e spritave të shumëfishtë të mikut dhe armikut në lojëra, si dhe për efekte speciale si fishekzjarre dhe borë.

Klonët zakonisht kryejnë një veprim kur krijohen. Blloku |when_clone| shkakton skenarin, i cili fillon të ekzekutohet kur krijohet një klon. Skriptet e shumta që fillojnë me këtë bllok mund të shtohen në të njëjtën sprite, dhe të gjitha ato do të funksionojnë njëkohësisht kur të krijohet një klon. Skenari vetë mund të jetë duke u ekzekutuar në klone të shumta njëkohësisht. Disa nga veprimet që ky bllok mund të kryejë përfshijnë vendosjen e klonit në një pozicion të rastësishëm, lëvizjen e klonit derisa të përplaset me një tjetër sprit.

.....

Blloqet e ndjeshmërisë
~~~~~~~~~~~~~~~~~~~~~~~~~

.. sidebar:: |sensing_blocks| Sensing
    
   |fig11_6|
 
.. |fig11_6| image:: ../_images/11/fig11_6.png

Ky grup është i përbërë nga blloqe që lejojnë projektin të pranojë të dhëna nga pajisje të ndryshme, ashtu si mënyra se shqisat njerëzore mbledhin informacione nga mjedisi i tyre.
Ekzistojnë 18 blloqe në grupin *Sensing*. Tre blloqe, të cilat ishin në versionin Scratch 2.0 dhe që i referoheshin lëvizjes së redaktimit dhe monitorimit të videos të regjistruar nga një video, nuk janë më të përfshira, por blloku |set_drag| u shtua. Ky bllok rregullon nëse një sprite me ekran të plotë mund të tërhiqet ose jo, i cili ishte rregulluar më parë në informacionin e sprite. Blloqet në lidhje me zbulimin e videos janë zhvendosur në shtrirjen përkatëse.

Këto blloqe ndahen në 6 nëngrupe me këto funksione:

1. ruajtja e informacionit për distancën e spritit në lidhje me treguesin e miut ose objektet e tjera,

2. vendosjen e të dhënave hyrëse nga tastiera,

3. ruajtja e informacionit për operacionet aktuale të treguesit të miut dhe tastierës,

4. ruajtja e vlerës aktuale të zhurmës së tingullit,

5. duke punuar me një kohëmatës,

6. ruajtja e parametrave të sprites dhe skenës,

7. ruajtja e informacionit për kohën e tanishme dhe përdoruesin.

Vetëm tre blloqe nga ky grup mund të qëndrojnë më vete, pjesa tjetër janë blloqe funksioni. Prandaj, blloqet nga grupi i parë futen në blloqe kontrolli, të cilat duhet të mundësojnë kryerjen e aktiviteteve të ndryshme në varësi të pozitës së sprite. Blloqet e grupit të dytë korrespondojnë me informacionin që një person mbledh me sensin e prekjes, dhe grupi i tretë i përgjigjet informacionit që mblidhet nga sensi i të dëgjuarit. Koha mund të përdoret për të kufizuar kohën e lojës ose kohën që duhet për të përfunduar një detyrë provë. Blloku që ruan parametrat e sprites dhe skena mund të sigurojë shumë të dhëna për të gjitha objektet, të cilët marrin pjesë në projekt. Informacioni që një person do të mbledhë përmes sensit të shikimit, dhe një kompjuter me një kamerë video, mund të përdoret nëse shtesa *Ndjesia Video* i shtohet projektit.

Ne kemi shtjelluar funksionet e shumicës së blloqeve në këtë grup përmes shembujve në mësimet e mëparshme. Këtu do të përmendim vetëm funksionet e blloqeve logjikë dhe reporterëve të kohës aktuale.

**Blloqe logjike**

Ka 5 blloqe logjike në këtë grup. Secila prej këtyre blloqeve mund të kthejë vetëm një nga dy vlera: e vërtetë ose e rremë, në varësi të faktit nëse kushti është përmbushur apo jo. Blloqet logjike vendosen në fushat hyrëse të formës gjashtëkëndore të blloqeve të kontrollit.

**Koha aktuale dhe informacioni i përdoruesit**

Blloku i reporterit |time_unit| mund të japë informacionin e mëposhtëm për kohën aktuale.

.. image:: ../_images/11/fig11_6b.png
     :width: 200px   
     :align: center

.....

Blloqet Operator
~~~~~~~~~~~~~~~~~

.. sidebar:: |operator_blocks| Operators
    
   |fig11_7|
 
.. |fig11_7| image:: ../_images/11/fig11_7.png

Në grupin *Operatorët* nuk ka blloqe të pavarura, të cilat do të korrespondonin me komandat gjuhësore. Të gjitha blloqet janë blloqe funksioni, d.m.th. ato ruajnë vlerat e numrit, vargjeve ose shprehjeve logjike dhe ato futen në fushat përkatëse hyrëse të blloqeve të pavarura ose blloqeve të tjera të funksionit. Blloku |text_contains| është një bllok i ri në këtë grup, i cili kthen vlerat *true* ose *false* në varësi të faktit nëse vargu përmban karakterin e dhënë apo jo.

Ekzistojnë 18 blloqe në grupin *Operatorët* - 11 reporterë dhe 7 blloqe logjike (boolean), të cilat mundësojnë llojet e mëposhtme të operacioneve:

1. operacionet themelore aritmetike - shtimi, zbritja, shumëzimi dhe ndarja,

2. gjenerimi i numrave të rastit,

3. krahasimet - më të mëdha se, më pak se, të barabarta me,

4. ndërtimin e shprehjeve logjike komplekse,

5. operacione me tela,

6. operacione të plotë,

7. llogaritja e vlerës së funksioneve matematikore.

Operacionet themelore aritmetike mund të kryhen me numër të plotë dhe real. Vetëm ndarja me zero (pjesëtuesi = 0) mund të çojë në probleme, sepse nuk ka ndonjë numër që, kur shumëzohet me zero, do të jepte një numër tjetër përveç zeros (pjesëtori * pjesëtuesi = dividenti). Kjo është arsyeja pse ndarja me zero duhet të parandalohet në programe. Ne treguam se si mund të arrihet kjo në projekt *Matematikan i ri* nga mësimi 7 i këtij praktiku.

Si rezultat i ndarjes në zero, përkthyesi Scratch kthen njërën prej vlerave *Infinity*, *NaN* (jo një numër) ose *Përfundimi*, në varësi të faktit nëse dividenti është një numër pozitiv, zero ose një numër negativ .

Ne kemi shpjeguar përdorimin e numrave të rastit, shprehjeve logjike dhe shprehjeve logjike komplekse të formuara nga operacionet logjike *dhe*, *ose* dhe *jo* me shembujt e paraqitur në mësimet e mëparshme.

Operacionet e përdorura me string mundësojnë bashkimin e dy vargjeve, zgjedhjen e karaktereve të vendosura në pozicione të përcaktuara në varg, përcaktimin e gjatësisë së vargut dhe kontrolloni nëse vargu përmban karakterin e specifikuar. Operacioni i kryer në tela u shtjellua në mësimin 9 të këtij kursi.
 
Operacionet e numrave të plotë të mbështetur në Scratch janë llogaritja e pjesës tjetër në ndarjen e numrit të plotë dhe rrumbullakimi i numrave.

Funksionet matematikore që mund të zgjidhen nga lista drop-down e bllokut |function| janë:

.. hlist::
    :columns: 6

    * abs
    * floor
    * ceiling
    * sqrt
    * sin
    * cos
    * tan
    * asin
    * acos
    * atan
    * e^
    * 10^ 

.....

Variablat dhe Blloqet Lista
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. sidebar:: |variables_blocks| Variables and Lists
    
   |fig11_8|
 
.. |fig11_8| image:: ../_images/11/fig11_8.png

Funksionet e nëngrupeve janë këto:

Për variablat

1. reporterët për variablat e përdoruesit,

2. vendosjen dhe ndryshimin e vlerës së një variabli,

3. duke treguar dhe fshehur reporterë të ndryshueshëm në skenë.

Për listat

4. reporterët për listat e përdoruesve,

5. duke shtuar elemente në fund të listës,

6. operacionet e kryera në listë,

7. informacioni për listën e kthimit,

8. duke treguar dhe fshehur reporterët e listave në skenë.

Operacionet që janë mbështetur për të punuar me listat janë:

.. hlist::
    :columns: 1
    
    * fshirjen e një artikulli nga një pozicion i caktuar në listë,
    * fshirjen e të gjitha sendeve nga një listë e veçantë,
    * futja e artikujve në listë në pozicionet e dhëna, dhe
    * zëvendësimi i artikujve në pozicione të përcaktuara.

Informacioni i mëposhtëm mund të merret në lidhje me listën:

.. hlist::
    :columns: 1
    
    * cili artikull është në pozicionin e specifikuar,
    * cili është pozicioni (në listë) të sendit të specifikuar
    * gjatësia e listës (numri i artikujve në listë), dhe
    * nëse një artikull është përfshirë në një listë apo jo.

Variablat dhe listat mund të jenë globale - ato mund të përdoren nga të gjithë sprites, ose lokalë - ato mund të përdoren vetëm nga një sprite. Variablat dhe listat e krijuara për skenë janë të dukshme për të gjitha sprites.

Vlerat aktuale të variablave mund të ndiqen në skenë përmes monitorëve të ndryshueshëm. Monitorët e ndryshueshëm mund të vijnë në tre formate:

.. hlist::
    :columns: 1
    
    * shfaqja e vlerës me emrin e ndryshores,
    * shfaqje e madhe e vlerës pa emrin përkatës të ndryshores,
    * ekran që përmban një shirit rrëshqitës, i cili mund të përdoret për të ndryshuar vlerën e ndryshores.

Variablat janë shtjelluar në mësimin 7, dhe listat në mësimin 9 të këtij praktiku.
 
.....

Blloqet e mia
~~~~~~~~~~~~~~~~~

.. sidebar:: |my_blocks| My blocks
    
   |fig11_9|
 
.. |fig11_9| image:: ../_images/11/fig11_9.png

Mundësia që përdoruesi të bëjë blloqet e tij / saj dhe në këtë mënyrë të zbatojë procedurat u prezantua për herë të parë në versionin Scratch 2.0. Në versionin e ri të Scratch, ngjyra dhe forma e blloqeve të përdoruesit u ndryshuan.

Blloku përcaktues është blloku i parë që do të shfaqet kur përdoruesi kërkon të prezantojë një bllok të ri. Veprimet, të cilat duhet të kryhen nga ky bllok i prezantuar rishtazi, duhet të shtohen në bllokun e përcaktuar. Pastaj në paletën e bllokut do të shfaqet një pirg me emrin që i është caktuar në përkufizim. Blloku i ri i përcaktuar nga përdoruesi mund të përdoret më tej si çdo bllok tjetër.

Blloku i ri mund të ketë fushat e hyrjes. *Parametrat* futen në fushën e hyrjes së titullit të përkufizimit. Procedurat mund të kenë më shumë se një parametër. Kur blloku i ri përdoret për të thirrur një procedurë, në fushat e tij të hyrjes përdoruesi do të fusë *argumentet*. Argumentet zëvendësojnë çdo paraqitje të parametrave përkatës në procedurë.

Krijimi dhe përdorimi i blloqeve të prezantuara janë shtjelluar në mësimin 8 të këtij kursi.

.....

Blloqet e Pen Extension 
~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. sidebar:: |pen_extension| Pen
    
   |fig11_10|
 
.. |fig11_10| image:: ../_images/11/fig11_10.png

Në Scratch, secilës sprite mund të caktohet një pozicion, drejtim dhe orientim i lëvizjes dhe mund të lërë një shenjë gjatë lëvizjes. Duke vepruar kështu, madhësia, forma dhe ngjyra e sprite nuk kanë asnjë efekt në shenjën e lënë nga vizatimi i sprite me një stilolaps. Sprite mund të jetë e padukshme, ose mund të përbëhet nga një pikë e vetme, por kjo nuk ndikon në vizatimin e saj. Mundësia e sprite për të lënë një shenjë gjatë lëvizjes bazohet në blloqe të këtij grupi. Imazhet që janë krijuar nga sprites ruhen si një koleksion figurash, së bashku me parametrat e tyre. Imazhet e përcaktuara në këtë mënyrë quhen *grafika vektoriale*.

Blloqet në shtrirjen *Pen* janë të ndara në 5 nëngrupe. Komanda e stilolapsit Shade nga versionet e mëparshme është nxjerrë, dhe në vend që të vendosni ngjyrën e stilolapsit vetëm nga numri, ngjyra tani përcaktohet nga ngjyrimi, ngopja dhe shkëlqimi. Të gjitha blloqet që i përkasin këtij grupi janë blloqe pirgësh.

Funksionet e nëngrupeve janë:

1. fshirja e çdo gjëje e tërhequr (heqja e të gjitha shenjave të stilolapsit nga skena),

2. vulosja e sprite,

3. vendosjen e stilolapsit lart ose poshtë,

4. vendosjen dhe ndryshimi i atributeve të stilolapsit,

5. vendosja dhe ndryshimi i madhësisë së stilolapsit (trashësia).

Redaktori grafik në këtë version të Scratch është duke punuar me të ashtuquajturin model ngjyrash HSB (Hue, Saturation, Brightness). Kjo do të thotë që ngjyra është e ndërtuar me 3 përbërës: Hue, ngopje dhe shkëlqim. Hija e ngjyrave tregon numrin e ngjyrave në paletën spektrale, domethënë vetë ngjyrën. Është përshkruar në një rreth ngjyrash, në të cilin këndi 0 ° përfaqëson ngjyrën e kuqe të ngjyrës (numri i ngjyrës është zero), dhe këndi 180 ° paraqet ngjyrën blu-jeshile të quajtur cyan (numri i ngjyrës 100). Ngopja i referohet intensitetit të ngjyrës - sa më e lartë të jetë ngopja, aq më e pastër është ngjyra. Ngopja mund të jetë nga 0 në 100%, me intensitetin 0% që përfaqëson të bardhë dhe ngjyrën e pastër me intensitet 100%. Shkëlqimi i ngjyrës varet nga sasia e ngjyrës së zezë të përzier me ngjyrën e vrojtuar.

.....

Blloqet Text to Speech dhe Translate Extensions
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. sidebar:: |voices_extension| Text to Speech and |translate_extension| Translate
    
   |fig11_11|
 
.. |fig11_11| image:: ../_images/11/fig11_11.png


**Zgjatja e tekstit në të folur**

Kjo zgjatje mund të përdoret vetëm nëse kompjuteri është i lidhur me Internet |requires|, sepse ai përdor Shërbimet Ueb në Amazon.

Kur zgjidhni |voices_extension| nga grupi *Zgjatjet*, tre blloqe të reja do të shfaqen në paletën e bllokut. Ato lejojnë që sprite të thotë tekstin e futur në fushën hyrëse të bllokut të parë, në gjuhën e vendosur nga përdoruesi me bllokun e tretë nga ky grup. Përdoruesi mund të vendosë edhe zërin, i cili në të vërtetë do të flasë tekstin: femër (soprano ose alto) ose mashkull (tenor ose bas). Kjo është vendosur nga një bllok tjetër nga ky grup.

**Përkthim i zgjatjes**

Kjo shtesë mund të përdoret vetëm nëse kompjuteri është i lidhur në Internet |requires|, sepse përdor Google.

Kur ju zgjidhni |translate_extension| nga *Zgjatjet*, dy blloqe të reja shfaqen në paletën e bllokut. Ato lejojnë që teksti i shkruar në një gjuhë të përkthehet në një gjuhë tjetër. Blloku |language| tregon se cila gjuhë është e vendosur në Scratch. Teksti i shkruar në gjuhën e tanishme në fushën e parë hyrëse të bllokut |translate_to| është përkthyer në gjuhën e zgjedhur nga lista rënëse e fushës së dytë të hyrjes. Nëse blloku i përkthimit vendoset në fushën hyrëse të bllokut ``say`` ose ``think``, përdoruesi mund të shohë përkthimin.

Përdorimi i redaktorit të integruar të grafikëve (bojës)
----------------------------------------------------------

Scratch ka një redaktues të integruar të bojrave që mund të përdorni për të krijuar dhe modifikuar sprites, kostumet dhe sfondet. Kjo edito

.. infonote:: 

  Kompjuterët mund të ruajnë imazhet në dy mënyra: raster dhe vektor.
  
   Në grafikët **raster** imazhi ruhet si një rrjet drejtkëndësh i pikselave - bitmap. Bitmap-i përcaktohet teknikisht nga gjerësia dhe lartësia e sprite në pixel dhe nga numri i bitëve të nevojshëm për të ruajtur ngjyrën e pikselave. Për shembull, nëse kemi 16 ngjyra, nevojiten 4 bit për pixel për ruajtjen e ngjyrës së tij. Grafika e rasterit varet nga rezolucioni. Imazhet në raster nuk mund të zmadhohen pa humbur cilësinë e figurës.

   Ky disavantazh tejkalohet nga aplikimi i grafikës **vektor**, i cili ruan një imazh si koleksion figurash së bashku me të dhënat e tij (parametrat) që përcaktojnë se si do të vizatohet figura dhe ku do të vendoset. Grafika e breshkës është një shembull i grafikëve vektoriale.

   Figura e mëposhtme tregon një imazh të zgjeruar të një linje të tërhequr në këto dy mënyra.

  .. image:: ../_images/11/fig11_12.png
     :width: 210px   
     :align: center

Ndërfaqja e përdoruesit
~~~~~~~~~~~~~~~~~~~~~~~~~~~

Figura e mëposhtme tregon paraqitjen e redaktorit të ngjyrave të integruara në mënyrën vektoriale dhe rasteri.

.. image:: ../_images/11/fig11_13.png
     :width: 1200px   
     :align: center

.. sidebar:: Kostume të reja
    
   |novi|
 
.. |novi| image:: ../_images/11/fig11_14.png

**Zona e Kostumit**

Në të majtë është zona e kostumit (1) me ikona për çdo kostum dhe numrin rendor të kostumit. Në fund të zonës së kostumit është një buton për krijimin e kostumeve të reja. Për të modifikuar kostume të ndryshme në redaktorin e pikturës, thjesht klikoni në ikonën e kostumit të dëshiruar dhe imazhi përkatës do të shfaqet në zonën e redaktimit - zona e vizatimit ose kanavacë (7).

Ju mund të shtoni një kostum të ri (ose sfond) duke rri pezull mbi butonin |b_sprite| vendosur në fund të kësaj zone me treguesin e miut dhe zgjedhjen e njërës nga opsionet që do të shfaqet. Ju mund të zgjidhni një kostum nga libraria e kostumeve, të vizatoni vetë, të shkarkoni një skedar imazhi nga kompjuteri juaj, të bëni një fotografi ose të zgjidhni një "kostum surprizë", i cili zgjidhet rastësisht nga libraria e kostumeve.

Shënim. Libraria e kostumeve përmban kostume individuale të të gjitha sprites që gjenden në bibliotekën e sprites.

.. sidebar:: Ndryshimi i gjendjes së operatorit 
    
   |vector_bmp|
   
   |bmp_vector|
 

**Konvertimi i mënyrës vektoriale në modalitetin e rasterit dhe anasjelltas**

Nën këndin e poshtëm të majtë të zonës së vizatimit është butoni (2) që ndërron redaktorin nga një modalitet në një tjetër. Mjetet specifike për mënyrën e veçantë mund të gjenden në anën e majtë të ekranit pranë zonës së vizatimit, në figurën tonë mënyra e vektorit shënohet me (5) dhe modalitetin raster (bitmap) me (6). Opsionet mund të shihen sipër zonës së vizatimit (kanavacë). Disa prej tyre janë të zakonshme për të dy mënyrat e funksionimit, në figurë, këto opsione janë përshtatur me drejtkëndësha të kuq (3), dhe disa prej tyre vlejnë vetëm për mënyrën vektoriale, këto janë të përshtatura me drejtkëndësha gri (4).

Opsione të zakonshme
~~~~~~~~~~~~~~~~~~~~~~~~~

Këto opsione janë të vendosura mbi zonën e vizatimit.

.. sidebar::  Ndryshimi i ngjyrës
    
   |promena_boje|
 
.. |promena_boje| image:: ../_images/11/fig11_15.png

|fill| **Ndryshimi i ngjyrës**

Duke klikuar në fushën hyrëse të bllokut që përdoret për të vendosur ngjyrën, do të hapni një menyë drop-down që përmban rrëshqitës: ngjyrën, ngopjen dhe shkëlqimin dhe nën to një mjet eyedropper (pipetë) për marrjen e mostrës së ngjyrës. Ju mund të vendosni ngjyrën që dëshironi duke lëvizur rrëshqitësin ose duke klikuar mjetin e syrit.

Lëvizja e shiritit *color* ndryshon ngjyrën e ngjyrës (për shembull, nga e kuqja në blu). Ky mjet është më shpesh i përdorur sepse ka ndryshimin më të madh midis ngjyrave.
Zhvendosja e ngopjes *e saturation* ndryshon intensitetin e ngjyrës: ngopja 100 është ngjyra e zgjedhur, 50 - është një ngjyrë më e lehtë, dhe 0 - është plotësisht e bardhë.
Lëvizja e shkëlqimit *brightness* ndryshon sa e errët është ngjyra: shkëlqimi 0 është plotësisht i zi, ndërsa 100 është ngjyra e zgjedhur.

Kur klikoni në mjetin e syrit, shfaqet një xham zmadhues me një rreth në qendër.
Për të zgjedhur ngjyrën e dëshiruar, duhet të vendosni qendrën e xhamit zmadhues mbi pjesën e zonës së vizatimit në të cilën ndodhet ajo ngjyrë dhe të klikoni.

Ekzistojnë katër opsione sipër tre rrëshqitësve. Këto mundësojnë mënyra të ndryshme të mbushjes së një zone me ngjyra. Një zonë mund të plotësohet në mënyrë të barabartë me një ngjyrë të fortë, ose si një gradient, me hije të ndryshme të një ngjyre. Nëse klikoni në njërën prej opsioneve përveç opsionit të ngjyrave të ngurta, do të shfaqen dy ngjyra të zgjedhura: |swap|. Duke klikuar në ngjyrën e parë ose të dytë ju mund t'i vendosni ato. Klikimi i *swap* midis dy ngjyrave ndryshon rendin e tyre. Opsionet e mbushjes janë: ngjyra e ngurtë, gradient vertikal, gradient horizontal ose gradient rrethi.

|Size| **Ndryshimi i madhësisë së stilolapsit**

Ekziston një fushë hyrëse për të zgjedhur madhësinë e stilolapsit (trashësinë). Ju mund të shkruani madhësinë ose të përdorni shigjetat në anën për ta ndryshuar atë. Sa më i lartë numri, aq më i trashë është linja.

|Name| **Emërtimi i Kostumeve**

Emri i kostumit është i rëndësishëm për organizatën dhe nganjëherë edhe për programimin e projektit. Meqenëse çdo kostum është caktuar numri i sekuencës së tij, nuk rekomandohet të vini emrat e kostumeve vetëm duke përdorur numra pa ndonjë karaktere të tjera. Për të emëruar një kostum, duhet të klikoni në shiritin e tekstit në këndin e sipërm të majtë të redaktorit të bojës dhe të shkruani emrin e ri.

|Copy| **Kopjimi dhe ngjtija** |paste|

Rreshti i dytë i opsioneve përfshin butonat kopjues dhe ngjitës. Opsioni i kopjimit kopjon zonën e zgjedhur, ndërsa paste e vendos atë diku tjetër. Ju gjithashtu mund të përdorni shkurtoret e tastierës: Ctrl + C për të kopjuar dhe Ctrl + V për të ngjitur. Së pari, zgjidhni zonën drejtkëndëshe që dëshironi të kopjoni dhe pastaj tërhiqeni atë atje ku dëshironi të vendosni kopjen.

|Redo| **Zhbëj**

Në të djathtë, pranë emrit të kostumit, ka dy butona që quhen prishje dhe ribërë. Këto butona ju lejojnë të prishni veprimin e fundit ose të përsërisni veprimin që më parë i keni zhbërur. Butoni i ribërë nuk mund të përdoret nëse nuk është përdorur butoni i prishjes. Nëse dilni nga redaktori i bojës, gjithçka që keni bërë në të do të bëhet e përhershme dhe ajo vetëm mund të zhvishet me dorë. Shkurtorja e tastierës për opsionin e prishjes është Ctrl + Z.


|Flip_h| **Fluturimi horizontal** |flip_v| **Fluturimi vertikal**

Kur zgjidhni një objekt, ekziston mundësia që ta rrokullisni atë horizontalisht ose vertikalisht. Në rreshtin e dytë të opsioneve, ka dy butona me dy shigjeta secila duke treguar një vijë pikash. Një në të majtë rrotullon objektin e zgjedhur horizontalisht, dhe atë në të djathtë vertikalisht.

Opsionet e redaktorit të vektorit
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Këto opsione janë të disponueshme vetëm kur redaktori grafik është në modalitetin e vektorit dhe nuk shfaqet kur është në modalitetin e rasterit.

**Lëvizja e saktë e objektit**

Kur një objekt zgjidhet në redaktorin e vektorit, çelësat e shigjetave mund të përdoren për ta lëvizur atë saktësisht një piksel. Në redaktorin e rasterit, përdoruesi mund të përdorë gjithashtu tastet me shigjeta për të lëvizur zonat e zgjedhura. Ky opsion mund të jetë i dobishëm nëse doni të bëni një vizatim të saktë ose të rreshtoni objektet e ndryshme.

.. sidebar::  Ndryshimi konturit
    
   |promena_konture|
 
.. |promena_konture| image:: ../_images/11/fig11_16.png

|outline| **Konturi**

Në të djathtë të opsionit të përdorur për vendosjen e ngjyrës, ekziston një menu drop-down që lejon përdoruesin të ndryshojë skicat e objekteve. Kjo menu që bie poshtë ka tre rrëshqitëse, por ndryshe nga menyja për përcaktimin e ngjyrave, këtu përdoruesi nuk ka mundësinë të përziejë dy ngjyra të ndryshme. Në të djathtë, pranë asaj menyje rënëse, është një fushë hyrëse ku përdoruesi mund të zgjedhë trashësinë e skicës. Mund të shkruani një numër ose të përdorni shigjetat për ta ndryshuar atë.

**Shtrirja e figurës**

Ne mund të përdorim analogjinë e mëposhtme për të shpjeguar sesi sprites prezantohen në skenë. Imagjinoni që secila sprite është vizatuar në një fletë të veçantë të letrës së tejdukshme dhe që të gjitha fletët të grumbullohen mbi atë në të cilën është pikturuar sfondi. Në Scratch, këto fletë transparente korrespondojnë me **shtresat**. Sa herë që lëviz një sprite, do të mbulojë imazhet e vizatuara në shtresat poshtë tij.

Në pjesën e sipërme të djathtë të redaktorit të pikturave, ka katër butona, të cilat ju lejojnë të lëvizni objektet nëpër shtresa të ndryshme:

.. hlist::
    :columns: 1
    
    * |v_forward| e zhvendos objektin një shtresë përpara (përpara asaj aktuale),
    * |v_front| lëviz objektin gjatë gjithë rrugës përpara
    * |v_backward| zhvendos objektin një shtresë prapa (pas asaj aktuale),
    * |v_back| lëviz objektin gjatë gjithë rrugës prapa.

|v_group| **Grupimi** |v_Ungroup| **Çgrupimi**

Ky opsion përdoret për të grupuar shumë objekte në një tërësi. Kur ka shumë objekte që ju duhet të lëvizni menjëherë, mund të jetë e dobishme t'i gruponi ato. Në këtë mënyrë, të gjithë mund të zhvendosen ose fshihen në të njëjtën kohë. Për të zgjedhur objektet, klikoni dhe tërhiqni treguesin e miut mbi objektet e dëshiruara (ose mbani shtypur butonin Shift në tastierë dhe klikoni në secilin objekt), dhe pastaj klikoni në opsionin e grupimit. Nga kjo pikë e tutje, të gjitha objektet do të trajtohen si një objekt i vetëm.

Opsioni ungrouping bën të kundërtën - grupi i zgjedhur mund të ndahet në pjesë më të vogla. Ky buton do të bëhet i dukshëm pasi të keni zgjedhur një grup objektesh dhe do t'ju lejojë të mos grumbulloni ato.

|V_curved| **i lakuar** |v_pointed| **shënim**

Kur përdorni mjetin e riformësimit, ekzistojnë dy mundësi në të djathtë të skicave, të cilat ju lejojnë të bëni skajet ose të lakuara, si një elips ose të theksuar, si një drejtkëndësh. Kjo është e dobishme kur krijoni forma me të dy skajet e lakuara dhe të theksuara. Nëse zgjidhen më shumë se një pikë (mbajeni tastin shift dhe klikoni në më shumë se një), ndryshimi i specifikuar do të zbatohet në të gjitha pikat e zgjedhura.

Duke punuar në modën Raster 
~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. sidebar:: Veglat Raster 

   |rasterski|

.. |rasterski| image:: ../_images/11/fig11_17.png
  
|r_brush| **Vizatim i lirë**

Ju mund të vendosni ngjyrën dhe madhësinë (trashësinë) e furçës së bojës me opsionet e duhura. Përdorni opsionet e prishjes dhe ribërë nëse bëni një gabim. Ju gjithashtu mund të përdorni gomë për korrigjimin e gabimeve.

|r_line| **Vizato një vijë të drejë**

Ju mund të ndryshoni trashësinë e linjës me opsionin e duhur. Shtypni Shift dhe tërhiqni për të vizatuar linja horizontale ose vertikale.

|r_circle| **Vizato një Ellips**

Mund të vizatoni një elips të thjeshtë ose të mbushur (me ngjyra). Shtypni Shift dhe tërhiqni për të vizatuar një rreth. Me opsionet e duhura, ju mund të zgjidhni stilin e mbushjes dhe të ndryshoni trashësinë e skicës.

|r_rectan| **Vizato një drejtkëndësh**

Ju mund të vizatoni një drejtkëndësh të thjeshtë ose të mbushur (me ngjyra). Shtypni Shift dhe tërhiqni për të vizatuar një drejtkëndësh. Me opsionet e duhura, ju mund të zgjidhni stilin e mbushjes dhe të ndryshoni trashësinë e skicës

.. sidebar:: Tekst

 |text|

.. |text| image:: ../_images/11/fig11_18.png

|r_text| **Teksti i të shkruarit**

Klikoni kudo në zonën e vizatimit (kanavacë) dhe kur kursori shfaqet, shtypni tekstin e dëshiruar. Pastaj klikoni jashtë zonës së tekstit. Mjeti i zgjedhur automatikisht zgjedh tekstin, kështu që ju mund të ndryshoni madhësinë dhe orientimin e tij. Ju mund të përdorni kutinë e matjes që shfaqet në skajin e jashtëm të kutisë së zgjedhjes (rrathë dhe shigjeta rreth tekstit) për të ndryshuar madhësinë dhe për të ndryshuar orientimin e tekstit.

|R_fill| **Mbushja e zonave të mbyllura me ngjyra**
 
Ju mund ta mbushni zonën në mënyrë të barabartë me një ngjyrë ose si një gradient, me hije ngjyrash duke përdorur opsionin e duhur të mbushjes.

|R_eraser| **Vegël për fshirje jo manualisht**

Ju mund të vendosni madhësinë e gomës duke përdorur opsionin e duhur. Zonat e fshira bëhen transparente.

|R_select| **Zgjedhja e një zone në formë drejtkëndëshi**

Zona e zgjedhur mund të jetë:

1. tërhequr në një lokacion të ri,

2. të bëra më të mëdha, të bëra më të vogla ose të rrotulluara,

3. fshihet duke shtypur butonin Del në tastierë.

Punimi në mënyrën vektoriale
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

.. sidebar:: Veglat e vektorit

 |vektorski|

.. |vektorski| image:: ../_images/11/fig11_19.png

|v_select| **Selecting an Object**

This tool is used for moving, erasing, resizing and rotating objects. When you click on an object, a frame will appear around it |izbor_objekta|, which indicates that the object is selected.

.. |izbor_objekta| image:: ../_images/11/fig11_20.png

Nëse dëshironi të zgjidhni shumë objekte menjëherë, klikoni në butonin e majtë të miut dhe tërhiqni miun mbi objektin e dëshiruar ose mbani tastin Shift dhe klikoni në secilin objekt që dëshironi të zgjidhni në të njëjtën kohë.
Kur zhvendosni kursorin afër qendrës së objektit, ai ndryshon formën e tij dhe bëhet një dorë, që do të thotë se ju mund ta lëvizni objektin në telajo. Objekti gjithashtu mund të zhvendoset me tastet e shigjetës së tastierës.
Objekti i zgjedhur mund të fshihet duke shtypur butonin Del. Objektet mund të ndryshohen në madhësi me kutitë e matjes që shfaqen në skajin e jashtëm të kutisë së zgjedhjes.
Për të rrotulluar një objekt, kapni dhe tërhiqni shigjetat e rrotullimit.

|V_reshape| **Ristrukturimi i një objekti**

Klikoni në objektin që dëshironi të riorganizoni dhe një grup pikash kontrolli do të shfaqen në perimetrin e objektit, siç tregohet në figurën (1). Klikoni në njërën nga pikat e kontrollit dhe tërhiqni (2). Duke klikuar në skicën e objektit mund të krijoni pika të tjera kontrolli (3). Ju mund të fshini një pikë kontrolli duke sjellë kursorin në të (4). Pika e zgjedhur do të ndryshojë ngjyrën dhe pastaj duhet të klikoni mbi të (5). Butonat |v_curved| dhe |v_pointed|, të cilat paraqiten në opsione, ju lejojnë të lakoni ose drejtoni skicën e objektit.

.. image:: ../_images/11/fig11_21.png
   :width: 680px   
   :align: center

|V_brush| **Vizatimi pa duar**

Ky mjet është i ngjashëm me mjetin përkatës në modalitetin e rasterit. Mbajeni kursorin e miut dhe lëvizeni për të vizatuar një vijë të lakuar. Në vend të pikselave, linja këtu përcaktohet nga një grup pikash kontrolli. Mund të ndryshoni pamjen e rreshtit me mjetin *Rishape*.

|V_eraser| **Eraser**

Ky mjet është i ngjashëm me mjetin përkatës në modalitetin e rasterit.

|V_fill| **Mbushja e zonave të mbyllura me ngjyra ose ngjyrosja e skicës së një objekt**

Mjeti i kovës së bojës në modalitetin vektor funksionon ndryshe sesa në mënyrën e rasterit, ku mjet plotëson çdo zonë të zgjedhur të mbyllur. Kova e mënyrës vektoriale funksionon vetëm me objekte vektoriale. Pas zgjedhjes së këtij mjeti, mund të ndryshoni ngjyrën ose ngjyrën skicë të një objekti duke klikuar mbi të.

|V_text| **Teksti i të shkruarit**

Klikoni në mjet dhe pastaj kudo në kanavacë; kur shfaqet kursori, filloni të shtypni tekstin e dëshiruar. Pasi të keni mbaruar, klikoni kudo tjetër jashtë zonës së tekstit. Mjeti *Choose* do të zgjedhë automatikisht tekstin, në mënyrë që të ndryshoni madhësinë dhe orientimin e tij. Për dallim nga teksti në modalitetin e rasterit, teksti i krijuar në modalitetin vektor mund të redaktohet në çdo kohë, edhe pas daljes nga redaktori i pikturës. Për të qenë në gjendje të modifikoni përmbajtjen e tij, ju vetëm duhet të zgjidhni tekstin.

|V_line| **Vizatimi i një vije të drejtë**

Linja përcaktohet nga dy pika kontrolli në të dy skajet. Për të vizatuar një rresht, klikoni dhe mbani miun ku dëshironi të fillojë rreshtin dhe tërhiqni për të tërhequr vijën në pikën e fundit. Për të vizatuar një vijë horizontale ose vertikale, mbani shtypur butonin Shift ndërsa tërhiqni miun.

Për të vizatuar një vijë të lakuar, së pari duhet të vizatoni një vijë të drejtë, pastaj zgjidhni mjetin *Rishape*, shtypni Shift dhe klikoni kudo në vijë për të krijuar një pikë të re dhe më pas tërhiqni pikën e re të kontrollit. Kjo është një mënyrë për të formuar një vijë të lakuar.

|V_circle| **Vizatimi i një Elipsi**

Përdorni këtë mjet nëse doni të vizatoni një elips në ngjyrën e zgjedhur për vizatim. Klikoni për të nënvizuar këndin e sipërm të majtë, pastaj tërhiqni (mbani tastin shift ndërsa vizatoni me mjetin e elipsit) derisa të merrni madhësinë që dëshironi. Ju mund të ndryshoni stilin e mbushjes (të mbushur ose bosh) dhe trashësinë e linjës duke përdorur butonat në zonën e opsioneve. Elipsi i krijuar ka 4 pika kontrolli në mënyrë të barabartë.

|V_rectan| **Vizatimi i një drejtkëndëshi**

Përdorni këtë mjet nëse doni të vizatoni një drejtkëndësh në ngjyrën e zgjedhur për vizatim. Klikoni për të nënvizuar këndin e sipërm të majtë, pastaj tërhiqni (mbani tastin shift ndërsa vizatoni me mjetin drejtkëndësh) derisa të merrni madhësinë që dëshironi. Ju mund të ndryshoni stilin e mbushjes (të mbushur ose bosh) dhe trashësinë e linjës duke përdorur butonat në zonën e opsioneve. Drejtkëndëshi i krijuar ka 4 pika kontrolli, një në secilin skaj.

Duke përdorur Redaktorin e Tingullit të Ndërtuar
----------------------------------------------------

Redaktori i tingullit lejon përdoruesit të modifikojnë dhe rimodelojnë tinguj. Në muzikë, termi *remix* përdoret për t'iu referuar një versioni të ri, të modifikuar të një përbërje muzikore.

Ndërfaqja e përdoruesit
~~~~~~~~~~~~~~~~~~~~~~~~

Dritarja e redaktorit të tingullit është e ndarë në dy fusha: lista e tingullit (1) dhe zona e redaktimit (2).

.. image:: ../_images/11/fig11_22.png
   :width: 880px   
   :align: center

.. sidebar:: New Sound

 |novi_zvuk|

.. |novi_zvuk| image:: ../_images/11/fig11_23.png

**Lista e Tingullit**

Lista e tingujve ndodhet në anën e majtë të dritares dhe përdoret për zgjedhjen e tingujve, të cilat do të redaktohen në zonën e redaktimit. Ju zgjidhni një tingull duke klikuar mbi të. Një skicë e trashë blu do të shfaqet rreth ikonës së tingullit të zgjedhur, e ngjashme me atë rreth rrjedhës aktive në listën e sprite. Një "x" shfaqet në këndin e sipërm të majtë të degëzës aktive, e cila lejon që ajo të fshihet.

Në fund të zonës, ka një buton |b_sound|, i cili mundëson futjen e tingujve të rinj.

**Zona e redaktimit**

Zona e redaktimit ka një shirit në majë (3), një paraqitje grafike të një tingulli në mes (4) dhe një shirit në fund (5), i cili përmban 7 mjete.

Në shiritin e lartë janë mjetet që redaktojnë tingullin, por nuk shtojnë asnjë efekt. Këto janë:

.. hlist::
    :columns: 1
    
    * një fushë emri për tingullin,
    * butonat e ribërë dhe ribërë, dhe
    * butoni |trim|, i cili fshin pjesët e zgjedhura të tingullit.

Në shiritin e poshtëm janë mjetet, të cilat bëjnë efekte speciale ndërsa tingulli është duke luajtur:

.. hlist::
    :columns: 1

    * |faster| - faster,
    * |slower| - slower,
    * |echo| - echo,
    * |robot| - robot,
    * |louder| - louder,
    * |softer| - softer and
    * |reverse| - reverse, makes the sound run backward. 
    
Bërja e tingullit më e shpejtë ose e ngadaltë arrihet duke luajtur notën më të lartë ose më të ulët në vend të asaj aktuale. Efekti jehon arrihet duke riprodhuar tingullin pas 0,15 sekondash.




