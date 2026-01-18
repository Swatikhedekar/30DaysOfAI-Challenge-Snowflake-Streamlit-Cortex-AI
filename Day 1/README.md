# 🚀 Day 1: Connect to Snowflake  
### 30DaysOfAI – Streamlit × Snowflake

This project is part of the **#30DaysOfAI challenge**, where we build AI and data-driven applications using **Streamlit** and **Snowflake**.

On **Day 1**, we focus on establishing a secure connection between a Streamlit app and Snowflake, then validating the connection by querying the Snowflake version.

---

## 🧠 What You’ll Learn
- How to connect Streamlit to Snowflake using **Snowpark**
- How to manage credentials securely using **Streamlit Secrets**
  
---

## 🛠️ Tech Stack
- **Streamlit**
- **Snowflake**
- **Snowpark (Python)**

---

## 📌 How It Works
The app automatically detects the environment:
- **Streamlit in Snowflake** → Uses `get_active_session()`
- **Local / Streamlit Community Cloud** → Uses `Session.builder` with `secrets.toml`

A simple SQL query (`SELECT CURRENT_VERSION()`) confirms the connection.

---

## ▶️ Output
![Project Banner](https://github.com/Swatikhedekar/30DaysOfAI-Challenge-Snowflake-Streamlit-Cortex-AI/blob/main/Day%201/s1.png?raw=true)
---

## 🔗 Resources
- https://30daysofai.streamlit.app/?day=1

---

✨ *Day 1 complete! Stay tuned for Day 2 of the 30DaysOfAI challenge.*

