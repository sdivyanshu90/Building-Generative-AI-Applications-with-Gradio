# 🌟 Building Generative AI Applications with Gradio

Welcome! 👋
This repo contains all the **Jupyter notebooks** for the course **[Building Generative AI Applications with Gradio](https://www.deeplearning.ai/)**, created by **DeepLearning.AI**.

In this course, you’ll learn how to use [Gradio](https://www.gradio.app/) to **prototype, demo, and share generative AI applications** — all with just a few lines of Python code!

---

## 📚 What You’ll Learn

By working through these notebooks, you’ll gain hands-on experience with:<br>
✅ Setting up interactive apps using Gradio.<br>
✅ Building text, image, and audio generation demos.<br>
✅ Connecting large language models (LLMs) to Gradio.<br>
✅ Combining multiple components for more advanced apps.<br>
✅ Sharing your apps with friends, classmates, or the world 🌍.<br>

---

## 🚀 Getting Started

### 1️⃣ Clone this repo

```bash
git clone https://github.com/sdivyanshu90/Building-Generative-AI-Applications-with-Gradio.git
cd Building-Generative-AI-Applications-with-Gradio
```

### 2️⃣ Install dependencies

It’s best to create a virtual environment first:

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows

```

### 3️⃣ Launch Jupyter Notebook

```bash
jupyter notebook
```

Now open any notebook and start learning 🎉.

---

## 🛠️ Requirements

* Python 3.8+
* Jupyter Notebook
* [Gradio](https://www.gradio.app/)

---

## 🌍 Sharing Your First Gradio App

Here’s a tiny sneak peek of what you’ll build:

```python
import gradio as gr

def greet(name):
    return f"Hello {name} 👋"

demo = gr.Interface(fn=greet, inputs="text", outputs="text")
demo.launch(share=True)
```

👉 Run it, and you’ll get a **public link** to share your app instantly!

---

## 🤝 Contributing

This repo is mainly for learners following the DeepLearning.AI course.
But if you find a typo, bug, or want to improve the notebooks, PRs are welcome!

---

## 📜 License

This repo shares example notebooks for **educational purposes**, adapted from the official DeepLearning.AI course.
Please check the **[course terms of use](https://www.deeplearning.ai/)** before redistributing.

---

## 🙏 Acknowledgements

This course and materials are provided by **[DeepLearning.AI](https://www.deeplearning.ai/)**.
Special thanks to the **Gradio team** for making model prototyping simple, fast, and fun!

---

✨ Happy Learning & Happy Building! ✨
