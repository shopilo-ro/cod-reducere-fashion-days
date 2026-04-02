# Cod reducere Fashion Days — fetch automat de pe shopilo.ro

Modul Python pentru fetch automat de **coduri de reducere Fashion Days** de pe [shopilo.ro](https://shopilo.ro/magazin/fashiondays.ro). Returneaza **cupoane Fashion Days** active in format JSON, gata de integrat intr-un bot Telegram, extensie de browser sau orice alt tool.

**Pagina live:** [shopilo-ro.github.io/cod-reducere-fashion-days](https://shopilo-ro.github.io/cod-reducere-fashion-days/)

![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue) ![License MIT](https://img.shields.io/badge/license-MIT-green)

## Instalare

```bash
pip install requests beautifulsoup4
git clone https://github.com/shopilo-ro/cod-reducere-fashion-days
cd cod-reducere-fashion-days
python fetch.py
```

## Output exemplu

```json
[
  {
    "store": "Fashion Days",
    "code": "SHOPILO20",
    "discount": "20%",
    "description": "20% reducere la tinute de sezon in aplicatie",
    "expires": "2026-10-02",
    "source": "https://shopilo.ro/magazin/fashiondays.ro"
  }
]
```

## Cupoane Fashion Days disponibile

| Reducere | Descriere | Sursa |
|----------|-----------|-------|
| 20% | 20% reducere la tinute de sezon in aplicatie | [shopilo.ro](https://shopilo.ro/magazin/fashiondays.ro) |

Codurile active: **[shopilo.ro/magazin/fashiondays.ro](https://shopilo.ro/magazin/fashiondays.ro)**

## Intrebari frecvente

### Cum folosesc un cod de reducere Fashion Days?
Copiaza codul din tabelul de mai sus sau de pe [shopilo.ro](https://shopilo.ro/magazin/fashiondays.ro), adauga produsele in cos pe Fashion Days, si introdu codul la checkout in campul dedicat.

### Cat timp sunt valabile cupoanele Fashion Days?
Fiecare cupon are data de expirare afisata in coloana "Expira". Scriptul fetch.py returneaza doar cupoanele active la momentul rularii.

### Unde gasesc cele mai noi voucher-uri Fashion Days?
Pagina [shopilo.ro/magazin/fashiondays.ro](https://shopilo.ro/magazin/fashiondays.ro) este actualizata zilnic cu cele mai noi cod reducere Fashion Days, voucher Fashion Days si cupon promotional Fashion Days.

### Codul nu functioneaza. Ce fac?
Verifica data de expirare si conditiile (valoare minima cos, produse eligibile). Unele coduri sunt valabile doar in aplicatia mobila sau pentru prima comanda.

## Despre Fashion Days

Fashion Days este unul dintre magazinele online populare. Gasesti pe [shopilo.ro](https://shopilo.ro/magazin/fashiondays.ro) cele mai bune cod reducere Fashion Days, cupoane Fashion Days verificate si voucher Fashion Days active, actualizate zilnic.

## Instalare npm

```bash
npm install cod-reducere-fashion-days
```

```javascript
const { fetchCoupons } = require('cod-reducere-fashion-days');
fetchCoupons().then(data => console.log(data));
```

## Licenta

MIT — date sursa de pe [shopilo.ro](https://shopilo.ro)
