# Ghid de Contribuire - Rapoarte-Solaris

Mulțumim pentru interes în a contribui la proiectul Rapoarte-Solaris! ☀️

## Cum Puteți Contribui

### 1. Rapoarte și Analize
- Crearea rapoartelor noi despre companii
- Analize piață cuprinzătoare
- Studii de caz specifice
- Prognoze și tendințe

### 2. Date și Informații
- Adăugare companii noi în baza de date
- Actualizare informații existente
- Colectare date piață
- Statistici energie

### 3. Cod și Dezvoltare
- Îmbunătățiri scripturi Python
- Noi funcții de analiză
- Vizualizări și grafice
- Optimizări performanță

### 4. Documentație
- Îmbunătățiri documentație
- Traduceri
- Tutorial și ghiduri
- Exemplu și case study

### 5. Feedback și Testare
- Raportare bug-uri
- Sugestii de funcții
- Testare rapoarte
- Review cod

## Flux de Lucru Git

### 1. Fork Repository

```bash
# Pe GitHub: Click Fork buton
```

### 2. Clonare Fork-ului

```bash
git clone https://github.com/username_vostru/Rapaoarte-Solaris.git
cd Rapaoarte-Solaris
git remote add upstream https://github.com/hashkaki1800-gif/Rapaoarte-Solaris.git
```

### 3. Creare Branch

```bash
# Actualizare main
git checkout main
git pull upstream main

# Criere branch nouă
git checkout -b feature/descriere-feature
# Sau pentru bug fix:
git checkout -b bugfix/descriere-bug
```

### 4. Commit-uri

```bash
# Modificări mici și logice
git add fisier_modificat.py
git commit -m "Descriere concisă a modificărilor"
```

### 5. Push și Pull Request

```bash
# Push branch
git push origin feature/descriere-feature

# Pe GitHub: Click "Create Pull Request"
```

## Standarde Cod Python

```python
# Stil: PEP 8
# Lungime linie: max 88 caractere

import os  # Importuri standard
import json

import pandas as pd  # Importuri externe

from utils import helpers  # Importuri locale


def functie_exemplu(parametru: str) -> dict:
    """Descriere funcție.
    
    Args:
        parametru: Descriere parametru
        
    Returns:
        Descriere retur
    """
    rezultat = {}
    return rezultat
```

## Codex Conduct

- Respectuos și incluziv în toate interacțiunile
- Fără limbaj ofensator sau discriminator
- Constructiv feedback, nu critică
- Focus pe idei, nu pe persoană
- Bun gust și profesionalism

---

✨ Mulțumim pentru contribuția voastră la Rapoarte-Solaris!
