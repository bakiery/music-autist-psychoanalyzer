# 🚩 music-autist-psychoanalyzer

A clinically autistic, meme-tier psychoanalysis engine that **brutally roasts your entire existence based solely on your raw Spotify or Last.fm data**.

No HR-safe answers. No LinkedIn diversity-washing. Just savage, data-driven truth and neurotic, hyper-detailed judgment—powered by open GPT-OSS 20B.

---

## 🚨 WARNING: WILL EAT YOUR LAPTOP ALIVE

> **This project requires a MASSIVE AMOUNT OF RAM** (32GB recommended, 16GB is absolute minimum for GPT-OSS 20B).
> Running with less RAM will cause lag, swap hell, and may crash your system.
> If you have 16GB or less, use pre-generated outputs or try much smaller (non-gpt-oss) models—but don’t expect full meme-roast quality.
>
> **NO DIVERSITY-WASHING, NO CORPORATE FILTERS.**
> Output is savage, offensive, and terminally online.
> Not recommended for HR, LinkedIn normies, or anyone allergic to reality.

---

## 📝 Features

| Feature                | Description                                                             |
|------------------------|-------------------------------------------------------------------------|
| Brutal Psychoanalysis  | No-PC, clinical, meme-tier roast based on your raw music taste.         |
| Demographic Guessing   | Predicts age, gender, sexuality, neurotype, social status, and more.    |
| Online Subculture Map  | Identifies your likely Discord servers, meme diet, and forum habits.    |
| “Mog” Detection        | Tells you exactly who you mog, who mogs you, and why.                   |
| Customizable Models    | Works with GPT-OSS 20B (or other Ollama models—see warnings below).     |
| Jupyter Notebook Demo  | Interactive, copy-paste friendly, works with pre-canned output.         |

---

## 🚩 What does it do?

You dump your music taste (Spotify/Last.fm top tracks, genres, playlists, scrobbles, etc).  
Example: For your raw Spotify stats (last 1/6/12 months), use [FavoriteMusic.Guru](http://favoritemusic.guru).

The model **diagnoses you**:  
- Age, gender, neurotype, likelihood of LGBTQ+
- DSM-5 traits (autism/BPD/etc), political leanings
- MBTI/Socionics/Enneagram, IRL and online archetype
- Exactly who you mog/who mogs you in terms of social status and SES

**Output:**  
A full psycho-meme roast. Not for normies, LinkedIn clout-chasers, or anyone allergic to reality.

---

## 🦾 Why is this different?

- **No filter, no cope:** Roasts you using raw, clinical, non-PC logic.
- **Savage as fuck:** If you’re a “midwest emo femboy” or a “cyber-goth meme alchemist,” it’ll tell you.
- **Gen Z/Terminally Online POV:** Knows your Discord servers, TikTok meme diet, and 4chan /mu/ browsing history.
- **Actually uses LLMs:** Demo runs GPT-OSS-20B locally via Ollama (or, with warnings, other Ollama models).

---

## ⚙️ Hardware Requirements

- **GPT-OSS 20B:** 32GB RAM *strongly* recommended (16GB minimum with swap abuse), SSD with 20GB+ free space.
- **Tested on:** Apple Silicon (M1/M2/M3) and Linux/Windows with enough RAM.
- **Running on a potato?** Use pre-baked outputs in the notebook; don’t try to load 20B unless you want your machine to cry.

---

## 🏃‍♂️ Quickstart

1. **Clone the repo:**
    ```bash
    git clone https://github.com/bakiery/music-autist-psychoanalyzer.git
    cd music-autist-psychoanalyzer
    ```

2. **[Install Ollama](https://ollama.com/download)** and pull the desired model:
    ```bash
    ollama pull gpt-oss:20b
    # (Or try gemma/deepseek if you want, but results will NOT be as savage.)
    ```

3. **Run the notebook or script.**
    - If your Mac starts screaming, stop and use a smaller model or load pre-run demo results.

4. **Paste your raw Spotify/Last.fm data** as shown in [`notebook/music_autist_demo.ipynb`](notebook/music_autist_demo.ipynb).

5. **Enjoy your clinical roast.**

---

## ❗ Disclaimer

- This project is for **meme, educational, and research purposes only**.
- Output may be offensive, unfiltered, or unhinged by design.
  Not intended for HR, therapy, or LinkedIn cringe posts.
- **DO NOT** run large models on low-RAM machines; you WILL thrash your disk.
- No warranty, no guarantee of “accuracy,” and definitely **not safe for normies**.

---

## 🤝 Contributing

Open to PRs—especially for better meme-roasts, new archetypes, or making it even more unhinged.

---

## 📜 License

Licensed under Apache-2.0. See [LICENSE](LICENSE) for details.

---

> *If you die from cringe or your MacBook dies from swap overload, you were warned.*
