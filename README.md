# skolschema

course *eller* subject används i Activity. Course för gymnasiet och annan verksamhet baserat på kurser (exempelvis komvux). Subject syftar på grundskoleämnen (är ju redundant för gymnasiet)

*Frågor:*

hostas schemat någonstans? URI / URL?

om "start" = "", är det invalid data eller?

Finns det en tjänst för att validera? Eric W?

comment på calendarevent, finns bättre namn? vad används den till?

Vi tycker exceptions är för komplicerade. Även om det kan beskrivas i källan, behöver det verkligen kommuniceras? En enklare variant vore att inte ha tid eller length, undantag betyder bara att "objektet" *inte* deltar? Resten borde handla om frånvaro snarare än schema? Om en elev ska gå litet tidigare på måndagar, skrivs det verkligen i schemat? Har vi nytta av detta?

Varför finns teachingLength för Group och Teacher men inte för elever?

Behövs flera parentactivity? Vi tycker inte det. NO-exemplet?

Courses och subjects på grupper. Kan det vara flera? Kan det vara både och?

activity.type sätter egentligen lärarens roll. behövs flera lärarroller i samma activity?

datumintervall som gått ur tiden ska väl inte behöva kommuniceras i evighet? Men hur får man då fram historisk data? Var går gränsen, eller hur avgränsar man?

Tjänstgöringsgrad - årsarbetstid är kanske bättre?

Var är man anställd? Skola? Kommun? Skolenhet? "Skola + skolform"?

Många frågor kring anställning. Olika antal timmar över tid?

Lärare hör inte till skolenhet, utan normalt sett till skola+skolform. I LifeCare kan man välja att koppla anställningen till en Skola eller till kommunen.

Skolenhet kopplar *bara* ihop elever och rektor.

Kommun
 Förvaltning
        anställning musik
  Skola 1
  Skola 2
     Skola 1 Sär
        anställning asdfsadf

Lärarroll på grupp? Klasslärare? 


för grupper med olika typer, hur spärrar vi  olika typers attribut?

Employeegroup, oklart, ska den verkligen gruppera anställningar? Onödigt komplicerat och oklart syfte?

Course och subject ska väl också ha UUID om det är egna objekt och kan ha olika värdeförråd i skolformer, vissa helt fria.

behöver vi ha historik på årskurs?

Skolenhet / Skola på anställning, funkar det med ref till grupp?

Grupper kan väl inte ha skolform, bara elever?

Behövs flera responsible (ändring över tid?) för klasser?

Behövs flera kurskoder för en grupp?

Enklare att ha gruppmodell för skolor och skolenheter. Ibland kan skolan innehålla flera skolenheter, en det omvända borde kunna finnas, att flera skolor bildar en skolenhet.

Skolenhet, municipality code, gäller det även friskolor?
Skolenhet: vad är "ownerType"?