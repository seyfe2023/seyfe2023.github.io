# LLM vs. LLM+KG Skill Extraction

This project compares two pipelines for extracting professional skills from resumes:

- **LLM-Only**: Extracts skills using LLaMA 3.3-70B without few-shot prompting.
- **LLM+KG**: Enhances extraction with ESCO-guided prompting and few-shot examples 

## Objective

Evaluate how ESCO knowledge graph integration impacts precision, recall, and F1-score in skill extraction across multiple job categories.

## Tools Used

- Python · Pandas · Hugging Face Transformers · LLaMA 3.3-70B (via SambaNova)  
- ResumeAtlas dataset · ESCO ontology

## Structure

- `llm_only/` – Baseline LLM pipeline  
- `llm_esco_guided/` – ESCO-augmented prompting pipeline  
- `evaluation/` – Mapping, metrics, and results

## 📊 Metrics

Performance compared using ground truth ESCO skills with:
- Exact & fuzzy matching
- Per-resume precision, recall, and F1-score

