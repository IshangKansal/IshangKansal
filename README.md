# 👋 Hey, I'm Ishang!

I'm a developer focused on **Machine Learning, Full-Stack Engineering, and Data Systems**.  
I enjoy building things that solve real problems — whether that’s **training models**, **analyzing data**, or **designing scalable backend systems**.

---

## 🧠 Skills & Tech

**Languages:** C++, Python, Java, SQL, JavaScript  
**Data & ML:** NumPy, Pandas, CNNs, ARIMA/ARMA, Hugging Face, Prophet  
**Backend / Tools:** Flask, PostgreSQL, Git, Streamlit, NeonDB  
**Frontend:** React, Next.js, TailwindCSS  
**Soft Skills:** Clear communication • Problem solving • Adaptable teamwork

---

## 🔥 Featured Projects

### 1) 🐍 Apache Jira Scraper → LLM Training Dataset  
**(Python, REST API, Data Engineering, NLP)**  
A **fault-tolerant data pipeline** that scrapes Apache Jira issues and converts them into **high-quality JSONL corpora** for **LLM training**.

- Resumable scraping with retries + rate-limit handling  
- Generates summaries, classification tags & Q/A tasks  
- Sharded output ready for training pipelines  

🔗 **Repo:** https://github.com/IshangKansal/jira-scraper  
📄 Dataset format: JSONL (cleaned + structured)

---

### 2) ⌨️ zero_-_one — Typing Test  
**(Python, Standard Library, Threading, CLI App)**  

A **beginner-friendly typing test** built in Python. It picks a random line from text files (grouped by difficulty), lets you type it, and then shows your **accuracy** and **WPM**.  
I also used a lightweight **background thread** to auto-end the test when the timer expires (it basically “presses Enter” for you in the backend).

**How it works 🚀**
- Prompts are stored in `.txt` files organized by difficulty.
- A random prompt is selected when the test starts.
- Your input is compared **word-by-word** to compute accuracy.
- WPM is calculated based on number of words typed in the time window.
- A background thread counts down and auto-submits your input when time ends.

**Requirements 📦**
- Python 3.x  
- Uses only standard libraries → `random`, `threading`, `time`, `sys`

**Why I built it ✨**
Just for fun and practice — specifically to learn:
- File handling
- Random prompt selection
- Basic threading for timers
- Calculating real-time accuracy + speed metrics

🔗 **Repo:** https://github.com/IshangKansal/zero_-_one

---

## 📊 Recent Work & Research

### Autism Spectrum Disorder (ASD) Detection using CNNs  
Designed and evaluated **deep learning pipelines** (VGG16, ResNet50) for early ASD screening using neuroimaging datasets — improving model robustness & diagnostic reliability.

---

## 🌱 Currently Learning
- Improving dataset quality for **LLM fine-tuning**
- Efficient inference + optimization strategies
- Advanced prompt engineering & structured knowledge distillation

---

## 📫 Connect With Me
Feel free to reach out — I love discussing ML ideas, dataset design, or just improving typing speed 🙂

