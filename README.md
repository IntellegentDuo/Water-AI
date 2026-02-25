# Water-AI
# [cite_start]🌊 Water-AI Security — Syrdarýa (Qyzylorda) MVP 5.1 [cite: 1, 5]

[cite_start]**AEROO SPACE AI COMPETITION байқауына арналған жоба** [cite: 3]
[cite_start]**Команда:** Intelligent Duo [cite: 3]

🔗 **[Презентация (Pitch-deck)](pitch_deck.pdf)**
🔗 **[Техникалық құжаттама](TECHNICAL_DOCUMENTATION.docx)**

---

## 🛰 Жоба туралы
[cite_start]**Water AI Syrdarya** — Сырдария өзені бойындағы су тапшылығы тәуекелін ерте анықтауға және суды тиімді басқаруға арналған Space + AI бағытындағы MVP платформа[cite: 6]. [cite_start]Жоба спутниктік деректер логикасын (NDWI/NDVI индекстері), тәуекел картасын және DSS (Decision Support System) ұсыныстарын біріктіріп, операторлар мен фермерлерге түсінікті веб-интерфейс арқылы нақты әрекет ұсынуды мақсат етеді[cite: 7].

### 🛠 Негізгі мүмкіндіктер (MVP)
* [cite_start]Сырдарияның нақты геометриясын OpenStreetMap (Overpass API) арқылы жүктеу[cite: 11].
* [cite_start]Өзен бойындағы операциялық аймақтарды (қызыл/сары/жасыл) тәуекел деңгейімен белгілеу[cite: 12].
* [cite_start]NDWI/NDVI индекстері, аномалия/утечка сигналдары, аймақ рейтингі[cite: 13].
* [cite_start]**DSS (Decision Support System):** әрекет ұсыну панелі[cite: 14].
* [cite_start]UI 3 тілде (KZ/RU/EN) [cite: 15] [cite_start]және MVP деңгейіндегі AI-ассистент режимі[cite: 16].

---

## 🏗 Технологиялық стек
* [cite_start]**Frontend:** HTML5 / CSS3 / Vanilla JavaScript (single-file MVP)[cite: 46].
* [cite_start]**Карта:** Leaflet 1.9.4 [cite: 47] [cite_start]және Turf.js гео-утилиталары[cite: 48].
* [cite_start]**Графиктер:** Chart.js (индекстер мен тренд графиктері үшін)[cite: 49].
* [cite_start]**Дерек көздері:** OpenStreetMap (Overpass API), Esri World Imagery[cite: 51, 52].

---

## 📂 Репозиторий құрылымы
Бұл репозиторийде келесі файлдар орналасқан:
* [cite_start]`index.html` — Басты веб-интерфейс (Dashboard)[cite: 137].
* [cite_start]`TECHNICAL_DOCUMENTATION.docx` — Техникалық құжаттама (MVP).
* [cite_start]`pitch_deck.pdf` — Инвесторлар мен қазылар алқасына арналған презентация[cite: 143].
* [cite_start]`syrdarya_2020.jpg.jpeg` — 2020 жылғы спутниктік сурет (салыстыру үшін)[cite: 139].
* [cite_start]`syrdarya_2025.jpg.jpg` — 2025 жылғы спутниктік сурет (салыстыру үшін)[cite: 140].

---

## 🚀 Іске қосу нұсқаулығы (Local Demo)
[cite_start]Бұл жоба локалды демо үшін жасалған, деплой міндетті емес[cite: 17].

**Ең оңай жолы:**
1. Жоба файлдарын компьютерге жүктеп алыңыз.
2. [cite_start]`index.html` файлын браузерде аш (Chrome/Edge)[cite: 130].

**Ұсынылатын әдіс (Локал сервер арқылы):**
[cite_start]Кейде браузер сыртқы fetch-ті шектеуі мүмкін[cite: 131]. [cite_start]Сондықтан Python арқылы қосуға болады[cite: 132]:
[cite_start]`python -m http.server 8000` [cite: 133]
[cite_start]Содан кейін браузерде `http://localhost:8000` сілтемесін ашыңыз[cite: 134].

---

## [cite_start]👥 Команда «Intelligent Duo» [cite: 3]
* [cite_start]**Бағдатқызы Жаннұр** — Капитан[cite: 4].
* [cite_start]**Нәби Жұлдыз** — Қатысушы[cite: 4].
