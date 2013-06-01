myBumperCar
===========

<p>myBumperCar är ett multiplayer spel där varje spelare har varsin bil och syftet med spelet är att krocka med varandra.
Spelet finns även i en Single Player version för den som föredrar att spela ensam. Spelet har bakgrundsmusik som går
att stänga av om man så önskar.</p>
<hr />

<h3>Vad behövs för att köra spelet myBumperCar?</h2>

<p>Innan du installerar spelet så behöver du ha en server och node.js installerat på din dator.</p>

Har du ingen server så rekommenderar jag att du installerar <b>Wampserver</b> som du hittar om du trycker på länken nedan:</p>
<i><a href="http://www.wampserver.com/en/">WampServer</a><i>

<p><b>node.js</b> behövs då spelet använder sig av websockets. node.js hittar du om du trycker på länken nedan: </p>
<i><a href="http://www.nodejs.org/">node.js</a></i>

<hr />

<h3>Installation</h2>

<p>För att ladda hem spelet myBumperCar så kan du trycka på länken nedan: </p>
<i><a href="http://www.github.com/anactazia/myBumperCar/archive/master.zip">Ladda ner myBumperCar</a></i>

<p>När du hämtat myBumperCar så läggs en komprimerad mapp på din dator (oftast i mappen hämtade filer) 
som heter <b>myBumperCar-master</b>.</p>

<p>Extrahera mappen på din server </p>

<p><b>EXEMPEL:</b><br />
Om du har WampServer så extraherar du mappen under c:/wamp/www/</p>

<p>Gå till den extraherade mappen och byt namn på den så att den bara heter <b>myBumperCar</b>.</p>

<p>Starta sedan <b>kommandotolken</b></p> 

<p><b>EXEMPEL:</b><br />
Om du har Windows, tryck på startknappen och skriv <b>cmd</b> i sökrutan och tryck enter</p>

<p>När kommandotolken startas så pekar den oftast på användarkatalogen. <br />
För att gå till c:/ så skriver du <b>cd/..</b> och trycker därefter på enter.</p>

<p>För att välja en katalog skriver du <b>cd</b> och namnet på katalogen

<p><b>EXEMPEL:</b><br />
<code>cd wamp</code>

<p>Skriv nu in sökvägen till katalogen <b>js</b> som ligger under myBumperCar. 

<p><b>EXEMPEL:</b><br />
<code>cd wamp/www/myBumperCar/js</code>

<p>Tryck sedan på enter.</p>

<p>När du nu står i katalogen js så skriver du: <br />
<code>node server<br /></code>
Därefter trycker du på enter.</p>

<p>Längst ner kommer det fram en rad där det står ett datum och - Listening for connections on port 9001<br />
Du har nu startat din server och rutan med cmd måste hållas öppen så länge som du vill att spelet skall fungera, 
då servern stängs av om du stänger rutan.</p>

<p>Efter detta öppnar du din browser (spelet är utvecklat i <b>Firefox</b>, så den browsern är att föredra. 
<a href="http://www.mozilla.org/en-US/">Firefox Kan hämtas här</a>)</p>

<p>I adressfältet skriver du in sökvägen till filen bumperCarMultiplayer.php som ligger under mappen myBumperCar <br />

<p><b>EXEMPEL:</b><br />
<code>localhost/wamp/www/myBumperCar/bumperCarMultiPlayer.php</code></p>

<p>Du har nu startat spelet.</p>

<p>Om du istället vill spela ensam så kan du skriva in följande sökväg i browsern:<br />
<code>localhost/wamp/www/myBumperCar/bumperCarSinglePlayer.php</code></p>

<p><i<b>Mycket nöje med myBumperCar!</b></i></p>
