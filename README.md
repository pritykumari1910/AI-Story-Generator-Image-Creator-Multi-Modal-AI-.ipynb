# ✨ AI Story + Image Generator  
Generate creative stories and matching AI images using Large Language Models (Phi-2) and Stable Diffusion in a simple web UI (Gradio or Streamlit).

---

## 🚀 Project Overview

This project combines **Natural Language Generation (NLG)** and **Image Generation** models to create a unique interactive experience.  
Users enter any **story theme**, and the system generates:

1. 📝 **A creative short story** using Phi-2 (text generation model)  
2. 🎨 **A matching AI-generated image** using Stable Diffusion  
3. 🌐 **A web-based UI** built using **Gradio** or **Streamlit**

This project is easy to run on **Google Colab**, **local machine**, or deploy on **HuggingFace Spaces** or **Streamlit Cloud**.

---

## ✨ Features

- ✔️ Generate original short stories from any theme  
- ✔️ Create stunning AI images matching the story  
- ✔️ Clean and interactive UI (Gradio or Streamlit)  
- ✔️ Uses state-of-the-art AI models  
- ✔️ Runs on Colab GPU  
- ✔️ Beginner-friendly and great for portfolios  
- ✔️ Fully open-source

---

## 🧠 Technology Used

| Component | Description |
|----------|-------------|
| **Phi-2** | Lightweight LLM for text generation (Microsoft) |
| **Stable Diffusion v1.5** | Text-to-image generation model |
| **Gradio / Streamlit** | UI for interacting with the app |
| **HuggingFace Diffusers** | Stable Diffusion pipeline |
| **Transformers Library** | For text model loading |
| **Google Colab** | Recommended execution environment |

---

## 📂 Project Structure



project/
│── app.py # Streamlit UI (optional)
│── gradio_app.py # Gradio UI (optional)
│── requirements.txt
│── README.md
│── images/ # Demo screenshots



 Load models (text + image)

Phi-2 for story generation

Stable Diffusion v1.5 for image creation

3. Run UI
For Gradio
python gradio_app.py



For Streamlit
streamlit run app.py


🖼️ Example Output
Theme: A robot learning to dream

Generated Story:
"In a quiet laboratory, a small robot suddenly discovered the strange warmth of dreaming..."

Generated Image:
(Stable Diffusion artwork)

🌐 Deployment Options

You can deploy this project easily on:

HuggingFace Spaces (Gradio recommended)

Streamlit Cloud

Your own server / VM

Docker container

GitHub Codespaces




💡 Future Enhancements

🎙️ Add text-to-speech narration for the story

✨ Add art styles (anime, 3D, watercolor, cyberpunk)




📜 License

This project is open-source under the MIT License.
Stable Diffusion must follow its original license guidelines.

⭐ Support

If this project helped you, please ⭐ the repository!

