# DiabetesLLM

## Project Structure

### Language Model
- **Base Model**: **Mistral-7B** — an efficient, decoder-only transformer.
- **Features**:
  - **Sliding Window Attention (SWA)** for faster processing.
  - **Grouped-Query Attention (GQA)** for better memory efficiency.

### Data Collection
- Collected over **1,500+ diabetes-specific Q&A pairs**.

### Fine-Tuning
- Fine-tuned using **LoRA (Low-Rank Adaptation)** for efficient training.
- Focused on:
  - Diabetes types
  - Management strategies
  - Medications
  - Lifestyle changes
  - Complications

---

## How to Run the Project
0. Download the UI folder and open the index file on your browser (if this doesn't work try the following steps).
1. Open the Python notebook on **Google Colab**.
2. Run all the code (**Runtime > Run all**).
3. Upload the **checkpoint zip file** when prompted.
4. Click the generated link at the end of the notebook to access the **chatbot**.

---
