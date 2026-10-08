<h1 align="center">Sergio Jiménez Cubas</h1>
<h3 align="center">AI Engineer · LLMs, RAG & Computer Vision</h3>
<p align="center">📍 Madrid, Spain</p>

<p align="center">
  <a href="https://www.linkedin.com/in/sergio-jimenez-cubas"><img src="https://img.shields.io/badge/LinkedIn-sergio--jimenez--cubas-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:sergiojimenezcubas@gmail.com"><img src="https://img.shields.io/badge/Email-sergiojimenezcubas%40gmail.com-D14836?logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/serjim06"><img src="https://img.shields.io/badge/GitHub-serjim06-181717?logo=github&logoColor=white" alt="GitHub"></a>
  <a href="Sergio_Jimenez_Cubas_CV.pdf"><img src="https://img.shields.io/badge/CV-Download%20PDF-2E7D32?logo=readdotcv&logoColor=white" alt="Download CV (PDF)"></a>
</p>

---

## About me

Computer Engineering graduate from **Complutense University of Madrid (UCM)**, currently pursuing a **Master's Degree in Artificial Intelligence**. I'm especially interested in **Computer Vision**, **Natural Language Processing** and **Evolutionary Computation**, and in applying them to real-world problems.

I have hands-on experience building **end-to-end AI software**: custom **RAG platforms**, **MCP servers** for natural-language access to data, and AI-powered apps backed by **Azure OpenAI** and **Azure Speech**.

- 🎓 Master's Degree in Artificial Intelligence — Universidad Europea (2026 – 2027)
- 💼 Previously Intern at Esferize Comunicaciones
- 🔭 Currently building an end-to-end receipt OCR system in PyTorch
- 🌍 Spanish (native) · English (B2)

---

## Experience

**Intern — Esferize Comunicaciones SL** · *Feb 2026 – Aug 2026*

- Built a **self-hosted RAG platform**  indexing ~40k documents from 4 internal sources (wikis, ticketing, GitLab, SharePoint), with incremental sync, hybrid retrieval and reranking, exposed as a MCP server for AI-assisted, source-cited Q&A.
- Designed and implemented an **MCP server** enabling natural-language querying over a database.
- Developed a **Microsoft Teams app** that provides real-time transcription and automatically generates meeting minutes.
- Built a mobile app with **React Native + Expo** and a **Python / FastAPI** backend, integrating **Azure OpenAI** and **Azure Speech** for speech-to-text and automated technical report generation.

---

## Featured Projects

### [Federated Learning Platform for Tabular Data](https://github.com/serjim06/TFG-FederatedLearning) — *Bachelor's Thesis (grade: 9.5/10)*

Desktop application to create, run and analyze **federated learning** experiments on tabular data: models are trained across distributed nodes **without centralizing the data**.

- Classification and regression with user-defined **PyTorch** models.
- Four aggregation strategies: **FedAvg**, **FedMedian**, **SCAFFOLD** (client-drift correction) and [**SSFed**](https://thesai.org/Publications/ViewPaper?Volume=16&Issue=3&Code=IJACSA&SerialNo=112) (significance-based weighting, Alsenani, IJACSA 2025).
- Federated simulation with **Flower + Ray**, launched straight from the GUI.
- Per-round metrics, **PDF report** generation, result validation workflow and prediction with the global model.
- Layered, **hexagonal-inspired architecture**, user/role management and a **pytest** suite running on **GitHub Actions CI**.

`Python` `PyTorch` `Flower` `Ray` `scikit-learn` `SQLite` `Tkinter` `pytest` `GitHub Actions`

### [Ticket Viewer — End-to-End Receipt OCR](https://github.com/serjim06/ticket-viewer) — *in progress*

OCR system that turns photos of purchase receipts into **structured JSON** (vendor, date, item, total).

- **CRNN** (CNN + 3-layer bidirectional LSTM) trained with **CTC Loss** on the **ICDAR2019-SROIE** dataset (4.2% CER / 85.6% word accuracy).
- Automated data pipeline: dataset download, per-word cropping, label cleaning and vocabulary extraction in one step.
- Configurable training CLI and inference on single images, lists or glob patterns.
- **Next:** U-Net text detector (heatmap → bounding boxes), full detection + recognition pipeline and rule-based key information extraction.

`Python` `PyTorch` `Computer Vision` `OCR` `CRNN` `CTC`

### [ImageGen — Evolutionary Art Generation](https://github.com/serjim06/ImageGen)

Generates artistic images of a target genre (landscape, portrait, abstract, still life… 14 genres) with an **evolutionary algorithm** whose fitness is computed by a **fine-tuned ResNet18** art-genre classifier.

- Individuals encoded as sets of geometric primitives (generic polygons and **Bézier curves**) decoded into images.
- Custom mutation and crossover operators, tournament selection, configurable via CLI (generations, population, rates, max shapes).
- Combines **evolutionary computation** with **deep learning** as a learned aesthetic evaluator.

`Python` `PyTorch` `ResNet18` `LEAP` `OpenCV` `Evolutionary Algorithms`

---

## Tech Stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=mysql&logoColor=white)

**AI / ML**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Flower](<https://img.shields.io/badge/Flower-Federated%20Learning-F2B705>)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Azure OpenAI](<https://img.shields.io/badge/Azure%20OpenAI-0078D4?logo=microsoftazure&logoColor=white>)
![RAG](https://img.shields.io/badge/RAG-Hybrid%20Search-6A1B9A)
![MCP](https://img.shields.io/badge/MCP-FastMCP-000000)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?logo=qdrant&logoColor=white)

**Technologies**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white)
![Microsoft Azure](<https://img.shields.io/badge/Microsoft%20Azure-0078D4?logo=microsoftazure&logoColor=white>)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white)

---

## Education

| Period       | Degree                                     | Institution                      |
| ------------ | ------------------------------------------ | -------------------------------- |
| 2026 – 2027 | Master's Degree in Artificial Intelligence | Universidad Europea              |
| 2022 – 2026 | B.Sc. in Computer Engineering              | Complutense University of Madrid |

---

<p align="center">
  📫 Open to <b>AI / ML Engineering</b> opportunities — feel free to reach out via <a href="https://www.linkedin.com/in/sergio-jimenez-cubas">LinkedIn</a> or <a href="mailto:sergiojimenezcubas@gmail.com">email</a>.
</p>
