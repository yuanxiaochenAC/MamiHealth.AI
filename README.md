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
  <img src="Asset/landing_page.jpg" alt="Landing Page" width="600"/>
  <br/>
  <em>Landing Page</em>
  <br/><br/>

  <img src="Asset/chat_page.JPG" alt="Chat Interaction" width="600"/>
  <br/>
  <em>Chat Interaction</em>
  <br/><br/>

  <img src="Asset/setting_page.JPG" alt="Settings Page" width="600"/>
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

| Key             | Description                       |
|----------------|------------------------------------|
| `GEMINI_API_KEY` | Required to access the AI service |

---

## 📊 Roadmap

- [ ] Native iOS & Android app  
- [ ] Personalized health dashboard  
- [ ] Recipe and meal planning module  
- [ ] Partnerships with health check centers and insurance  
- [ ] Daily health nudges and reward system  

---

## 📄 License

This project is licensed under the **MIT License**.  
See [`LICENSE`](./LICENSE) for details.
