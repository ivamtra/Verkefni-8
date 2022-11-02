# Vefforritun 1, 2022: Verkefni 8, JS #2

[Kynning](https://youtu.be/iy_VF8uY62k).

## Markmið

* Skipta JavaScript forriti upp í einingar.
* Forrita á móti DOM.
* Útbúa forrit með stöðu sem uppfærir viðmót.

## Grunnur

Gefin er grunnur að verkefni:

* `package.json` með uppsetningu á `browser-sync` og _build_ skrefi.
* `index.html` með leiðbeiningum og tengingu við `main.js` sem einingu (_module_).
* Allir stílar í `styles.css`.
* `main.js`, `lib/ui.js` og `lib/helpers.js` með grunni að forriti, athugasemdir og tillögur að útfærslum eru í skjölunum.

Skjölun á föllum og breytum nota [`jsdoc`](https://jsdoc.app/).

Ekki er krafa að nota þennan grunn.

## Virkni

Áframhald af leiknum úr verkefni 7: leikur þar sem bolti er falinn undir bolla.

Byrjað er á að biðja notanda að velja hversu marga bolla eigi að fela undir, lágmark 2, hámark 10. Notandi setur inn gildi í form, ef það er ekki rétt gildi eru villuskilaboð birt fyrir neðan form.

Þegar notandi er búinn að velja hve marga bolla skal birta það marga bolla sem notandi getur síðan smellt á til að giska. Ef notandi valdi rétt skal gefa notanda `N-1` stig þar sem `N` er fjöldi bolla.

Sjá fyrirmynd í `v8-fyrirmynd.mp4`.

Vefur skal vera prófaður og virka í nýjustu útgáfum af Firefox og Chrome.

Setja þarf upp `browser-sync` eða einhvern annan vefþjón svo hægt sé að nota einingar.

## Netlify

Skila skal verkefninu keyrandi á Netlify. Útbúa þarf `build` script í `package.json` og setja upp build ferli þ.a. mappa sem verður til í `build` ferli sé notuð fyrir vef. Þetta verður til þess að þau gögn sem eru i möppu og eru ekki fyrir almenning (t.d. `package.json`) eru ekki birt, heldur aðeins:

* `index.html`.
* `styles.css`.
* `main.js` og `lib` möppu.

## Mat

* 10% Snyrtilegur JavaScript kóði.
* 10% Verkefni sett upp á Netlify og `build` scripta útfærð.
* 20% Tekið við inntaki notanda gegnum form og það staðfest skv. forskrift.
* 25% Bollar birtir í viðmóti eftir því hversu marga notandi valdi.
* 25% Hægt að velja bolla og birt hvort bolti sé þar undir eða tómt.
* 10% Stig og spilaðir leikir uppfærðir eftir hvert gisk.

## Sett fyrir

Verkefni sett fyrir mánudaginn 24. október 2021.

## Skil

Skila skal í Canvas, seinasta lagi fyrir lok dags þriðjudaginn 1. nóvember 2022.

Skilaboð skulu innihalda:

* slóð á verkefni keyrandi á Netlify
* slóð á **private** GitHub repo fyrir verkefni. Dæmatímakennurum skal hafa verið boðið í repo. Notendanöfn þeirra eru:
  * `MarzukIngi`
  * `Stimmikex`
  * `brynjar13`
  * `ofurtumi`
  * `BjarniHaskoli`
  * `Stulli888`

Athugið að setja [`node_modules`](https://github.com/vefforritun/vef1-2022/blob/main/namsefni/21.taeki-tol/1.npm.md#node_modules) í [`.gitignore` skrá](https://github.com/vefforritun/vef1-2022/blob/main/namsefni/03.git/1.git.md#gitignore) þar sem sú mappa getur orðið stór.

## Einkunn

Leyfilegt er að ræða, og vinna saman að verkefni en **skrifið ykkar eigin lausn**. Ef tvær eða fleiri lausnir eru mjög líkar þarf að færa rök fyrir því, annars munu allir hlutaðeigandi hugsanlega fá 0 fyrir verkefnið.

Sett verða fyrir tíu minni verkefni þar sem átta bestu gilda 5% hvert, samtals 40% af lokaeinkunn.

Sett verða fyrir tvö hópverkefni þar sem hvort um sig gildir 10%, samtals 20% af lokaeinkunn.

> Útgáfa 0.1
