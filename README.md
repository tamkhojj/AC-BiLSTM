# 🏨 Aspect Based Sentiment Analysis in Ho Chi Minh City Hotel Reviews using Aspect-Conditioned BiLSTM with Cross-Aspect Attention and Ordinal Regression

## 📘 Understanding user sentiments in Vietnamese tourism reviews  

### 🌏 Overview  

Understanding user sentiments in tourism reviews is pivotal for enhancing service quality—especially in linguistically diverse and low-resource languages like Vietnamese.  

This study introduces a novel approach to Aspect-Based Sentiment Analysis (ABSA) for Vietnamese hotel reviews in Ho Chi Minh City, leveraging a curated dataset of **20,290 user-generated reviews** collected from major platforms such as:  

🏖️ TripAdvisor  
🗺️ Google Reviews  
✈️ Traveloka  

---

## 🧩 Dataset Description  

The dataset includes **10 annotated aspects**, each labeled with sentiment scores ranging from **−2 (strongly negative)** to **+2 (strongly positive)**:  

| # | Aspect | Description |
|---|---------|-------------|
| 1 | Room | Room quality, comfort, and facilities |
| 2 | Service | Staff attitude and professionalism |
| 3 | Location | Accessibility and surroundings |
| 4 | Price | Affordability and value for money |
| 5 | Food & Beverage | Restaurant and breakfast experiences |
| 6 | Amenities | Hotel facilities and convenience |
| 7 | Cleanliness | Hygiene and sanitation standards |
| 8 | Transportation | Accessibility to/from the location |
| 9 | Policy | Booking, refund, and check-in/out policies |
| 10 | Others | Miscellaneous impressions or unclassified comments |

---

## 🧠 Proposed Model: AC-BiLSTM  

We propose **Aspect-Conditioned BiLSTM with Cross-Aspect Attention and Ordinal Regression (AC-BiLSTM)** — an architecture specifically designed to handle **multi-aspect, ordinal sentiment prediction** for Vietnamese text.  

---

## ⚙️ Model Components  

- **PhoBERT** — Contextualized Vietnamese language embeddings  
- **BiLSTM** — Sequential processing of review text  
- **Cross-Aspect Attention** — Aspect-specific sentiment extraction  
- **Ordinal Regression Layer** — Captures sentiment intensity hierarchy  
- **Contrastive Learning** — Enhances representation consistency  

---

## 📊 Experimental Setup  

| Split | Samples |
|:------|---------:|
| Training | 16,232 |
| Validation | 2,029 |
| Test | 2,029 |
| **Total** | **20,290** |
# AC-BiLSTM
