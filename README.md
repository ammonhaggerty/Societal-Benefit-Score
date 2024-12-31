# Societal Benefit Score

## Introduction

The **Societal Benefit Score** is a framework for assessing how a digital product (social network, app, platform, etc.) impacts human well-being. Rather than simply labeling features as “good” or “bad,” this system looks at both a platform’s **purpose** (Does it promote health, education, genuine connection?) and the **intensity** of specific design choices (e.g., streaks, FOMO, misinformation). By calculating a single numeric score, we can see which platforms lean more toward beneficial outcomes—and which lean more toward addictive or exploitative designs
## Core Principles

1. **Purpose matters.** The same feature—like streaks or influencer culture—can be positive in a fitness/education setting but negative in an entertainment/ad-driven setting.
2. **Feature presence has levels.** Each feature can be **Strong (S)**, **Moderate (M)**, or **Weak/None (W)**. Strong doubles the base multiplier, moderate uses the base multiplier as is, and weak/none contributes zero.
3. **Positive vs. Neutral vs. Negative features.** We categorize features into three buckets. **Positive features** always add to the score, **negative features** always subtract, and **neutral features** can switch between positive or negative (or zero) depending on the product’s mission.
## Feature Categories & Multipliers

Below is the list of features with their base multipliers:
### Positive Features

- **Societal benefit focus**: ×3
- **Encourages IRL** (real-life connection): ×2
- **Data ownership** (user-owned data, privacy-first): ×2
- **Opt-out controls** (tools to reduce manipulation): ×1
- **Badges** (acknowledging positive behavior): ×1
- **Levels** (structured progress or skill levels): ×1
### Neutral Features

- **Streaks**: ±1
- **Infinite scroll**: ±1
- **Video Shorts**: ±2
- **FOMO** (fear of missing out): ±2
- **Social pressure**: ±2
- **Location sharing**: ±2
- **Celebrity/Influencer culture**: ±2

> **Note**: Neutral features become **positive** if the product’s primary mission is health, education, or genuine human connection; become **negative** if it’s purely ad-driven or entertainment-focused; or become **zero** if the purpose is somewhat beneficial but also potentially stressful (e.g., LinkedIn and job search).

### Negative Features

- **AI training** (monetizing user data to train AI): ×2
- **Selling your behavior** (data brokers, advanced ad targeting): ×2
- **Misinformation**: ×3
- **Mob mentality** (filter bubbles, polarization): ×3

These always subtract from the final score, with **strong** presence doubling the penalty.
## Presence Levels

Each feature on a product is labeled **Strong (S)**, **Moderate (M)**, or **Weak/None (W)**:
- **Strong (S)** → multiply the feature’s base multiplier by **2**.
- **Moderate (M)** → use the base multiplier as is.
- **Weak/None (W)** → **0** (no impact).
## Step-by-Step Mechanics

1. **Classify the Product’s Purpose**
    - **Health/Education/Human Connection**: Neutral features become **positive**.
    - **Primarily Ad-/Entertainment-Driven**: Neutral features become **negative**.
    - **Mixed/Partial Benefit**: Neutral features become **0**.
2. **Identify Feature Presence**
    - For each feature, decide if the platform’s use of it is **Strong**, **Moderate**, or **Weak/None**.
3. **Apply Multipliers**
    - For each **Positive** feature present, add the base multiplier (×2 if strong).
    - For each **Neutral** feature, convert it to +, –, or 0 based on product purpose, then apply the multiplier (and double if strong).
    - For each **Negative** feature present, subtract the base multiplier (and double if strong).
4. **Sum Up the Score**
    - A higher (or positive) score suggests more user-friendly, socially beneficial design.
    - A lower (negative) score indicates heavier reliance on manipulative or exploitative patterns.

## Example Calculations

### Example: **Duolingo**
- **Purpose**: Education → **Neutral features become positive**.

Suppose we label Duolingo’s features as follows:
- **Societal benefit focus**: Moderate (M) → base +3
- **Encourages IRL**: Strong (S) → +2 doubled = +4
- **Data ownership**: Weak (W) → 0
- **Opt-out controls**: Moderate (M) → +1
- **Badges**: Strong (S) → +1 doubled = +2
- **Levels**: Strong (S) → +1 doubled = +2

Since it’s education-focused, **Neutral** features (streaks, FOMO, etc.) become **positive**:
- **Streaks**: Strong (S), base ±1 → now +1 doubled = +2
- **FOMO**: Moderate (M), base ±2 → now +2
- **Infinite scroll**: Weak (W) → 0

Negative features (AI, selling behavior, misinformation, etc.) might be weak or moderate:
- **AI training**: Moderate (M), ×2 → –2
- **Selling behavior**: Weak (W) → 0
- **Misinformation**: None (W) → 0
- **Mob mentality**: None (W) → 0
#### Summation
- **Positive**: 3 + 4 + 1 + 2 + 2 + 2 + 2 + 2 = 18
- **Negative**: 2 (AI training) + 0 + 0 + 0 = 2
- **Final Score** = 18 – 2 = **+16**

### Example: **TikTok**  
- **Purpose**: Entertainment → Neutral features become **negative**.

Suppose we label TikTok’s features as follows:
- **Societal benefit focus**: Weak (W) → **0**
- **Encourages IRL**: Weak (W) → **0**
- **Data ownership**: Weak (W) → **0**
- **Opt-out controls**: Moderate (M) → **+1**
- **Badges**: Moderate (M) → **+1**
- **Levels**: Weak (W) → **0**

Since it’s **entertainment-focused**, **Neutral** features (infinite scroll, FOMO, etc.) become **negative**:
- **Infinite scroll**: Strong (S), base ±1 → now **–1** doubled = **–2**
- **Video Shorts**: Strong (S), base ±2 → now **–2** doubled = **–4**
- **FOMO**: Strong (S), base ±2 → now **–2** doubled = **–4**
- **Social pressure**: Strong (S), base ±2 → now **–2** doubled = **–4**
- **Celebrity/Influencer culture**: Strong (S), base ±2 → now **–2** doubled = **–4**
- **Streaks**: Weak (W) → **0**
- **Location sharing**: Weak (W) → **0**

Negative features (AI training, selling behavior, misinformation, etc.) might be weak or moderate:
- **AI training**: Moderate (M), ×2 → **–2**
- **Selling your behavior**: Strong (S), base ×2 → now **–2** doubled = **–4**
- **Misinformation**: Strong (S), base ×3 → now **–3** doubled = **–6**
- **Mob mentality**: Moderate (M), base ×3 → now **–3**
#### Summation
- **Positive**: 1 (Opt-out) + 1 (Badges) = **2**
- **Negative**:
    - 2 (Infinite scroll) + 4 (Video Shorts) + 4 (FOMO) + 4 (Social pressure) + 4 (Celebrity)
    - - 2 (AI training) + 4 (Selling behavior) + 6 (Misinformation) + 3 (Mob mentality)  
            = 2 + 4 + 4 + 4 + 4 + 2 + 4 + 6 + 3 = **33**
- **Final Score = 2 – 33 = –31**

TikTok’s **–31** indicates heavy reliance on attention hooks (infinite scroll, video shorts, FOMO) and data monetization practices, with minimal emphasis on societal well-being or user empowerment.
