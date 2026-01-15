<div align="center">

# 🌱 PM-KUSUM Scheme Chatbot  
### *AI-Assisted Conversational System for Government Scheme Accessibility*

📍 **Developed during Technical Internship at BSPGCL, Patna**  
🎯 **Focused on PM-KUSUM Scheme – Component-C**

</div>

---

## 📌 Overview  

The **PM-KUSUM Scheme Chatbot** is a specialized conversational assistant designed to help farmers and citizens easily understand and navigate the **PM-KUSUM (Component-C) solar pump scheme**.

Government policies are often complex and difficult to interpret. This chatbot simplifies that by offering **instant, accurate, and multilingual assistance through both text and voice interfaces**.

---

## 🚀 Key Features  

| Feature | Description |
|--------|-------------|
| 🗣️ Dual-Mode Interaction | Supports both **text** and **voice-based** queries |
| 🎯 Intent Identification | Uses **rule-based keyword matching** to detect user intent |
| 🌐 Multilingual Support | Handles **English, Hindi & Hinglish** style inputs |
| 🛡️ Robust Error Handling | Handles **empty, unclear, or invalid queries** gracefully |
| 🔁 Guided Fallback Flow | Prevents conversation dead-ends with recovery prompts |

---

## 🛠️ Tech Stack  

| Layer | Technology |
|------|-----------|
| Frontend | React.js |
| Language | TypeScript |
| Styling | CSS Modules |
| Tools | VS Code, Git, GitHub |
| Voice Engine | Web Speech API |

---

## 🏗️ System Architecture  

The chatbot follows a **deterministic rule-based conversational flow**:

### 1️⃣ Speech-to-Text  
Voice input from users is converted into text using the **Web Speech API**.

### 2️⃣ Intent Recognition  
User input is matched against predefined **intent trees**, such as:
- Component-C eligibility  
- Subsidy details  
- Application process  
- Installation status  

### 3️⃣ Response Engine  
If a valid intent is found, the chatbot returns the corresponding answer.

### 4️⃣ Fallback System  
If no intent matches, the system triggers a **guided fallback flow** to help the user rephrase or choose from suggested options.

---

## 🧪 Testing & Quality Assurance  

To ensure reliability for government service delivery, the following testing strategies were used:

- 🔍 **Boundary Testing**  
  Verified behavior for incomplete, vague, or incorrect inputs.

- 🔄 **Multi-Turn Conversation Testing**  
  Ensured the chatbot maintains logical flow across multiple user queries.

- 📊 **Data Validation**  
  Focused on training keyword sets and intent mappings to maximize response accuracy.

---

## 📈 Impact  

The PM-KUSUM Chatbot delivered measurable benefits:

- 🌾 **Reduced friction** for farmers accessing scheme information  
- 📞 **Lowered dependency on BSPGCL staff for manual query handling**  
- 🕒 **Faster access** to subsidy, eligibility, and process details  
- 📚 **Improved awareness** of renewable-energy government schemes  

---

## 🎯 Vision  

To scale this system into a **state-wide or national digital assistant** that helps citizens access government welfare schemes through simple conversation — no paperwork, no confusion.

---

<div align="center">

💡 *Making Government Services Simple, Accessible, and Digital.*

</div>
