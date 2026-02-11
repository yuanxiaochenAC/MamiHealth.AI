<!-- MamiHealth Banner Section -->
<div align="center">
  <img src="Asset/logo.png" alt="MamiHealth Logo" width="180"/>
</div>

<h2 align="center">
  爱你妈咪 MamiHealth
</h2>

<p align="center">
  Your AI Nutrition Companion — Make Better Food Choices, One Photo at a Time  
  <br/>
  你的 AI 饮食伙伴 —— 每一口之前，做出更健康的选择
</p>

<br/>

<!-- App Previews (Vertical Layout) -->
<div align="center">
  <img src="Asset/landing_page.jpg" alt="Landing Page" width="1000"/>
  <br/>
  <em>Landing Page</em>
  <br/><br/>

  <img src="Asset/chat_page.JPG" alt="Chat Interaction" width="1000"/>
  <br/>
  <em>Chat Interaction</em>
  <br/><br/>

  <img src="Asset/setting_page.JPG" alt="Settings Page" width="1000"/>
  <br/>
  <em>Settings Page</em>
</div>

---

## 💡 What is MamiHealth?

**MamiHealth** is an AI-powered nutrition companion designed for people managing chronic diseases, weight loss goals, or unhealthy eating habits due to busy lifestyles.

It turns a simple daily habit — taking a photo before meals — into a powerful health decision-making moment, with personalized food suggestions based on user profiles, health data, and medical risks.

Unlike calorie-counting apps, MamiHealth offers warm, empathetic, and behavior-friendly AI support that meets users where they are.

---

## 🧭 System Workflow Overview

Below is a simplified workflow of how MamiHealth operates behind the scenes:

```
         ┌───────────────────────┐
         │   User takes photo    │
         └─────────┬─────────────┘
                   │
                   ▼
   ┌────────────────────────────────────┐
   │   AI analyzes the meal image       │
   │ (e.g. food type, calories, sodium) │
   └─────────┬──────────────────────────┘
             │
             ▼
  ┌────────────────────────────────────────┐
  │   Match with user health profile       │
  │  (e.g. diabetes, gout, weight goals)   │
  └─────────┬──────────────────────────────┘
            │
            ▼
  ┌──────────────────────────────────────┐
  │   Generate personalized suggestion   │
  │   (via warm Mami AI dialogue)        │
  └─────────┬────────────────────────────┘
            │
            ▼
  ┌──────────────────────────────────────┐
  │     Update long-term user archive    │
  │     (trend chart, risk history)      │
  └──────────────────────────────────────┘

```

---

## 💻 Run Locally

```bash
git clone https://github.com/YourOrg/MamiHealth.git
cd MamiHealth
npm install
```

```bash
# Set up your API key
echo "GEMINI_API_KEY=your_api_key_here" > .env.local
```

```bash
npm run dev
```

Then open: `http://localhost:5173`

---

## 🔐 Environment Variables

MamiHealth uses environment variables for secure access to backend services. Please create a `.env.local` file in the root directory of your project and configure the following keys:

| Key               | Description                                                           |
|-------------------|------------------------------------------------------------------------|
| `GEMINI_API_KEY`  | Required to access the AI backend (used for meal image understanding)  |
| `NEXT_PUBLIC_ENV` | (Optional) Set to `production` or `development` to toggle runtime modes |

> **Note:** Never commit your `.env.local` file to version control.

---

## 🎯 Target Users

MamiHealth is designed for **high-intent health users** who require simple, actionable meal-time support. Core personas include:

- 👨‍⚕️ **Chronic Disease Managers**  
  Users managing conditions like **gout**, **diabetes**, **high blood pressure**, or **fatty liver** who require strict, ongoing dietary discipline.

- 👩 **Weight Control Users**  
  Users with long-term **weight loss** or **body composition goals**, often cycling through willpower failures and seeking sustainable support.

- 🏙 **Urban Professionals (外卖依赖者)**  
  Office workers aged 25–40, eating irregularly or ordering takeout daily, who want **quick, smart nudges** on what to eat, when, and how much.

- 👪 **Health-aware Families**  
  Young parents or caregivers seeking nutritional guidance for **children**, **pregnant women**, or **elderly family members**.

Each user receives **differentiated tone**, **nudging frequency**, and **behavior feedback** from the AI based on their profile.

---

## 🔬 B2B Use Cases

In addition to the consumer-facing app, MamiHealth is developing a suite of **modular B2B features** for integration across sectors:

- 🏥 **Health Check Centers & Clinics**  
  Plug into post-screening health dashboards to provide AI-generated dietary suggestions based on **lab results + user photos**.

- 🏢 **Corporate Wellness Platforms**  
  Provide nutrition nudges & tracking tools for employees with **gamified meal scoring**, weekly trend reports, and anonymized group insights.

- 🛡️ **Insurance & Health Risk Scoring**  
  License user behavior models for **diet-based underwriting**, chronic condition risk detection, and long-term health scoring.

- 🥗 **Nutrition & Food Brands**  
  Provide AI-driven **targeted recommendation engine** to suggest healthier substitutes based on user needs (e.g. low-sodium sauce for hypertensive user).

- 📚 **Schools, Gyms, & Lifestyle Communities**  
  Deploy simplified front-end meal tracking & suggestion widgets to groups with **custom rulesets** (e.g. sports teams, children, vegans).

---

## 📊 Roadmap

We are building MamiHealth as a long-term platform that blends **empathy + AI** to help people eat better every day.

### ✅ In Progress

- Native **iOS & Android** app (built with React Native)  
- Photo recognition + GPT-style food suggestion logic  
- Behavior nudging logic tuning by user segment  
- Personalized **nutrition dashboard**

### 🔜 Planned

- Health trend reports (weekly/monthly PDF exports)  
- Food recommendation engine integration with **e-commerce** (e.g. recipe kits, grocery delivery)  
- Rewards/loyalty system based on consistent usage  
- Partnership API for health labs, gyms, HR systems  
- Voice-based meal logging (for elderly users)

### 💭 Long-Term Vision

- Build a **nutrition intelligence layer** for Asia  
- Turn MamiHealth into a **“pre-meal Siri”**, deeply integrated into smartwatches, fridges, or ordering platforms  
- Offer **emotion-aware dietary guidance** through voice tone & context

---

## 📄 License

This project is licensed under the **MIT License**.  
See [`LICENSE`](./LICENSE) for details.
