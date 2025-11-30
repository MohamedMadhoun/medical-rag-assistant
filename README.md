# Medical RAG Agent 🩺

A **Retrieval-Augmented Generation (RAG) system** for symptom-based disease prediction. This agent helps provide structured, reliable medical diagnosis suggestions based on user-provided symptoms and internal medical datasets.

---

## 🚀 Features

* **Symptom-Based Diagnosis**: Accepts a list of user symptoms and returns a structured diagnosis in JSON format.
* **Retrieval-Augmented**: Uses an internal medical knowledge base for context instead of relying solely on general LLM knowledge.
* **Confidence Scoring**: Provides a confidence level (`High`, `Medium`, `Low`) based on symptom matching.
* **LangChain + LangGraph**: Efficient decision-making workflow with document grading and query refinement.

---


## 🧠 Usage

* Enter symptoms in the input box.
* Click **Send** to get a structured diagnosis in JSON.
* Download the report using the **Download Reports JSON** button.

Example output:

```json
{
  "Disease": "Common Cold",
  "Key_Symptoms": ["Sneezing", "Runny Nose", "Fever"],
  "Description": "A viral infectious disease of the upper respiratory tract.",
  "Precautions": ["Rest", "Hydration", "Avoid contact with others"],
  "Confidence_Level": "High"
}
```

---

## 📌 Notes

* Ensure your CSV files are in the correct paths (`dataset.csv`, `symptom_precaution.csv`, `symptom_Description.csv`).
* The app is designed for **educational purposes** and **should not replace professional medical advice**.

---

## 📝 Author

**Mohammed Madhoun** – Computer Systems Engineer | AI & ML Enginner
[GitHub](https://github.com/MohamedMadhoun)
