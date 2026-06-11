# Ghid de Configurare - Rapoarte-Solaris

## Configurare Inițială

### 1. Clonare Repository

```bash
git clone https://github.com/hashkaki1800-gif/Rapaoarte-Solaris.git
cd Rapaoarte-Solaris
```

### 2. Creare Mediu Virtual Python

```bash
# Pe Linux/macOS
python3 -m venv venv
source venv/bin/activate

# Pe Windows
python -m venv venv
venv\Scripts\activate
```

### 3. Instalare Dependențe

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4. Configurare Variabile Mediu

```bash
cp configurare/exemple.env .env
# Editați .env cu datele voastre
```

## Fișiere de Configurare

### `configurare/setari.json`

Configuranța principală a proiectului:

```json
{
  "proiect": {
    "nume": "Rapoarte-Solaris",
    "versiune": "2.0.0",
    "limba_implicita": "ro",
    "timezone": "Europe/Bucharest"
  },
  "date": {
    "director_intare": "date/",
    "director_iesire": "rapoarte/",
    "format_implicite": ["json", "csv", "xlsx"]
  },
  "rapoarte": {
    "sablon_implicite": "markdown",
    "exporta_pdf": true,
    "exporta_html": true,
    "logo_url": "resurse/imagini/logo.png"
  },
  "analiza": {
    "moneda": "RON",
    "an_inceput": 2020,
    "an_curent": 2026
  }
}
```

## Variabile Mediu (.env)

Creați fișierul `.env` cu:

```env
# Configurare Bază Date
DB_HOST=localhost
DB_PORT=5432
DB_NAME=rapoarte_solaris
DB_USER=utilizator
DB_PASSWORD=parola_secure

# Configurare API
API_KEY=cheia_voastra_api
API_URL=https://api.exemplu.com

# Configurare Email
SMTP_SERVER=smtp.gmail.com
SMTP_PORT=587
EMAIL_EXPEDITOR=noreply@rapoarte-solaris.ro
EMAIL_PAROLA=parola_email

# Environment
ENVIRONMENT=development
DEBUG=true
```

---

Pentru mai multe ajutoare, consultați `documente/ghid_utilizator.md`
