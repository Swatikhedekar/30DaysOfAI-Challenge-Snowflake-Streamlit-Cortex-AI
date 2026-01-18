# 🔄 Day 3: Write Streams
### 30 Days of AI – Streamlit × Snowflake Cortex

This project is part of the **#30DaysOfAI challenge**, designed to help you build AI applications using **Streamlit** and **Snowflake Cortex**.

On **Day 3**, we explore **streaming LLM responses** using the Snowflake Cortex **Complete Python API**, displaying AI output in real time as it is generated.
![Project Banner](https://github.com/Swatikhedekar/30DaysOfAI-Challenge-Snowflake-Streamlit-Cortex-AI/blob/main/Day%203/s3.png?raw=true)

---

## 🧠 What You’ll Learn
- How to use the **Cortex Complete Python API**
- How to stream LLM responses token-by-token
- How to build real-time AI UIs in Streamlit
- Differences between direct streaming and custom generators

---

## 🛠️ Tech Stack
- Streamlit  
- Snowflake Snowpark  
- Snowflake Cortex (Complete API)

---

## ⚙️ How It Works
1. User selects an LLM model
2. User enters a prompt
3. Cortex generates the response
4. The response is streamed live in the UI using `st.write_stream()`

Two streaming methods are demonstrated:
- **Direct streaming (`stream=True`)**
- **Custom generator (compatibility mode)**

---

## ▶️ Output
The AI response appears **word by word in real time**, creating a smooth chat-like experience.

---

## 📚 Resources
- Snowflake Cortex Complete Python API  
- `st.write_stream()` Documentation  

---

✨ *Day 3 complete — real-time AI streaming with Snowflake Cortex!*

