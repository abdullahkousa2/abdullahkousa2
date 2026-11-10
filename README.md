<div align="center">

<img src="assets/header.svg" alt="Abdullah Kousa — AI / ML Engineer" width="100%">

<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdullahkousa)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:akousa360@gmail.com)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)](https://huggingface.co/Abdullahkousa2)
</div>

## About

I'm an AI engineer with a degree in Informatics Engineering (AI track) from Arab International University. I like the whole loop: get the data, train the model, evaluate it honestly, then put it behind an API with a demo anyone can open.

- Working across LLM fine-tuning, agents and RAG, computer vision, and classic tabular ML
- Every project below has the code, the numbers, and in most cases a live demo
- Open to junior AI / ML engineer roles, remote-friendly

## Featured work

<table>
<tr>
<td width="50%" valign="top">

### [SQLForge](https://github.com/abdullahkousa2/sqlforge)

**Fine-tuned text-to-SQL model**

QLoRA fine-tune of Qwen2.5-Coder-1.5B on a single 8 GB GPU. Scored by running the generated SQL against real databases on the full Spider dev set (1,034 questions).

📈 **57.4% → 65.6%** execution accuracy

`PyTorch` `PEFT` `QLoRA` `W&B` `FastAPI`

[![Code](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/abdullahkousa2/sqlforge)
[![Demo](https://img.shields.io/badge/Live%20demo-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/Abdullahkousa2/sqlforge)
[![Model](https://img.shields.io/badge/Model-FF9D00?style=flat-square&logo=huggingface&logoColor=white)](https://huggingface.co/Abdullahkousa2/sqlforge-qwen2.5-coder-1.5b)
[![PyPI](https://img.shields.io/pypi/v/sqlforge?style=flat-square&logo=pypi&logoColor=white&color=3775A9)](https://pypi.org/project/sqlforge/)

</td>
<td width="50%" valign="top">

### [DoorDash ETA Prediction](https://github.com/abdullahkousa2/doordash-eta-prediction)

**Delivery-time regression on real orders**

Rebuilt the ideas from DoorDash's ETA engineering blog on their public dataset of 197k orders: store embeddings, dasher-supply features, and a calibrated prediction range.

📈 **14.85 min RMSE**, 21% better than the naive baseline · p10–p90 range covers 77% of orders

`XGBoost` `PyTorch` `scikit-learn` `FastAPI`

[![Code](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/abdullahkousa2/doordash-eta-prediction)
[![Demo](https://img.shields.io/badge/Live%20demo-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/Abdullahkousa2/doordash-eta-prediction)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [AutoAnalyst](https://github.com/abdullahkousa2/autoanalyst)

**An agent that does its own data analysis**

Ask a question in plain English. The agent writes pandas code, runs it in a sandbox, reads the output, fixes its own errors, draws the chart, and answers. Streams every step live.

🛠️ Tool-calling loop · persistent sandbox · SSE streaming

`Groq` `Llama 3.3` `pandas` `FastAPI`

[![Code](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/abdullahkousa2/autoanalyst)
[![Demo](https://img.shields.io/badge/Live%20demo-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/Abdullahkousa2/autoanalyst)
[![PyPI](https://img.shields.io/pypi/v/autoanalyst?style=flat-square&logo=pypi&logoColor=white&color=3775A9)](https://pypi.org/project/autoanalyst/)

</td>
<td width="50%" valign="top">

### [CardioAI](https://github.com/abdullahkousa2/AI_Cardio-ECG)

**ECG diagnosis with visual explanations**

EfficientNetV2-S trained in three phases to sort ECG images into four cardiac classes. Every prediction comes back with a Grad-CAM heatmap showing what the model looked at.

📈 **98.61%** test accuracy on 4 classes

`PyTorch` `timm` `Grad-CAM` `FastAPI` `Docker`

[![Code](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/abdullahkousa2/AI_Cardio-ECG)
[![Demo](https://img.shields.io/badge/Live%20demo-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/Abdullahkousa2/AI-Cardio-ECG)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [PlateVision](https://github.com/abdullahkousa2/PlateVision)

**License-plate detection, tracking and OCR**

A custom-trained YOLOv8 detector feeds ByteTrack, then each plate is read eight different ways and the readings vote. Fuzzy matching and character-confusion rules clean up the result.

🛠️ Video in · annotated MP4 + CSV + JSON out

`YOLOv8` `ByteTrack` `EasyOCR` `CUDA FP16`

[![Code](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/abdullahkousa2/PlateVision)

</td>
<td width="50%" valign="top">

### [MedReport AI](https://github.com/abdullahkousa2/medreport-ai)

**Ask questions about a medical PDF**

Upload a report, ask in plain language, get an answer grounded in the document with the source passages cited. Retrieval over FAISS, generation on Groq.

🛠️ RAG with citations · `pip install medreport-ai`

`FAISS` `sentence-transformers` `Groq` `FastAPI`

[![Code](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/abdullahkousa2/medreport-ai)
[![Demo](https://img.shields.io/badge/Live%20demo-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/Abdullahkousa2/medreport-ai)
[![PyPI](https://img.shields.io/pypi/v/medreport-ai?style=flat-square&logo=pypi&logoColor=white&color=3775A9)](https://pypi.org/project/medreport-ai/)

</td>
</tr>
</table>

### More

- **[Archivist-AI](https://github.com/abdullahkousa2/archivist-ai)** — search your photo library in plain English, fully offline on CPU. [Demo](https://huggingface.co/spaces/Abdullahkousa2/archivist-ai) · [PyPI](https://pypi.org/project/archivist-ai/)
- **[Diabetes Prediction System](https://github.com/abdullahkousa2/diabetes-prediction-system)** — XGBoost ensemble with a per-patient SHAP explanation behind a REST API. [Demo](https://huggingface.co/spaces/Abdullahkousa2/Diabetes-Prediction)
- **[EventSY](https://github.com/abdullahkousa2/event-booking)** — event booking web app in Laravel and MySQL, from my backend side.

## How I work

- **I evaluate on the whole benchmark.** A 200-question sample of Spider told me SQLForge had barely improved. The full 1,034 told the real story. I don't trust small samples anymore.
- **I keep the baseline honest.** On the DoorDash data my neural net with embeddings lost to plain XGBoost (15.04 vs 14.85 min RMSE). That result is in the README, not hidden.
- **It isn't done until someone can click it.** A notebook is a draft. Finished means an API, a demo, CI, and where it makes sense a `pip install`.

## Stack

<table>
<tr><td><b>Languages</b></td><td><img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL"></td></tr>
<tr><td><b>ML / DL</b></td><td><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"> <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" alt="scikit-learn"> <img src="https://img.shields.io/badge/XGBoost-1B6FB5?style=flat-square" alt="XGBoost"> <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="pandas"></td></tr>
<tr><td><b>LLMs</b></td><td><img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black" alt="Transformers"> <img src="https://img.shields.io/badge/PEFT%20%2F%20QLoRA-FF9D00?style=flat-square" alt="PEFT / QLoRA"> <img src="https://img.shields.io/badge/RAG-7C3AED?style=flat-square" alt="RAG"> <img src="https://img.shields.io/badge/Tool%20calling-0EA5E9?style=flat-square" alt="Tool calling"> <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square" alt="FAISS"></td></tr>
<tr><td><b>Computer vision</b></td><td><img src="https://img.shields.io/badge/YOLOv8-111F68?style=flat-square" alt="YOLOv8"> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"> <img src="https://img.shields.io/badge/EfficientNet-0F766E?style=flat-square" alt="EfficientNet"></td></tr>
<tr><td><b>Serving / MLOps</b></td><td><img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI"> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"> <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions"> <img src="https://img.shields.io/badge/Weights%20%26%20Biases-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black" alt="Weights & Biases"> <img src="https://img.shields.io/badge/Gradio-F97316?style=flat-square&logo=gradio&logoColor=white" alt="Gradio"></td></tr>
<tr><td><b>Also</b></td><td><img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white" alt="Laravel"> <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL"></td></tr>
</table>

## Get in touch

The fastest way to reach me is [email](mailto:akousa360@gmail.com) or [LinkedIn](https://linkedin.com/in/abdullahkousa). If one of the demos is asleep, give it a minute to wake up. Free hosting naps.
