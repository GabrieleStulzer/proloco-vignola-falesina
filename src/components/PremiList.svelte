<script>
    let premi = [
        {id: "1", biglietto: "2803", descrizione:	"Buono spesa SAIT valore 800 euro offerto da Trentino Lavori, Moltrer Scavi, Costem e Famiglia Cooperativa Perginese"},
        {id: "2", biglietto: "5484", descrizione:	"30 quintali di legna offerti da Diego Oss Pegorar lavorazioni boschive"},
        {id: "3", biglietto: "1242", descrizione:	"Buono per 2 persone mezza pensione + trattamento wellness offerto da Garni & Wellness Anderle"},
        {id: "4", biglietto: "0454", descrizione:	"Buono carburante valore 300 euro offerto da Lenzi Trattori "},
        {id: "5", biglietto: "5569", descrizione:	"Tosasiepe Sthil offerta da Giongo Eligio"},
        {id: "6", biglietto: "7050", descrizione:	"Buono carburante valore 200 euro offerto da Planchel Autonoleggio"},
        {id: "7", biglietto: "2930", descrizione:	"Buono carburante valore 200 euro offerto da Gandini Luigi Edilizia"},
        {id: "8", biglietto: "3558", descrizione:	"Buono spesa SAIT valore 150 euro offerto da Zampedri Lorenzo Scavi"},
        {id: "9", biglietto: "1876", descrizione:	"Cena per 4 persone offerta da Hotel Compet"},
        {id: "10", biglietto: "0299", descrizione:	"Due piumini anallergenici offerti da Bioflex Materassi"},
        {id: "11", biglietto: "3515", descrizione:	"Kit elettroutensile spazzolatrice offerto da Fratelli Lasta"},
        {id: "12", biglietto: "7270", descrizione:	"Buono Carburante valore 100 euro offerto da Paolo Gadler Lavorazioni Boschive"},
        {id: "13", biglietto: "1747", descrizione:	"Buono spesa SAIT valore 100 euro offerto da Pegoretti Legnami s.r.l."},
        {id: "14", biglietto: "2340", descrizione:	"Buono Carburante valore 100 euro offerto da Vasil Pitture"},
        {id: "15", biglietto: "7017", descrizione:	"Buono Spesa Punto Verde Xausa valore 100 euro offerto da Lavorazioni Boschive Pallaoro Matteo"},
        {id: "16", biglietto: "3137", descrizione:	"Buono Spesa Giongo Eligio valore 100 euro offerto da Angeli Mattia Lavorazioni Forestali - Scavi - Lavori Edili"},
        {id: "17", biglietto: "2222", descrizione:	"Buono spesa SAIT valore 100 euro offerto da Anderle Michele Scavi e Movimento Terra"},
        {id: "18", biglietto: "0415", descrizione:	"Buono Spesa Punto Verde Xausa valore 100 euro offerto da Fedrizzi Claudio Taglio e Esbosco Legname"},
        {id: "19", biglietto: "6689", descrizione:	"Buono Carburante valore 100 euro offerto da Stefano Baitella Bs impianti elettrici"},
        {id: "20", biglietto: "3269", descrizione:	"Buono 5 pizze + bibite offerto da Pizzeria Baitella"},
        {id: "21", biglietto: "1971", descrizione:	"Valigetta Porta Utensili offerta da Frisanco Ferramenta"},
        {id: "22", biglietto: "5805", descrizione:	"Catene da Neve offerte da Pneus Pergine"},
        {id: "23", biglietto: "0939", descrizione:	"Buono 2 pizze + bevande + cartone vino offerto da Hotel Turismo"},
        {id: "24", biglietto: "5723", descrizione:	"100 cialde caffe offerte da Perzen Vending"},
        {id: "25", biglietto: "3411", descrizione:	"Cena per due persone offerta da Stube Valzurg"},
        {id: "26", biglietto: "5454", descrizione:	"Supporto per vaso di Fiori offerto da Punto Verde Xausa"},
        {id: "27", biglietto: "3948", descrizione:	"2 buoni da 25 euro offerti da Fabbrica Pedavena Levico"},
        {id: "28", biglietto: "7959", descrizione:	"Buono 50 euro offerto da Bocciodromo Pergine"},
        {id: "29", biglietto: "2243", descrizione:	"Cesto prodotti offerto da Fiordimugo"},
        {id: "30", biglietto: "2929", descrizione:	"Buono 30 euro offerto da Macelleria Zanotelli"},
    ];

</script>

<div>
    {#each premi as p}
    <div class="mb-4">
        <h3 class="text-lg">{p.id} - {p.descrizione}</h3>
        <p>Numero Estratto: <span class="font-bold">{p.biglietto}</span> </p> 
    </div>
    {/each}
</div>