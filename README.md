# examen-bootcamp

En guide för hur man kommer åt hemsidan från github till vscode (hos mig).

Jag har inte lyckats skapa en bro mellan github och min vscode, så för att få tittat på hemsidan behöver man(jag) länken till githubrepot först, om man är inne på github klickar man på den gröna knappen där det står ” <> code”, sedan kopiera länken. Alternativt kan man ta adressen från browsern.
Starta sedan vscode
Sen väljer man ”explorer” på vänstersidan - nästan uppe i hörnet i vscode. Det ser ut som två ark halvt över varandra. (Ctrl + Shift + E)
Därefter trycker man på ”clone repository”, då kommer det upp en ”clone from github” i sökrutan upp i mitten av skärmen, så kan man lägga in länken från github. Då borde det poppa upp ett alternativ man kan klicka på - det repo man har sökt fram. 
Så behöver man välja en mapp på sin dator där vi kan lägga repot.
Då laddas det in och kommer upp en ruta där man kan trycka ”add to workspace.” (gör det)
Sen hittar man index.html och högerklickar på den. Nästa val är ”Open with live server” – då poppar det upp i browser och man är i gång. Väl inne på index.html kan man fortsätta som en vanlig hemsidan man söker upp på nätet.


1 HTML-struktur
Jag har semantiska HTML-element med navigationsmeny och den finns på alla sidor.
skulle kunnat ta bort nav på förstasidan då hela sidan är som en nav vidare, men enligt uppgiften får den vara kvar.

2/3 CSS-styling och responsiv design
Jag har flex – row i min nav, och flex – column i mina bilder. (Plus en bonus som var nödvändig för att bilder inte skulle ha två kolumner på lite skärm)
Det är grid som skapar responsivitet på sidorna annars. En med areas och en utan.
Försöker vara så tydlig som möjligt med mina CSS-selektorer så det inte blir en plötsligt krock
Jag gjorde först responsive text med font-size på html och rem som enheter, men det krockade med kravet på clamp, så fick ta bort det till slut, och min header har clamp. Hade en på knapparna som jag trodde funkade, men det var font-size på html som styrde den.

4 Tillgänglighet
Det finns alt-attribut på alla bilder förutom gifen i footer.
Har endast h1-h3, men det är rätt struktur
Fick av lighthouse 100 på allt för min desktop, endast 95 för mobil.
Alla länkar och knappar har aria-label

5 webbläsarverktyg
Det är för snabbt fram och tillbaka för att säga exakt vad man har löst med detta, men det brukar var storlekar, position, och framför allt responsivitet. 
Kollar över vad som är överflödigt genom att klicka bort, samma som när man kommenterar bort beroende på var man har fokus just då. Har två skärmar, så båda alternativen funkar.
Fick ändra hover och currentpage färg på bildsidan då den blåa färgen inte hade bra kontrast till den gula. Det blev svart i stället.

6 Git
Gjorde två brancher med en gång, vilket uppenbarligen var lite för tidigt. När jag kopplade github-repot till datorn skapades ett nytt repo - en mapp i mappen. Så kodade väldigt länge i endast main.
Gjorde på slutet fler brancher så jag inte skulle få fler krockar än jag redan haft på vägen.
Gjorde merge mellan bild och main först, sen gjorde jag samma sak med hem och main för att få med hela. Inga konflikter.
Skulle så jättegärna önskat att jag var lite duktigare att använda commit efter lyckade ändringar i css. 

