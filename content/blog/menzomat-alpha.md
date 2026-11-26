+++
title = 'Pomozi mi da telefonom proveravamo kartice za menzu!'
date = 2026-11-26T21:00:00+01:00
draft = false
description = 'Znaš onaj momenat kad čekaš 5 minuta ispred automata u menzi samo da proveriš da li imaš uplaćen ručak? Šta ako ti kažem da postoji lakši način?'
tags = ['menzomat', 'testing', 'announcement']
[cover]
image = '/menzomat/banner.png'
alt = 'Menzomat app'
hiddenInSingle = true
+++

Već neko vreme radim na Menzomatu, aplikaciji pomoću koje telefonom možeš da pročitaš karticu za menzu i vidiš uplaćene obroke, stanje novca i ostale podatke koji se na njoj nalaze. Za sada aplikacija radi samo na Androidu, ali planiram u budućnosti napraviti i iOS verziju. 

{{< figure src="/menzomat/screenshot-alpha.png" alt="Očitana kartica u menzomatu" width="300" align="center" >}}

Kartica se može čitati bez ključa, ali sam morao mesec dana skenirati, analizirati i zaključivati šta koji bajt na njoj predstavlja, jer sadržaj kartice niko nije dokumentovao.

Većinu stvari sam uspeo da odgonetnem, ali ostalo je još par stvari koje treba proveriti:

- Fakulteti su na kartici obeleženi brojevima, počevši od 1. Za sada znam brojeve za FTN, PMF, Filozofski i Poljoprivredni, a za ostale treba otkriti koji broj im pripada.
- Aplikacija je za sada testirana samo na novosadskim karticama. Kartice iz drugih gradova bi trebalo da rade na isti način, ali to tek treba proveriti.
- Da bi aplikacija izašla na Google Play, Google traži najmanje 12 testera koji su u testu 14 dana zaredom.

### Kako možeš pomoći

Pre svega, ako ti ovo deluje kul, preuzmi aplikaciju i isprobaj. Svaki tester mi znači :)

Ako si sa nekog od fakulteta koji nisam još uvek odgonetnuo (npr. piše ti Fakultet 7), javi mi na [contact@misa.st](mailto:contact@misa.st) koji si fakultet i koji broj ti piše, kako bismo odgonetnuli sve fakultete!

Ako si na nekom drugom univerzitetu, tvoja pomoć mi naročito znači. Prisloni karticu, pa mi preko prijave bagova u podešavanjima pošalji šta je aplikacija pročitala, da vidim kako su podaci zapisani na tvojoj kartici. Cilj mi je napraviti aplikaciju koja radi u celoj Srbiji, ne samo u Novom Sadu.

Svakako, ako naletiš na neki bag, iskoristi opciju za prijavljivanje bagova u podešavanjima kako bi aplikacija na kraju radila perfektno!

### Okej, ali kako da skinem ovo čudo?

Google je maaalo zakomplikovao ovaj proces, tako da treba da odradiš ova 3 koraka:

1. Učlani se u [Google grupu](https://groups.google.com/g/menzomat) klikom na „Pridruži se grupi“.
2. Prihvati [poziv za testiranje](https://play.google.com/apps/testing/st.misa.menzomat).
3. Posle par minuta možeš da [preuzmeš Menzomat sa Google Play-a](https://play.google.com/store/apps/details?id=st.misa.menzomat).

Za sva tri koraka koristi isti Google nalog koji ti je na telefonu. Treba ti Android telefon sa NFC-om. I molim te, ne briši aplikaciju bar 14 dana, inače se nećeš računati u tih 12 testera.

### Šta je sa mojim podacima?

Aplikacija nema pristup internetu, tako da sve što pročita sa kartice ostaje na tvom telefonu. Jedini izuzetak je prijava bagova: ona otvara mejl sa podacima sa kartice u prilogu, uključujući ime i JMBG, i ništa se ne šalje dok mi ti ne pošalješ mejl. Te podatke koristim samo da popravim bag ili dodam tvoj fakultet i brišem ih čim završim. Celu politiku privatnosti možeš da pročitaš [ovde](https://github.com/MikMik1011/menzomat/blob/main/docs/privacy-policy.md).

### Za kraj

Menzomat je besplatan i otvorenog koda, pa ako te zanima kako radi, kod je na [GitHub-u](https://github.com/MikMik1011/menzomat). Ako znaš nekog ko svaki dan čeka ispred automata, slobodno mu pošalji ovaj post!

Kad aplikacija izađe, pisaću detaljnije o tome kako sam odgonetnuo karticu. Ako ne želiš to da propustiš, blog ima [RSS](/blog/index.xml).

Vidimo se u menzi :D