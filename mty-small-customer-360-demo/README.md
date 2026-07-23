# MTY Small Customer 360 Demo

Ensimmäinen V1-demo, jossa Excel-mockdata on muunnettu JSON-tiedostoiksi ja `index.html` hakee datan `data/`-kansiosta.

## GitHub-rakenne

Lataa tämän paketin sisältö uuteen kansioon esimerkiksi:

```text
mty-small-customer-360-demo/
├── index.html
└── data/
    ├── assets.json
    ├── orders.json
    ├── invoices.json
    ├── billing-accounts.json
    ├── requests.json
    ├── incidents.json
    ├── news.json
    ├── detail-actions.json
    └── companies.json
```

Kun kansio on GitHub Pages -repossa, demo avautuu polusta:

```text
/business-portal-demos/mty-small-customer-360-demo/
```

## V1-sisältö

- Asiakasvalinta
- KPI-kortit
- Assetit
- Tilaukset
- Laskut
- Palvelupyynnöt
- Vikailmoitukset
- Klikattava detail-paneeli
- Detail-toiminnot Excelin `detailpage`-välilehdeltä
