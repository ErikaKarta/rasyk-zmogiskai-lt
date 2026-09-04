# Rašyk žmogiškai LT Lite

Nemokamas lietuviškas įgūdis, padedantis pašalinti dažniausius DI teksto šablonus, perteklinį aiškinimą ir mechanišką ritmą, nepaverčiant teksto tyčinių klaidų rinkiniu.

Sukurta **Erikos Kartaševos**  
Instagram: [@erika.marketingas](https://www.instagram.com/erika.marketingas/)  
Telegram: [t.me/erikamarketingas](https://t.me/erikamarketingas)

## Ką daro „Lite“ versija

- rašo ir perrašo natūralia lietuvių kalba;
- šalina dažniausias generines DI formuluotes;
- tikrina pasikartojimus, abstrakcijas ir perteklinį aiškinimą;
- saugo faktus, citatas ir autoriaus mintį;
- gali atlikti trumpą teksto auditą.

Įgūdis nėra DI detektorius ir negarantuoja, kad tekstas bus klasifikuojamas kaip parašytas žmogaus.

## Pilna versija

Pilna versija papildomai gali turėti:

- individualų autoriaus balso profilį;
- atskirus „Reels“, karuselių, pardavimo ir naujienlaiškių režimus;
- išplėstinį faktų, citatų bei autorystės auditą;
- konkrečiam verslui pritaikytas leidžiamų ir draudžiamų formuluočių taisykles.

[Gauti informaciją apie pilną versiją](https://t.me/erikamarketingas)

## Naudojimas

Pavyzdinės užklausos:

- `Naudok Rašyk žmogiškai LT Lite ir perrašyk šį tekstą.`
- `Pašalink iš šio teksto DI braižą.`
- `Atlik auditą, bet teksto neperrašyk.`
- `Parašyk šį įrašą natūralia lietuvių kalba.`

## Įdiegimas kaip atskiras įgūdis

Atsisiųskite `rasyk-zmogiskai-lt-lite-skill.zip` ir importuokite jį per įgūdžių kūrimo arba diegimo funkciją palaikomame „ChatGPT“ ar „Codex“ paviršiuje.

## Įdiegimas kaip pluginas

Šiame projekte yra skills-only pluginas pagal oficialią „OpenAI“ struktūrą:

```text
.agents/plugins/marketplace.json
plugins/rasyk-zmogiskai-lt-lite/
├── .codex-plugin/plugin.json
└── skills/rasyk-zmogiskai-lt-lite/
```

Įkėlus šį projektą į „GitHub“, jo marketplace galima pridėti „Codex“ komanda:

```bash
codex plugin marketplace add SAVININKAS/rasyk-zmogiskai-lt
```

`SAVININKAS` pakeiskite „GitHub“ paskyros vardu. Tada pluginą pasirinkite iš pridėto marketplace „Plugins“ kataloge. Palaikomi diegimo būdai ir paviršiai gali keistis, todėl tikrinkite [oficialią „OpenAI“ pluginų dokumentaciją](https://developers.openai.com/plugins/build/plugins).

## Licencija

MIT. Galima naudoti, keisti ir platinti, išsaugant autorystės bei licencijos informaciją.
