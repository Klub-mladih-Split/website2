---
title: Klub ima novu internet stranicu!
date: 2019-05-12T06:14:34.000+00:00
image: images/blog/post-2/web-screenshot-hero.png
description: This is meta description.

---
*Napisao: Tomislav Mamić"

## Odabir tehnologije i načina izrade
Nova web stranica Kluba mladih Split nastala je za vrijeme Hack4Split 2020. hackathona. Kako bi smanjili troškove, odabrali smo Jamstack kao tehnologiju koja omogućava besplatnu izradu, veoma brzih web stranica, za koje nije potreban klasičan server. Kako smo server za staru stranicu plaćali oko 30$ mjesečno, ovime smo postigli značajnu uštedu za Klub. Nova web stranica je i brža od prethodne.

Kako nismo imali resurse za izradu potpuno nove prilagođene web stranice, odlučili smo koristiti postojeću temu. Jamstack je relativno mlada tehnologija, i nema ni približno puno besplatnih templatea kao Wordpress, no ipak ih je bilo iznimno puno. Zato nam je trebalo vremena dok nismo pronašli i odabrali odgovarajući template.

## Definiranje strukture, sadržaja i izgleda
Najvažnija je bila podrška za različiti sadržaj kojeg smo htjeli imati na našem web-u. Kroz grupni brainstorming smo najprije u (Google dokumentu)[https://docs.google.com/document/d/1y5BqacoXPIAIJGHDZjicO20qlNmiojxtsRb_AIGpgAY/edit?usp=sharing] definirali što treba sadržavati naša web stranica. Inače smo za početak koristili Google Drive za pohranu svih sadržaja (slike, tekstovi, linkovi, dokumenti) koje smo htjeli postaviti na web. Zatim smo potražili temu koja, osim što podržava sve oblike sadržaja, nam odgovara i izgledom.

Za izgled je najbitnije bilo da ne odvraća pozornost sa sadržaja, a dodatna prednost je bila ako bojama i oblicima daje do znanja da se radi o online mjestu udruge mladih. Izbor je na kraju pao na temu (Kross Hugo)[https://themes.gohugo.io/kross-hugo-portfolio-template/] koja je zahtjevala minimalne preinake.

## Postavljanje
Kod Jamstacka, programski kod obično stoji na (Githubu)[https://github.com]. Tako je bilo i u našem slučaju. Napravii smo (Klub mladih Split račun)[https://github.com/Klub-mladih-Split] na Githubu. Na tom računu u budućnosti planiramo dodati i druge online sadržaje Kluba, kao što je forum i dr. Za sada smo samo klonirali temu u (novi repositorij)[https://github.com/Klub-mladih-Split/website2/]. Taj repositorij je mjesto gdje se sada nalazi naša web stranica.

Odmah smo odabrali Hugo site builder. Riječ je o besplatnom alatu koju pretvara kod stranice iz repozitorija u web stranicu kojoj onda pristupaju naši korisnici. Osim toga, za lako uređivanje, postavili smo Content Management Sustav Forestry. Tako da se web stranica može uređivati jednako lako kao i Wordpress stranica.

Osim ovoga, da bi web stranica koju izgradi Hugo bila dostupna na našoj domeni klubmladihsplit.hr, spojili smo Netlify. Netlify omogućava besplatno serviranje Jamstack web stranice na vlastitoj domeni. Potrebno je samo promijeniti DNS zapise tako da Netlify dobije pristup našoj domeni.

## Uređivanje
Kross Hugo tema posjeduje dosta elemenata koji nam u ovoj fazi nisu bili potrebni. Srećom, lako ih je samo onemogućit, bez brisanja. Na taj način je u budućnosti moguće ubaciti još efektnih vizualnih poruka i informacija.

Kod prvog uređivanja, sadržaj smo u najvećoj mjeri promijenili korištenjem Visual Studio Code alata. Kasnije, tehnički manje iskusni članovi će uređivati web stranicu putem Forestry sučelja. Inače, sve promjene na web stranici su vidljive na (*commits* stranici Github repositorija)[https://github.com/Klub-mladih-Split/website2/commits].