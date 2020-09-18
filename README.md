The problem with many available frequency lists is that they don't take word morphologies into account. For example, in English, "playing" and "played" might be found seperated in a frequency list. This code adresses this issue by taking morphology into account. An experiment word list order by frequency is in the "5000.txt" file.

## Example:
The file 5000.txt (in the 'data' folder) contains top 5000 German words ranked by frequency based on German movie subtitles. It only display one form of each group of word morphologies. The list was just generated from the code available here and needs some refinement.

- The data was generated via [LuminosoInsight](https://github.com/LuminosoInsight/wordfreq) and [german-morph-dictionaries](https://github.com/DuyguA/german-morph-dictionaries).

## Top 1000 German word (ommiting their morphologies):

     1.ich
     2.das
     3.hat
     4.ein
     5.nicht
     6.und
     7.zu
     8.in
     9.was
    10.wird
    11.kann
    12.mit
    13.ja
    14.wie
    15.auf
    16.dass
    17.aber
    18.will
    19.an
    20.gut
    21.so
    22.von
    23.hier
    24.sagen
    25.bitte
    26.für
    27.geht
    28.komm
    29.machen
    30.wenn
    31.keine
    32.alles
    33.muss
    34.nein
    35.diese
    36.sehen
    37.noch
    38.da
    39.tun
    40.nur
    41.weiß
    42.soll
    43.schon
    44.auch
    45.mal
    46.als
    47.jetzt
    48.um
    49.aus
    50.dann
    51.doch
    52.hör
    53.lassen
    54.oder
    55.dachte
    56.nach
    57.viel
    58.bei
    59.nichts
    60.man
    61.wo
    62.wissen
    63.etwas
    64.oh
    65.mehr
    66.also
    67.danke
    68.wer
    69.immer
    70.warum
    71.ganz
    72.vor
    73.los
    74.liebe
    75.glaube
    76.wieder
    77.finden
    78.leben
    79.sehr
    80.okay
    81.denn
    82.möchte
    83.vielleicht
    84.brauchen
    85.über
    86.anderen
    87.nehmen
    88.wirklich
    89.einfach
    90.nie
    91.weg
    92.hey
    93.bringen
    94.hause
    95.leid
    96.weil
    97.warte
    98.fall
    99.verstehe
   100.lange
   101.reden
   102.bleiben
   103.jeder
   104.nun
   105.schön
   106.heute
   107.tag
   108.sicher
   109.steht
   110.fragen
   111.fahren
   112.weiter
   113.jemand
   114.damit
   115.kennen
   116.bis
   117.kleine
   118.erst
   119.zurück
   120.helfen
   121.große
   122.na
   123.zwei
   124.hallo
   125.alter
   126.halten
   127.sprechen
   128.genau
   129.versuchen
   130.morgen
   131.passiert
   132.klar
   133.richtig
   134.spielen
   135.junge
   136.neue
   137.darf
   138.ab
   139.gerade
   140.heißt
   141.durch
   142.letzte
   143.gleich
   144.töten
   145.sterben
   146.raus
   147.ob
   148.paar
   149.nächste
   150.bekommen
   151.verdammt
   152.suchen
   153.wohl
   154.erzählt
   155.scheiße
   156.läuft
   157.krieg
   158.selbst
   159.her
   160.recht
   161.arbeiten
   162.ohne
   163.essen
   164.schnell
   165.tot
   166.stimmt
   167.holen
   168.gar
   169.wieso
   170.treffen
   171.beide
   172.dort
   173.natürlich
   174.stellen
   175.später
   176.niemand
   177.ruf
   178.seit
   179.ach
   180.davon
   181.zeigen
   182.dinge
   183.allein
   184.vergessen
   185.verloren
   186.dafür
   187.drei
   188.wegen
   189.hin
   190.rein
   191.welche
   192.schau
   193.sorgen
   194.unter
   195.fühle
   196.schlafen
   197.schaffen
   198.zusammen
   199.liegt
   200.wahr
   201.ziehen
   202.genug
   203.echt
   204.setzen
   205.gegen
   206.wenig
   207.toll
   208.einmal
   209.sonst
   210.erinnern
   211.nennen
   212.dabei
   213.sofort
   214.halt
   215.ende
   216.pass
   217.bevor
   218.stunden
   219.entschuldigen
   220.einzige
   221.schlecht
   222.fangen
   223.verschwinden
   224.hoch
   225.fertig
   226.trinken
   227.wann
   228.schicken
   229.verrückt
   230.früher
   231.darüber
   232.ne
   233.freunde
   234.bereit
   235.daran
   236.wichtig
   237.dazu
   238.schreiben
   239.reicht
   240.eigentlich
   241.nett
   242.schlagen
   243.kurz
   244.hoffe
   245.gern
   246.sitzen
   247.teil
   248.bedeutet
   249.egal
   250.falsch
   251.verlassen
   252.all
   253.legen
   254.lernen
   255.schwer
   256.lesen
   257.glück
   258.einige
   259.schuld
   260.schlimm
   261.retten
   262.tragen
   263.angerufen
   264.bisschen
   265.scheint
   266.darauf
   267.bald
   268.kaufen
   269.ruhe
   270.kümmern
   271.runter
   272.voll
   273.ruhig
   274.arm
   275.eigenen
   276.draußen
   277.hinter
   278.folgen
   279.wagen
   280.versprochen
   281.bestimmt
   282.ziemlich
   283.vorbei
   284.plan
   285.herz
   286.hi
   287.fast
   288.gerne
   289.dran
   290.wach
   291.umbringen
   292.gewinnen
   293.sogar
   294.überhaupt
   295.stark
   296.he
   297.drin
   298.vertrauen
   299.wünschte
   300.lachen
   301.darum
   302.frei
   303.woher
   304.steckt
   305.je
   306.fliegen
   307.laut
   308.während
   309.endlich
   310.hasse
   311.erwartet
   312.oben
   313.klingt
   314.heiraten
   315.niemals
   316.glücklich
   317.bezahlen
   318.fünf
   319.lügen
   320.etwa
   321.beweise
   322.ernst
   323.anders
   324.gestern
   325.möglich
   326.erklären
   327.verkaufen
   328.vier
   329.süß
   330.zimmer
   331.eben
   332.benutzt
   333.anfangen
   334.miss
   335.deshalb
   336.ändern
   337.film
   338.freut
   339.beginnen
   340.kämpfen
   341.zwischen
   342.spaß
   343.schreit
   344.fest
   345.dies
   346.manchmal
   347.wiedersehen
   348.aufhören
   349.wein
   350.entschuldigung
   351.wohnen
   352.verdient
   353.reise
   354.äh
   355.versteckt
   356.platz
   357.schiff
   358.schule
   359.unten
   360.funktioniert
   361.bloß
   362.schätze
   363.geschehen
   364.hart
   365.böse
   366.dumm
   367.ehrlich
   368.brechen
   369.dauert
   370.zahlen
   371.werfen
   372.aussehen
   373.langsam
   374.dasselbe
   375.zeug
   376.solche
   377.oft
   378.wohin
   379.leicht
   380.entscheiden
   381.singen
   382.bewegen
   383.besuch
   384.menge
   385.öffnen
   386.drauf
   387.wahrscheinlich
   388.falls
   389.irgendwie
   390.verbrechen
   391.krank
   392.drehen
   393.interessiert
   394.hübsch
   395.hierher
   396.irgendwas
   397.zuerst
   398.verletzt
   399.bereits
   400.gestohlen
   401.tanzen
   402.außer
   403.erledigt
   404.direkt
   405.froh
   406.großartig
   407.steig
   408.sondern
   409.schwarze
   410.erfahren
   411.schießen
   412.willkommen
   413.ließ
   414.besorgt
   415.vorstellen
   416.kaum
   417.klappe
   418.erkennen
   419.hängt
   420.sechs
   421.opfer
   422.zehn
   423.wert
   424.acht
   425.buch
   426.ehre
   427.fehlt
   428.bauen
   429.halb
   430.zweite
   431.überall
   432.laden
   433.ansehen
   434.vermisst
   435.perfekt
   436.völlig
   437.zerstört
   438.herausfinden
   439.trotzdem
   440.still
   441.hm
   442.erde
   443.schwierig
   444.weh
   445.behalten
   446.cool
   447.licht
   448.druck
   449.raten
   450.tief
   451.i
   452.normal
   453.wunder
   454.angriff
   455.schwöre
   456.schrecklich
   457.deswegen
   458.danach
   459.träume
   460.total
   461.spannende
   462.lustig
   463.sinn
   464.melden
   465.schade
   466.regeln
   467.ziel
   468.stören
   469.gefährlich
   470.überleben
   471.treten
   472.erreichen
   473.wow
   474.beruhigen
   475.blöd
   476.fassen
   477.selber
   478.nochmal
   479.nachdem
   480.komisch
   481.kostet
   482.himmel
   483.guck
   484.drüben
   485.rot
   486.persönlich
   487.deutsche
   488.übernehmen
   489.weise
   490.irgendwo
   491.haare
   492.tja
   493.genauso
   494.wunderbar
   495.vorsichtig
   496.damals
   497.zwar
   498.verzeihen
   499.beeil
   500.unglaublich
   501.ärger
   502.seltsam
   503.heilige
   504.kalt
   505.antworten
   506.stolz
   507.irgendeine
   508.nachgedacht
   509.bekannt
   510.merken
   511.rolle
   512.o
   513.offen
   514.fürchte
   515.nähe
   516.karte
   517.schließen
   518.sobald
   519.super
   520.irre
   521.muß
   522.schmerz
   523.außerdem
   524.beschützen
   525.besteht
   526.schloss
   527.interessant
   528.stopp
   529.klasse
   530.solange
   531.entfernt
   532.verändert
   533.erwischt
   534.jemals
   535.besonders
   536.eher
   537.küssen
   538.wenigstens
   539.wette
   540.absolut
   541.verlangt
   542.unmöglich
   543.nötig
   544.a
   545.traurig
   546.heraus
   547.mitnehmen
   548.sieben
   549.rennen
   550.hinten
   551.bieten
   552.dunkel
   553.fick
   554.besitz
   555.plötzlich
   556.schützen
   557.verheiratet
   558.wunderschön
   559.aufhalten
   560.frank
   561.verliebt
   562.tisch
   563.zählt
   564.schnappen
   565.griff
   566.riecht
   567.überlegen
   568.springen
   569.vorher
   570.gewissen
   571.erhalten
   572.beenden
   573.tatsächlich
   574.dienst
   575.treiben
   576.verfolgt
   577.blick
   578.feind
   579.schritt
   580.verraten
   581.überprüfen
   582.besonderes
   583.fort
   584.überrascht
   585.verhaftet
   586.erlaubt
   587.wütend
   588.zurückkommen
   589.spüren
   590.kochen
   591.packen
   592.wählen
   593.obwohl
   594.spur
   595.band
   596.angetan
   597.aufgeben
   598.behandelt
   599.dagegen
   600.gezwungen
   601.preis
   602.verpasst
   603.handeln
   604.dringend
   605.rum
   606.ständig
   607.rauchen
   608.rücken
   609.befehle
   610.überzeugt
   611.aufwachen
   612.leer
   613.atmen
   614.schwach
   615.unterwegs
   616.jagen
   617.aufgenommen
   618.zuhause
   619.landen
   620.schnitt
   621.ewig
   622.naja
   623.herum
   624.angenommen
   625.fremden
   626.geboren
   627.rüber
   628.müde
   629.irgendetwas
   630.gemeinsam
   631.sauber
   632.verwenden
   633.beschäftigt
   634.herkommen
   635.betrogen
   636.ermordet
   637.geschenkt
   638.manche
   639.aufgeregt
   640.lösen
   641.derjenige
   642.nutzen
   643.blau
   644.wirkt
   645.erwachsen
   646.beobachtet
   647.wozu
   648.bar
   649.feiern
   650.fisch
   651.verflucht
   652.fressen
   653.getrennt
   654.furchtbar
   655.leisten
   656.eingeladen
   657.ring
   658.kraft
   659.links
   660.frisch
   661.aufpassen
   662.wofür
   663.wild
   664.darin
   665.sonne
   666.dahin
   667.decke
   668.menschliche
   669.leck
   670.warm
   671.entspann
   672.dritte
   673.irgendwann
   674.ehe
   675.jedenfalls
   676.dick
   677.kaputt
   678.gefeuert
   679.hoffentlich
   680.tschüss
   681.sowieso
   682.liste
   683.wand
   684.leise
   685.unbedingt
   686.trauen
   687.zumindest
   688.runde
   689.bisher
   690.verbunden
   691.heil
   692.offensichtlich
   693.gewarnt
   694.neben
   695.ergibt
   696.gesund
   697.nick
   698.erwähnt
   699.sauer
   700.brennt
   701.nerven
   702.angekommen
   703.vergeben
   704.entdeckt
   705.mitgebracht
   706.übel
   707.unterschied
   708.unschuldig
   709.schlampe
   710.klingelt
   711.angestellt
   712.befindet
   713.lächeln
   714.betrunken
   715.rechts
   716.willen
   717.verdächtigen
   718.schuldig
   719.übrig
   720.fuß
   721.irgendwelche
   722.park
   723.erlebt
   724.vorbereitet
   725.ausgehen
   726.vermutlich
   727.erschießen
   728.diesmal
   729.ha
   730.verantwortlich
   731.stöhnt
   732.klopfen
   733.probieren
   734.grab
   735.erschossen
   736.geklaut
   737.klug
   738.unternehmen
   739.fantastisch
   740.witzig
   741.gegenüber
   742.schmeckt
   743.vergnügen
   744.verbrannt
   745.miteinander
   746.regen
   747.abholen
   748.abhauen
   749.grenze
   750.ran
   751.nämlich
   752.beten
   753.aufgetaucht
   754.fliehen
   755.grün
   756.übrigens
   757.bombe
   758.gründe
   759.loch
   760.quatsch
   761.verhalten
   762.nervös
   763.soweit
   764.indem
   765.eis
   766.unterschreiben
   767.erfolg
   768.aufstehen
   769.erscheinen
   770.bemerkt
   771.kapiert
   772.namens
   773.empfangen
   774.entweder
   775.heim
   776.geheim
   777.weder
   778.anziehen
   779.jawohl
   780.gast
   781.ungefähr
   782.hals
   783.entkommen
   784.zuvor
   785.bestellt
   786.geschossen
   787.verboten
   788.drinnen
   789.flucht
   790.behauptet
   791.mitkommen
   792.herein
   793.ernsthaft
   794.worauf
   795.ähnlich
   796.genießen
   797.aussage
   798.scherz
   799.beeindruckt
   800.befreien
   801.vertrag
   802.vögel
   803.ball
   804.schwanger
   805.wiederhole
   806.fern
   807.bestätigt
   808.kontrollieren
   809.teuer
   810.konzentrieren
   811.gilt
   812.benehmen
   813.akzeptieren
   814.leiten
   815.hingehen
   816.zurückkehren
   817.lächerlich
   818.vorne
   819.grüß
   820.heben
   821.sowas
   822.herzlichen
   823.streiten
   824.begriff
   825.neun
   826.begleiten
   827.anklage
   828.untersuchen
   829.reinkommen
   830.richten
   831.erschreckt
   832.reiten
   833.existiert
   834.verschiedene
   835.pro
   836.zufrieden
   837.hinterlassen
   838.rauskommen
   839.allerdings
   840.erfüllt
   841.unterhalten
   842.riesige
   843.enttäuscht
   844.statt
   845.sieg
   846.entführt
   847.starten
   848.worüber
   849.davor
   850.fernsehen
   851.englisch
   852.entwickelt
   853.nachts
   854.zuhören
   855.fett
   856.stich
   857.waschen
   858.berichten
   859.post
   860.berührt
   861.anbieten
   862.reparieren
   863.fein
   864.scharf
   865.amerikanische
   866.komplett
   867.schweigen
   868.sorry
   869.entlang
   870.einverstanden
   871.zufällig
   872.gesamte
   873.maul
   874.mitten
   875.irgendjemand
   876.vergehen
   877.ecke
   878.beschissen
   879.hexe
   880.reiß
   881.wundervoll
   882.stammt
   883.umgehen
   884.anhalten
   885.aha
   886.ruiniert
   887.schließlich
   888.zustand
   889.schlau
   890.merkwürdig
   891.vernichten
   892.betrifft
   893.verarschen
   894.übersetzt
   895.riskieren
   896.wahnsinnig
   897.beigebracht
   898.au
   899.besprechen
   900.blind
   901.form
   902.liefern
   903.unterstützen
   904.daher
   905.offenbar
   906.wechseln
   907.französisch
   908.linken
   909.nee
   910.vorwärts
   911.überlassen
   912.beantworten
   913.studiert
   914.berühmt
   915.hinaus
   916.albern
   917.freundlich
   918.reihe
   919.angeht
   920.einsam
   921.worum
   922.zulassen
   923.kehren
   924.pfeift
   925.mächtig
   926.ertragen
   927.fair
   928.langweilig
   929.verwandelt
   930.schwul
   931.hure
   932.schalten
   933.weich
   934.verhindern
   935.sammeln
   936.lehren
   937.gewöhnt
   938.informiert
   939.gestoßen
   940.vollkommen
   941.pause
   942.senden
   943.rauf
   944.begegnet
   945.berge
   946.klären
   947.dorthin
   948.sparen
   949.rührt
   950.anfassen
   951.vermute
   952.begangen
   953.jene
   954.wecken
   955.brav
   956.betrachten
   957.verlobt
   958.verwirrt
   959.kompliziert
   960.verteidigen
   961.aufmachen
   962.selten
   963.festhalten
   964.dankbar
   965.vorhin
   966.nackt
   967.urlaub
   968.lebendig
   969.wenden
   970.daraus
   971.reagiert
   972.reizend
   973.private
   974.presse
   975.stinkt
   976.offiziell
   977.streich
   978.erfunden
   979.einstellen
   980.taucht
   981.geil
   982.eng
   983.besiegen
   984.überfallen
   985.weitermachen
   986.braut
   987.seitdem
   988.normalerweise
   989.verurteilt
   990.schämen
   991.schieben
   992.billig
   993.mindestens
   994.prima
   995.räumen
   996.bellt
   997.mies
   998.drüber
   999.hässlich
  1000.stürzen
