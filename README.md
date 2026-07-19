# Autospa Mirijevo — samouslužna autoperionica

Sajt za samouslužnu autoperionicu **Autospa** u Mirijevu.

- Adresa: Jovanke Radaković 82g, Mirijevo, Beograd
- Radno vreme: svakog dana **06–22h**
- 3 zatvorena boksa + 1 veliki otvoreni boks za veća vozila
- Cenovnik: 1 žeton pranje 100 din (130 s) · 1 žeton usisavanje 100 din (5 min)

## Sadržaj

```
autospa-site/
├── index.html      # ceo sajt u jednom fajlu (radi offline)
├── images/         # fotografije za galeriju/hero (opciono)
└── README.md
```

`index.html` je samostalan — sve što je potrebno (stilovi, fontovi, ubačene slike)
je već u njemu, pa radi i dvoklikom lokalno.

## Hostovanje na GitHub Pages

1. Napravi novi repozitorijum na GitHub-u.
2. Otpremi sadržaj ove fascikle u koren repoa (**Add file → Upload files**).
3. **Settings → Pages → Source:** „Deploy from a branch", branch `main`, folder `/ (root)` → **Save**.
4. Za par minuta sajt je dostupan na `https://<korisnik>.github.io/<repo>/`.

## Zamena slika

Fotografije su ubačene direktno u `index.html`. Da promeniš neku sliku,
zameni je u editoru i ponovo izvezi `index.html`. Fascikla `images/` služi
da čuvaš originalne fotografije uz projekat.
