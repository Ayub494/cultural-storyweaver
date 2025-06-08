# 🌍 Cultural StoryWeaver

Cultural StoryWeaver is a GenAI-powered storytelling app that generates culturally rich children's folk stories with moral values using Google's cutting-edge AI tools.

## ✨ Features

* Input a **country/culture**, **age group**, and **moral** to generate a custom story.
* Powered by **Google Vertex AI** and the **Gemini Pro model** via **Google AI Studio**.
* Clean and simple UI built using **Streamlit**.
* Download generated stories as text files.

## 🚀 Demo

Watch a step-by-step demo here: *(Upload your demo video and paste the YouTube or Drive link)*

## 🛠️ Tech Stack

* **Vertex AI** – To access and deploy Gemini Pro model.
* **Gemini Pro** – For creative story generation.
* **Google AI Studio** – For model prototyping and prompt tuning.
* **Streamlit** – For creating the user interface.

## 📦 Installation

```bash
pip install streamlit google-cloud-translate vertexai pyngrok
```

## ▶️ Running the App in Google Colab

1. Upload your `service-account.json` to Colab.
2. Run all setup cells (install libraries, write app, authenticate).
3. Use `pyngrok` to tunnel and expose the app.
4. Click the public URL to open your Streamlit app.

## 📝 Project Description

**Cultural StoryWeaver** is an AI-powered storytelling app designed to generate culturally inspired folk stories for children. Built using **Google Cloud’s Vertex AI** and the **Gemini Pro model** via **Google AI Studio**, the app creates imaginative stories based on a selected country, age group, and moral theme. With a simple interface powered by **Streamlit**, users can instantly generate and download custom stories tailored to different cultures and values. This project highlights the potential of **Generative AI in education and cultural awareness**, blending creativity with cutting-edge language models.

## 📁 Project Structure

```
cultural-storyweaver/
├── app.py
├── README.md
├── requirements.txt
└── your-service-account.json (excluded via .gitignore)
```

## ✅ How to Use

1. Clone this repo.
2. Replace `your-gcp-project-id` in `app.py`.
3. Upload your `service-account.json` file.
4. Run the app using Streamlit:

   ```bash
   streamlit run app.py
   ```

---

### 👏 Made using Google AI Tools:

* **Vertex AI**
* **Gemini Pro via AI Studio**
* **Google Cloud Translation API (optional)**

> Build inclusive, global AI experiences using the power of GenAI.

---

*Developed as part of a Generative AI project submission.*
