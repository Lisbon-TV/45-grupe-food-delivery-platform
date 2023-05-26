Projekto struktūra:


Bazinės struktūros responsive dizainas:

 - (1) desktop: šoninis menu, turinys, užsakymo suvestinė;

 - (1) mobile: šoninis menu, turinys;
siauriausias aktualus ekrano plotis yra 450px;


šoninis menu:

 - (2) dekstop: matosi ikona ir tekstas;

 - (1) mobile: matosi tik ikona;
 - (1) galimybė pasirinkti kuris menu punktas yra aktyvus, kuris puslapis atidarytas;


Filtras:

 - (2) dekstop/mobile: filtro pavadinimas ir 3 galimi jo pasirinkimai, iš kurių bet kuris vienas gali būti aktyvus;


Sąrašo įrankių juosta:

 - (1) desktop: elementų kiekis ir rikiavimas;

 - (1) mobile: elementų kiekis;


Maisto sąrašas:

 - (1) dekstop: turinys pateiktas keliais stulpeliais;

 - (1) mobile: turinys pateikstas 1 stulpeliu;

 - (1) "favorite" širdutė turi būti atvaizduota dviejose būsenose;

 - (1) maisto kortelių fono spalvų yra tik 9 galimi pasirinkimai;

 - (3) teisingas kortelės informacijos išdėstymas ir stilius;


"Load more":

 - (1) dekstop/mobile: atvaizduojamas maisto sąšaro atžvilgiu visada viduryje;


Vartotojo zona:

 - (1) desktop: rodomas gautų pranešimų elementas, vartotojo nuotrauka ir papildomas vartotojo zonos menu;

 - (1) mobile: nerodomas;

 - (1) gautų pranešimų elementas turi galėti rodyti būseną, jog yra naujų neperskaitytų pranešimų;

  - papildomas vartotojo zonos menu nėra interaktyvus ir neturi jokio turinio;


Užsakymo informacijos šoninis menu:

desktop:

 - (1) užsakovo detalės;

 - prekių krepšelio sąrašas:

 - (2) techniškai interaktyvių elementų nėra;

 - (1) drag&drop elementas;


Krepšelio suvestinė:

 - (2) "visa" logotipą susirasti patiems internete;

 - (1) mobile: nerodyti;


Projekto stilius:

 - (2) visos ikonos iš FontAwesome bibliotekos;

 - (2) spalvas naudoti per "CSS custom properties":

#44d187;
#ffd42e;
#d74369;
#fafafa;
#e5bde5;
#e5d4a7;
#93e5e5;
#a8e5e5;
#cae58f;
#c5d7e5;
#e5c1c1;
#e5e58b;
#e5bde5;

 - (1) naudoti tik pateikstas nuotraukas ("visa" kortelę susirandame ir apdorojame atskirai/patys);
 - (1) visų resursų keliai reliatyvūs;

 - (1) folder'ių ir failų pavadinimai galimi tik iš mažųjų angliškų raidžių, skaičių ir minuso ženklo;

 - (1) CSS turi turėti kelis komponentinius failus ir jie turi būti prijungti į pagrindinį CSS failą;

 - (3) semantiškai teisingai parinkti HTML tag'ai;

 - (3) naudojamas šriftas yra "Ubuntu"

 - (1) projekto "title" - Food delivery platform;

 - (2) favicon pagaminti iš šios nuotraukos: https://img.uxwing.com/wp-content/themes/uxwing/download/food-drinks-cooking/meal-food-icon.png;

 - (2) kodas tvarkingai suformatuotas ir nėra per daug nereikalingų tuščių eilučių;


Darbo eiga:

 - (1) projektas turi būti inicijuotas su NPM;

 - (1) naudoti "dead-server" paketą ir apsirašyti jo pasileidimo script'ą, kurio portas turi būti 42069;

 - (1) tinkamai užpildymas .gitignore failas;

 - (3) git istorijoja turi būti sudaryta iš ne mažiau 10 nuoseklių commit'ų su prasmingais pavadinimais;

 - (1) Github Pages nuoroda;

 - (2) Tvarkingas README failas, kuriame aprašyta:

        - įžanginis projekto aprašas ir jo pavadinimas;

        - Projekto tikslai;

        - aprašas, kaip pasileisti projektą pas save lokaliai;

        - projekto autorius

 - (5) naudoti git branch'us:

 - vienas master/main branch'as;

 - vienas branch'as skirtas "šoniniam menu";

 - vienas branch'as skirtas "pagrindiniam turiniui";

 - vienas branch'as skirtas "prekių krepšeliui";

 - feature/darbiniai branch'ai neturi būti ištrinti, net ir po darbų atlikimo;
