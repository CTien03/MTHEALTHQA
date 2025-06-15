# 🧠 MTHEALTHQA: Multilingual Mental Health QA Dataset

## 📌 Dataset Summary

**MTHEALTHQA** is a high-quality multilingual dataset containing expert-derived **question-answer (QA)** pairs in **Vietnamese, French, English**, and **Korean**, focused on **mental health**. Each QA pair is grounded in trustworthy medical and psychological documents. The dataset is structured for **training, validation, and testing** in each language.

It aims to foster research in:

- 🔎 Multilingual Open-domain Question Answering  
- 🌐 Cross-lingual Transfer in Mental Health  
- 🖼️ Multimodal QA *(future extension)*  
- 🧠 Health-oriented Natural Language Understanding  

---

## 🗣️ Supported Languages

- 🇻🇳 Vietnamese (`vi`)  
- 🇫🇷 French (`fr`)  
- 🇰🇷 Korean (`ko`)  
- 🇬🇧 English (`en`)  

---

## 🏗️ Dataset Structure

Each `.xlsx` file includes the following columns:

| Column Name | Description |
|-------------|-------------|
| `STT`       | Unique index |
| `id`        | Unique identifier (e.g., `fr_0003`) |
| `question`  | The mental health-related question |
| `answer`    | Expert-derived answer |
| `context`   | Supporting extract from the source document |

### 🔍 Example Entry:

```json
{
  "id": "fr_0003",
  "question": "Comment gérer les crises de panique ?",
  "answer": "Les crises de panique peuvent être gérées avec des techniques de respiration, de pleine conscience et, dans certains cas, par la thérapie ou la médication.",
  "source": "guide_anxiete_fr.pdf"
}
