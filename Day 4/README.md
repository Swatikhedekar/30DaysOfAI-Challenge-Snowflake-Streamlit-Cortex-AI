# ⚡ Day 4: Caching Your App
### 30 Days of AI – Streamlit × Snowflake Cortex

This project is part of the **30DaysOfAI-challenge**, designed to help you build AI applications using **Streamlit** and **Snowflake Cortex**.

On **Day 4**, we focus on improving performance by **caching LLM responses** in a Streamlit app that calls a Snowflake Cortex model.

---

## 🧠 What You’ll Learn
- How to call a Cortex LLM from Streamlit
- How to use `st.cache_data` to cache AI responses
- How caching reduces response time for repeated prompts
- How to measure and display request execution time

---

## 🛠️ Tech Stack
- Streamlit  
- Snowflake Snowpark  
- Snowflake Cortex (LLMs)

---

## ⚙️ How It Works
1. User enters a prompt in the app
2. The prompt is sent to a Cortex LLM (e.g., Claude 3.5 Sonnet)
3. The response is cached using `st.cache_data`
4. Repeated prompts return instantly from cache
5. Execution time is displayed along with the response

---

## ▶️ Output
- AI-generated response displayed in the app  
- Time taken for the request shown clearly  
- Cached responses load almost instantly

---

## 📚 Resources
- Streamlit `st.cache_data` Documentation  
- Caching in Streamlit  
- Streamlit in Snowflake Caching Limitations  

---

✨ *Day 4 complete — faster AI apps with smart caching!*

