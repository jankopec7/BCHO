# BCHO — Wykorzystanie LLM do wykrywania phishingu

Ten projekt bada skuteczność dużych modeli językowych (LLM), takich jak GPT-4o, w detekcji i analizie wiadomości phishingowych w środowiskach chmurowych.

## 📁 Zawartość repozytorium

- `bcho_project_v3.ipynb` — główny notebook z kodem eksperymentalnym (klasyfikacja, analiza wyników, metryki)
- `curated_set.csv` — rzeczywisty zbiór wiadomości e-mail (phishing i ham) z repozytorium [sadat1971/Phishing_Email](https://github.com/sadat1971/Phishing_Email)
- `wiadomosci_200.txt` — syntetyczny zbiór testowy (100 phishing + 100 bezpiecznych)

## 🧪 Testowane modele

- GPT-3.5 Turbo (porównawczo)
- GPT-4o (główny model eksperymentu)

## 📊 Metryki

Na zbiorze rzeczywistym (`curated_set.csv`):
- Dokładność: **93.3%**
- Czułość: **98.2%**
- Precyzja: **89.4%**

## 🚀 Jak uruchomić

Możesz uruchomić kod:
- w Google Colab (zalecane — szybki start)
- lokalnie (Python 3.10+, `openai`, `pandas`, `sklearn`)

Pamiętaj o uzupełnieniu swojego **OpenAI API Key** przed testowaniem.

---

## 📄 Licencja

Projekt edukacyjny — użytek dozwolony w ramach pracy zaliczeniowej/projektowej. Źródła danych pochodzą z publicznie dostępnych repozytoriów.
