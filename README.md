# 🎧 Sonic Currency – NFT Valuation Engine for Spotify Songs

What if Spotify tracks were digital collectibles?

**Sonic Currency** is a Power BI-driven data storytelling project that ranks 5,000+ Spotify songs by their emotional and replay value — then simulates an NFT-style music marketplace using GPT-enhanced descriptions for top-performing tracks.

---

## 🚀 Project Highlights

- 🧠 Built a custom scoring model using **Mood**, **Replayability**, and **Uniqueness**
- 💽 Analyzed over **5,000 songs** from Spotify's audio features dataset
- 🎯 Created a **NFT_Valuation** metric to tier songs as **Common, Rare, or Legendary**
- 🧾 Integrated **GPT-style Listing Descriptions** for top 10+ tracks
- 📊 Designed a **multi-layer Power BI dashboard** including:
  - KPI metrics
  - Mood vs Replay scatter analysis
  - Valuation distribution histogram
  - Tier breakdown
  - Sonic Signature chart
  - **NFT Marketplace Table** with preview links
  - Dedicated **Listing Description View**

---

## 🛠️ Tools & Technologies

- **Power BI** (data modeling + visualization)
- **Python** with `Spotipy` (Spotify API integration)
- **Pandas** (data prep & scoring logic)
- **ChatGPT** (manual batch NFT description generation)
- **Spotify 160k Dataset** ([Kaggle](https://www.kaggle.com/datasets/fcpercival/160k-spotify-songs))

---

## 🧬 Scoring Model

Each song is scored using:

| Metric        | Description                                 |
|---------------|---------------------------------------------|
| `MoodScore`   | Based on valence, energy, danceability      |
| `ReplayScore` | Inverse of duration & loudness; repeat bias |
| `UniquenessScore` | How far a song strays from the average   |
| `NFT_Valuation` | Weighted combination of all 3              |

---

## 💎 NFT Tiers

| Tier        | Description                          |
|-------------|--------------------------------------|
| Legendary   | Top 5% of songs by valuation         |
| Rare        | Top 15%–5% of songs                  |
| Common      | Remaining base tier                  |

---

## 📸 Dashboard Preview

> 📊 *See the full dashboard in the project PDF:*  
> [🔗 View: SpotifyNFT_Project1.pdf](./SpotifyNFT_Project1.pdf)

---

## 📁 Files in This Repo

| File                     | Purpose                                 |
|--------------------------|------------------------------------------|
| `sonic_currency_dataset.csv` | Full 5,000-song dataset with scores     |
| `sonic_currency_final.csv`   | Top 9 songs with GPT descriptions       |
| `SpotifyNFT_Project1.pdf`    | Full Power BI dashboard preview (PDF)  |
| `README.md`                  | Project summary (this file)            |

---

## 📍 Future Enhancements (Coming Soon)

- 🤖 Automated GPT-4 song description generation via OpenAI API
- 🎛️ Streamlit interface to preview and mint your own "Sonic NFT"
- 🎵 Playlist generator based on MoodScore + Tier
- 💡 Artist-based filtering and trend detection

---

## 🙋‍♀️ Created By

**Parul Rajkondawar**  
🎓 MS in Information Technology & Management  
📍 University of Texas at Dallas  
🔗 [LinkedIn](https://www.linkedin.com/in/your-link) | [GitHub](https://github.com/your-github)

---

