# 🎵 Emotion-Based BGM Classification

A MECE-structured library for classifying short‑video background music (BGM) by **emotion & atmosphere**.

This repository helps creators, editors, and algorithmic recommendation systems quickly choose suitable music based on emotional intent.

---

# ⭐ Badges

![Status](https://img.shields.io/badge/status-active-brightgreen)
![Category](https://img.shields.io/badge/category-music%20classification-blue)
![License](https://img.shields.io/badge/license-MIT-yellow)
![Made%20For](https://img.shields.io/badge/made%20for-short%20video%20creators-purple)

---

# 📁 Repository Structure

```
emotion-bgm/
├── README.md
├── categories/
│   ├── happy_uplifting.md
│   ├── warm_healing.md
│   ├── inspirational_epic.md
│   ├── tense_suspense.md
│   ├── romantic_soft.md
│   ├── cool_tech.md
│   ├── calm_minimal.md
│   └── playful_funny.md
└── tags/
    ├── emotion_tags.json
    └── keyword_map.json
```

---

# 🌈 Emotion Classification Overview

This repository uses **MECE**（Mutually Exclusive, Collectively Exhaustive） to ensure classifications are不重叠 and 覆盖所有主流短视频情绪。

## **1. Happy / Uplifting**

* Keywords: bright, cheerful, upbeat, good mood
* Styles: sunshine pop, bossa nova, upbeat edm
* Use cases: vlog, travel, celebrations

## **2. Warm / Healing**

* Keywords: cozy, gentle, peaceful, comforting
* Styles: soft piano, acoustic folk, ambient pads
* Use cases: lifestyle, emotional narration

## **3. Inspirational / Epic**

* Keywords: powerful, rising, motivational
* Styles: cinematic, orchestral, epic drums
* Use cases: sports, success stories

## **4. Tense / Suspense**

* Keywords: dark, mysterious, pulse, dramatic
* Styles: dark electronic, low-frequency beats
* Use cases: mystery skits, storytelling

## **5. Romantic / Soft**

* Keywords: dreamy, tender, sweet
* Styles: jazz, soft ballads, dreamy edm
* Use cases: romance, aesthetic clips

## **6. Cool / Tech**

* Keywords: futuristic, digital, neon
* Styles: synthwave, techno, future bass
* Use cases: product showcases, tech ads

## **7. Calm / Minimal**

* Keywords: quiet, reflective, pure
* Styles: minimal piano, ambient soundscapes
* Use cases: focus, meditation, study

## **8. Playful / Funny**

* Keywords: quirky, cute, whimsical
* Styles: cartoon fx, ukulele, bouncy beats
* Use cases: comedy, pets, kids

---

# 🧩 Metadata Format

```
{
  "emotion": "warm",
  "keywords": ["cozy", "gentle", "peaceful"],
  "styles": ["piano", "acoustic", "ambient"],
  "use_cases": ["lifestyle", "story"],
  "intensity": "low"
}
```

---

# 🚀 Usage Guide

## **1. For Creators**

Use the `categories/` folder to quickly select the best emotional BGM type for your video.

## **2. For Developers**

Integrate `emotion_tags.json` as a tagging system in recommendation models or content search.

## **3. For Editors / Teams**

Use the repo as a standard reference when briefing editors or planning content.

---

# 🧱 Future Roadmap

* Add audio examples (YouTube / CC0 sources)
* Add ML emotion‑prediction dataset
* Build a small web UI for browsing

---

# 📄 License

MIT License — free to use, modify, and distribute.
