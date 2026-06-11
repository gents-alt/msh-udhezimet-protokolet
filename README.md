# Udhërrëfyesit dhe Protokollet Klinike — Kërko & Filtro

Faqe statike (një skedar `index.html`) për të kërkuar dhe filtruar **Udhërrëfyesit dhe Protokollet Klinike** të publikuara nga Ministria e Shëndetësisë e Republikës së Kosovës.

🔗 Burimi i të dhënave: [msh.rks-gov.net/Documents/Index/273](https://msh.rks-gov.net/Documents/Index/273)

## Veçoritë

- **Kërkim dinamik realtime** — filtron ndërsa shkruan, me shumë fjalë, pa ndjeshmëri ndaj theksave (ë, ç), me theksim (highlight) të termit.
- **Tagje automatikë** — gjenerohen nga titulli (lloji: Udhërrëfyes / Protokoll / Udhëzues / Plan; tema: HIV, Diabet, COVID-19, Shëndeti Mendor, Obstetrikë, etj.).
- **Filtrime** — sipas llojit, temës (multi-select) dhe vitit (2018–2026), plus renditje.
- **Linqe direkte** — çdo kartë çon drejt e te dokumenti (PDF/DOCX) në serverin e MSH-së.
- **Punon offline** — të dhënat janë të ngulitura; nuk varet nga ndonjë API.

## Përdorimi

Hap `index.html` në çfarëdo shfletuesi. Nuk nevojitet server apo build.

## Përditësimi i të dhënave

Dokumentet janë në vargun `RAW` brenda `index.html` në formatin `[titulli, href, "dd.mm.yyyy"]`.
Tagjet llogariten automatikisht nga rregullat te `TOPIC_RULES`.

---

> Faqe jozyrtare. Të gjitha dokumentet i përkasin dhe hapen nga Ministria e Shëndetësisë e Kosovës.
