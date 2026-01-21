##⚡ Day 5: Build a Post Generator App
For today's challenge, our goal is to build a Streamlit web application that generates a professional LinkedIn post. We need to call Snowflake's Cortex AI function from within the Streamlit app to generate the post content based on user-provided input like a URL, desired tone, and length. Once that's done, we will display the generated LinkedIn post text in the application's user interface.

This project is part of the 30DaysOfAI-challenge, designed to help you build AI applications using Streamlit and Snowflake Cortex.

On Day 5, our goal is to build a Streamlit web application that generates a professional LinkedIn post.

🧠 What You’ll Learn
How to call a Cortex LLM from Streamlit
How to use st.cache_data to cache AI responses
How caching reduces response time for repeated prompts
How to measure and display request execution time
🛠️ Tech Stack
Streamlit
Snowflake Snowpark
Snowflake Cortex (LLMs)
⚙️ How It Works
User enters a prompt in the app
The prompt is sent to a Cortex LLM (e.g., Claude 3.5 Sonnet)
The response is cached using st.cache_data
Repeated prompts return instantly from cache
Execution time is displayed along with the response
▶️ Output
AI-generated response displayed in the app
Time taken for the request shown clearly
Cached responses load almost instantly
📚 Resources
Streamlit st.cache_data Documentation
Caching in Streamlit
Streamlit in Snowflake Caching Limitations
✨ Day 4 complete — faster AI apps with smart caching!
