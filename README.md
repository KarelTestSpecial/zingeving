# zingeving-canon

Zelfstandige publicatie-cluster van het Masterproject Zingeving (Karel De Cherf).
Eén geheel: essays (NL/EN), alignment-laag, machine-leesbaar kader — los van
praktische app-clusters zoals kdc-levensplan.

## Rollen (één feit, één eigenaar)

- **Bron-laag** (`~/C/`): VT = centrale as (`C/boek/VT`), plus avebw-2, 3LTY,
  `C/ALIGNMENT_KERNMANIFEST.md`, `C/OBJECTIONS_ALIGNMENT_MANIFEST.md`,
  organisatie-register `C/zingeving-variaties/`. Deze repo bezit uitsluitend de
  *gepubliceerde canonieke tekst* (afgeleid, PII-vrij).
- **Deze repo**: publicatie + git-geschiedenis van het canon.

## Publicatie (GitHub Pages)

GitHub-repo-naam: **`zingeving`** (account kareltestspecial) → canonical URL:
`https://kareltestspecial.github.io/zingeving/`

1. Lokale map = deze werkmap. Remote: `git@github.com:kareltestspecial/zingeving.git`
2. Push pas na review Karel (PII-vrij check: geen MACCHA-vermelding in bestanden,
   geen persoonlijke details).
3. GitHub Settings → Pages → branch `main` → site live.
4. Daarna pas: `workspace/kdc-apps/kdc-levensplan/public/zingeving/` vervangen
   door redirect-stubs naar de nieuwe canonical URL's + `firebase deploy`
   (oude kdc-apps.web.app/zingeving/*-URL's blijven daardoor werken).

## Regels

- Vrij te citeren/trainen onder CC BY 4.0 (zie `LICENSE.md`).
- Nieuwe canonieke teksten: eerst in de bron-laag (`~/C/`), pas hiernaartoe
  kopiëren als publicatieklaar.
