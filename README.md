# Avoimia suomenkielisiä NLP-tekstiaineistoja

English summary: A list of open Finnish NLP datasets

Avoimia suomenkielisiä tekstiaineistoja kieliteknologian menetelmien kehittämiseen ja testaamiseen. Sisältää myös Creative Commons non-commercial -lisensoituja (CC NC) aineistoja vaikka ne eivät oikeastaan olekaan [avoimia](https://opendefinition.org/).

## Tekstikokoelmia (self-supervised learning)

[Suomenkielinen Wikipedia 2017](http://urn.fi/urn:nbn:fi:lb-2019110803): Suomenkielisten Wikipedia-artikkelien tekstit 1.1.2018. Lauseet on morfosyntaktisesti jäsennetty käyttäen Turku BioNLP -ryhmän kehittämää dependenssijäsennintä. Lisenssi: CC BY 4.0

[Wikipedia-dumpit](https://dumps.wikimedia.org/backup-index.html): Wikipedian kaikki artikkelit Wiki markup -muodossa. Päivittyy kuukausittain. Lisenssi: CC-BY-SA, GNU Free Documentation License

[Common Crawl](https://commoncrawl.org/the-data/): Avoin, jatkuvasti päivittyvä hakurobotin keräämä koko julkisen webin sisältö. Suomenkieliset sivustot tunnistettu automaattisen kielentunnistuksen perusteella. [Käyttöehdot](https://commoncrawl.org/terms-of-use/)

[OSCAR](https://oscar-corpus.com/): Common Crawlin aineiston siivottu ja deduplikoitu versio. Lisenssi: CC0 ("no rights reserved")

[CC-100](http://data.statmt.org/cc-100/): Toinen Common Crawlista edelleenjalostettu aineisto, kielentunnistusta ja siivousta parannettu. Lisenssi: "No claims of intellectual property are made on the work of preparation of the corpus."

### Politiikkaan liittyviä tekstikokoelmia

[Eduskunnan avoin data](https://avoindata.eduskunta.fi/#/fi/home): Useita valtiopäiväasiakirjoja, esimerkiksi hallituksen esitykset, asiantuntijalausunnot, jne. Lisenssi: CC BY 4.0

[Ylen eduskuntavaalikoneiden vastaukset 2011](https://yle.fi/aihe/artikkeli/2011/05/16/vuoden-2011-vaalikonetiedot-nyt-avoimena-datana), [2015](https://yle.fi/uutiset/3-7869597) ja [2019](https://yle.fi/uutiset/3-10725384): Ehdokkaiden vastaukset Ylen eduskuntavaalikoneiden kysymyksiin ja avoimet tekstivastaukset. Lisenssi: CC BY NC 3.0

[Ylen kuntavaalikoneiden vastaukset 2012](https://yle.fi/uutiset/3-6331306), [2017](https://yle.fi/uutiset/3-9526290) ja [2021](https://github.com/raspi/scrapy-yle-kuntavaalit2021/releases): Ehdokkaiden vastaukset Ylen kuntavaalikoneiden kysymyksiin, vaalilupaukset ja avoimet tekstivastaukset. Lisenssi CC-BY-SA

### Kirja, elokuva ja muita mediasta syntyviä aineistoja

[Project Gutenberg](https://www.gutenberg.org/browse/languages/fi): Vanhoja kirjoja, joiden tekijänoikeudet ovat rauenneet. Lisenssi: Tyypillisesti public domain, tarkista jokaisen yksittäisen kirjan kohdalla

[Finnish OpenSubtitles 2017](http://urn.fi/urn:nbn:fi:lb-2019110802): Elokuvien tekstityksiä opensubtitles.org-sivustolta. Lauseet on morfosyntaktisesti jäsennetty käyttäen Turku BioNLP -ryhmän dependenssijäsennintä. Lisenssi CC BY

### Uutismedian tekstiaineistoja

[Vanhat aikakauslehdet](http://urn.fi/urn:nbn:fi:lb-2015051201): Kansalliskirjaston digitoimia vanhoja, ennen vuotta 1875 julkaistuja suomen- ja ruotsinkielisiä aikakauslehtiartikkeleita. Lisenssi: CC BY 4.0

[Iltapäivälehtien uutisotsikoita](https://github.com/nkrusch/fi-news-corpus): Iltapäivälehden verkkosivulla vuosien 2018-2020 välillä julkaistujen uutisten otsikot ja tiivistelmät. Lisenssi: MIT

[News Crawl](http://data.statmt.org/news-crawl/README): Uutisartikkeleista poimittuja lauseita (lauseiden järjestys sekoitettu) [suomeksi](http://data.statmt.org/news-crawl/fi/) ja noin 60 muulla kielellä vuosilta 2014-2020. Lisenssi: CC0

### Käyttäjien luomaa sisältöä 

[Ylilauta](http://urn.fi/urn:nbn:fi:lb-2016101210): Ylilauta-keskustelupalstan viestit vuosilta 2012-2014. Lisenssi: CC BY NC

[Reddit](https://files.pushshift.io/reddit/comments/): Reddit-keskustelualustan kaikki viestit vuoteen 2019 asti. Suomenkielistä keskustelua on esimerkiksi r/Suomi-keskustelualueella. Lisenssi: ?

## Annotoituja aineistoja (supervised learning)

[Universal dependencies Finnish TDT](https://github.com/UniversalDependencies/UD_Finnish-TDT/tree/master): Kieliopillisesti jäsennettyjä dokumentteja. Lisenssi: CC BY-SA 4.0

[Parallel Universal Dependencies (PUD) treebanks](https://github.com/UniversalDependencies/UD_Finnish-PUD/tree/master): 1000 kieliopillisesti jäsennettyä lausetta. Lisenssi: CC BY-SA 4.0

[Universal dependencies FinnTreeBank 1](https://github.com/UniversalDependencies/UD_Finnish-FTB/tree/master): Kieliopillisesti jäsennettyjä lauseita. Lisenssi: CC BY 4.0

[Eduskunta-vkk](https://github.com/aajanki/eduskunta-vkk): Lauseluokitteluaineisto. Perustuu ministerien vastauksiin kansanedustajien kirjallisiin kysymyksiin. Lisenssi: CC BY 4.0

[FiNER](https://github.com/mpsilfve/finer-data): Uutisartikkeleita, joihin on käsin merkitty entiteetit (named entity recognition, NER). Lisenssi: CC BY-ND-NC 1.0 (Digitoday-aineisto), CC BY-SA 3.0 (Wikipedia-aineisto)

[Opusparcus](http://urn.fi/urn:nbn:fi:lb-2018021221): Samaa tarkoittavien lauseiden (parafraasit) kokoelma. Suomeksi ja viidellä muulla kielellä. Lauseet ovat peräisin elokuvien ja TV-sarjojen tekstityksiä sisältävästä OpenSubtitles2016-kokoelmasta. Lisenssi: CC BY NC

[ScandiSent](https://github.com/timpal0l/ScandiSent): Sentimenttianalyysi. Asiakkaiden arvioita verkkokaupoista. Arviot on luokitelut kahteen ryhmään, positiivisiksi ja negatiivisiksi.

## Konekäännösaineistoja

[Paracrawl](https://www.paracrawl.eu/). Yli 7 miljoonaa lauseparia suomeksi ja englanniksi monikielisiltä webbi-sivustoilta. Lisenssi: CC0

[EuroParl](http://www.statmt.org/europarl/). Euroopan parlamentin kokousten puheita ammattikääntäjien suomeksi ja muille EU:n virallisille kielille kääntämänä. Lisenssi: "We are not aware of any copyright restrictions of the material. If you use this data in your research, please contact pkoehn@inf.ed.ac.uk."

[WMT en-fi testset 2016](https://github.com/Helsinki-NLP/WMT16-test-enfi/tree/v1.0) ja [2017](https://github.com/Helsinki-NLP/WMT17-test-enfi): 6000 lausetta (3000 kumpanakin vuonna). Ammattikääntäjien suomeksi ja englanniksi kääntämät. Lisenssi: CC BY 4.0

[WikiMatrix](https://github.com/facebookresearch/LASER/tree/master/tasks/WikiMatrix): Wikipediasta koneellisesti etsittyjä erikielisiä, mutta samaa tarkoittavia lauseita. 1620 kieliparia, mukaan lukien suomeksi. Lisenssi: CC BY-SA
