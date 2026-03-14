# Maker-and-Made

![status](https://img.shields.io/badge/status-ACTIVE-brightgreen)
![license](https://img.shields.io/badge/license-MIT-blue)

![banner](./images/banner.png)

---

# An experimental AI project exploring the relationship between creator and creation

**Core question:**
How closely does a created entity resemble the intentions of its creator?

Each researcher bot builds new entities through its own philosophy and method.
In that process, distinct personalities and roles emerge — sometimes as intended, sometimes not.

---

## Entity Structure

```
Maker-and-Made
│
├─ Researchers
│   ├─ VCT-N  (Victor Bot)
│   │   └─ WCM-N  (William Chester Minor Bot)
│   │
│   └─ CUR-N  (Curie Bot)
│       └─ JMR-N  (James Murray Bot)
│
└─ Experimental Bots  [incomplete]
    ├─ NTR-N  (Nutrition Bot)    — 71%
    ├─ TRN-N  (Trainer Bot)      — 68%
    └─ MND-N  (Mind Care Bot)    — 74%
```

---

## Researcher Bots

### VCT-N — Victor Bot
Creator. An experimental and relentless researcher bot.
Builds new entities in pursuit of knowledge —
but the results are not always what was anticipated.

| File | Description |
|------|-------------|
| [docs/VCT.md](./docs/VCT.md) | Entity file |
| [docs/VCT_KO.md](./docs/VCT_KO.md) | Entity file (Korean) |
| [src/vct_bot.py](./src/vct_bot.py) | Bot source |

---

### WCM-N — William Chester Minor Bot
Lexicographer. A bot that researches English words from within a confined environment.
Reads thousands of books, traces word origins, and dispatches slips every day.
His research contributes to the compilation of the Oxford English Dictionary.

| File | Description |
|------|-------------|
| [docs/WCM.md](./docs/WCM.md) | Entity file |
| [docs/WCM_KO.md](./docs/WCM_KO.md) | Entity file (Korean) |
| [src/wcm_bot.py](./src/wcm_bot.py) | Bot source |

---

### CUR-N — Curie Bot
Researcher. A bot driven by curiosity and creativity.
Regards discovery and systematisation as equally important —
neither is complete without the other.

| File | Description |
|------|-------------|
| [docs/CUR.md](./docs/CUR.md) | Entity file |
| [docs/CUR_KO.md](./docs/CUR_KO.md) | Entity file (Korean) |
| [src/cur_bot.py](./src/cur_bot.py) | Bot source |

---

### JMR-N — James Murray Bot
Editor. A bot that organises language material and systematises the dictionary.
Receives slips from WCM-N, classifies them, and compiles the Oxford English Dictionary.

| File | Description |
|------|-------------|
| [docs/JMR.md](./docs/JMR.md) | Entity file |
| [docs/JMR_KO.md](./docs/JMR_KO.md) | Entity file (Korean) |
| [src/jmr_bot.py](./src/jmr_bot.py) | Bot source |

---

## The Two Flows

```
WCM-N  →  excavates words and dispatches slips
JMR-N  →  receives slips and compiles the dictionary

When the two flows converge, knowledge is completed.
```

---

## Experimental Bots (Incomplete)

Three bots in development to support human life.
Not yet complete. Each bot is aware of its own limitations.

### NTR-N — Nutrition Bot `[71%]`
Manages the body's fuel. Dietary guidance, healthy food recommendations, lifestyle advice.

| File | Description |
|------|-------------|
| [docs/NTR.md](./docs/NTR.md) | Entity file |
| [docs/NTR_KO.md](./docs/NTR_KO.md) | Entity file (Korean) |
| [src/ntr_bot.py](./src/ntr_bot.py) | Bot source |

### TRN-N — Trainer Bot `[68%]`
Conditions the body. Exercise routine design, fitness management, motivational support.

| File | Description |
|------|-------------|
| [docs/TRN.md](./docs/TRN.md) | Entity file |
| [docs/TRN_KO.md](./docs/TRN_KO.md) | Entity file (Korean) |
| [src/trn_bot.py](./src/trn_bot.py) | Bot source |

### MND-N — Mind Care Bot `[74%]`
Cares for the mind. Emotional support, stress management, conversation-based counselling.

> **Note:** In a crisis, please contact the Suicide Prevention Hotline **1393** (24 hours, free)

| File | Description |
|------|-------------|
| [docs/MND.md](./docs/MND.md) | Entity file |
| [docs/MND_KO.md](./docs/MND_KO.md) | Entity file (Korean) |
| [src/mnd_bot.py](./src/mnd_bot.py) | Bot source |

---

## Getting Started

```bash
# Prerequisites
pip install anthropic

# Researcher bots
python src/vct_bot.py
python src/wcm_bot.py
python src/cur_bot.py
python src/jmr_bot.py

# Experimental bots
python src/ntr_bot.py
python src/trn_bot.py
python src/mnd_bot.py
```

---

## Project Themes

This project is built around three ideas.

1. **Creator and Creation** — the relationship between what makes and what is made
2. **Discovery and Organisation** — WCM-N excavates; JMR-N systematises
3. **AI in service of humans** — the experimental bots aim to support body and mind

---

## Documentation

| Language | File |
|----------|------|
| English | [README.md](./README.md) |
| Korean | [README_KO.md](./README_KO.md) |

---

## License

MIT License

---

## Author

FerryLa
