# 💬Yatra-Planner-Travel-Ai-Agent
An intelligent, AI-powered travel assistant that helps users plan, book, and manage their trips through natural, conversational interaction. Built using IBM Cloud and Granite LLM, the bot offers personalized recommendations, real-time travel updates, itinerary management, and 24/7 support—all in one place.

---

## 🧩 Problem Statement

Planning a trip can be overwhelming—especially for travelers unfamiliar with digital tools or navigating foreign destinations. Users face difficulties comparing options, managing bookings, understanding travel restrictions, or handling disruptions like delays and cancellations, which lead to stress, poor planning, and missed opportunities.

---

## 💡 Proposed Solution

Travel AI Agent Bot is a smart AI travel agent powered by **IBM Watsonx.ai** and **Granite LLM**. It delivers reliable, document-based answers to travel-related queries using **Retrieval-Augmented Generation (RAG)** and multilingual capabilities. The bot provides personalized recommendations, real-time updates, and grounded support throughout the user’s travel journey.

---

## 🧠 Technologies Used

- **IBM Watsonx.ai Studio**
- **IBM Granite Foundation Model (LLM)**
- **Vector Index for Retrieval-Augmented Generation**
- **Travel documents, itineraries, FAQs, and advisories (PDF/HTML)**
- **Natural Language Processing (NLP)**
- **IBM Cloud Object Storage**

---

## ☁️ IBM Cloud Services Used

- Watsonx.ai Studio
- IBM Granite Model
- Watsonx Vector Index
- IBM Cloud Lite Account
- IBM Cloud IAM
- IBM Cloud Object Storage

---

## 👥 End Users

- Leisure travelers planning personal vacations
- Business travelers needing real-time, efficient assistance
- Students or first-time flyers needing step-by-step support
- Digital nomads managing frequent travel
- Travel agencies and tour operators automating services
- NGOs or organizations helping rural travelers or migrants
- Customer support centers offering AI-driven travel help

---

## 🌟 WOW Factors

- Uses RAG to pull responses from real travel documents (e.g., booking FAQs, advisories, or uploaded PDFs)
- Built entirely on IBM Cloud using Watsonx tools
- Offers real-time, personalized trip planning and emergency help
- Responds politely to off-topic queries and handles natural language
- Multilingual-ready for international users
- Supports the entire travel lifecycle—from inspiration to post-trip feedback

---

## 🧪 Key Features

- Personalized travel Q&A via Vector Index
- Built on IBM Granite LLM for human-like conversation
- Suggests flights, hotels, local attractions, and safety tips
- Helps with travel disruption handling (delays, rebookings, cancellations)
- Gracefully responds to irrelevant or unsupported queries
- Guides users through itinerary creation and optimization

---

## 🚀 How It Works

1. **User submits a travel query**  
   _Example:_ “Best places to visit in Japan in November”
2. **IBM Granite LLM processes the question and intent**
3. **Vector Index retrieves relevant content from stored travel docs or guides**
4. **The bot responds with a contextual, easy-to-follow answer**

---

## 🛠️ Installation & Usage

> _Instructions below are a template. Please update with your repository’s actual setup steps._

### Prerequisites
- IBM Cloud account (Lite or higher)
- Access to Watsonx.ai Studio and Granite Model

### Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-org/yatra-planner-travel-ai-agent.git
   cd yatra-planner-travel-ai-agent
   ```

2. **Configure IBM Cloud credentials**  
   Set up environment variables or configuration files as per your authentication method.

3. **Upload relevant travel documents to IBM Cloud Object Storage**

4. **Deploy the bot using Watsonx.ai Studio**

5. **Start the service**
   ```bash
   # Example command
   python run_bot.py
   ```

### Usage

- Interact with the bot via web, chat app, or API endpoint.
- Submit travel questions and receive AI-powered responses.

---

## 🤝 Contributing

Pull requests are welcome! For significant changes, please open an issue first to discuss your ideas.

---

## 📜 License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.

---

## 🙏 Credits

- IBM Watsonx.ai and Granite LLM teams
- Contributors and testers

---

## 📬 Contact

For support, contact [your-email@example.com] or open an issue.

