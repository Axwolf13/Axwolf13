# Akshay Ashok

ML engineer and applied AI researcher, currently doing my M.Sc. in Data Science & AI at Saarland University. I work across the full pipeline (dataset construction, model benchmarking, evaluation design) in NLP and computer vision, with a bias toward measurements you can reproduce and systems that know when to distrust themselves.

Saarbrücken, Germany · [axwolf13.github.io](https://axwolf13.github.io) · [akshay57ax@gmail.com](mailto:akshay57ax@gmail.com) · [LinkedIn](https://linkedin.com/in/akshay-a-ax13)

## Publication

**Real-time yoga pose estimation with a hybrid MoveNet architecture**, first-author, *Sādhanā* (Indian Academy of Sciences, Springer, 2025). A Thunder-train, Lightning-infer split that classifies 11 asanas at 98.8% test accuracy (98.4% verified on the shipped quantized model; reproduce it with `verify_model.py`) while holding 30+ FPS on consumer hardware.

[Paper (DOI)](https://doi.org/10.1007/s12046-025-02788-w) · [Code](https://github.com/Axwolf13/pose-estimation-movenet) · [Live browser demo](https://axwolf13.github.io/demo/)

## Selected work

- **[molca-reproduction](https://github.com/Axwolf13/molca-reproduction):** A reproduction of MolCA (EMNLP 2023), a language model that reads molecules both as text and as graphs. Reproduced on two machines (62.32 and 62.77 BLEU-2 against the paper's 62.0), then the experiment the paper never ran: give it one molecule's text and another molecule's graph. It describes the graph's molecule about 90% of the time. [Write-up](https://axwolf13.github.io/writing/molca/)
- **[arabic-doc-triage-research](https://github.com/Axwolf13/arabic-doc-triage-research):** Benchmarking Arabic OCR (Surya, PaddleOCR) and Arabic-to-German translation on an 8 GB laptop GPU. KITAB-Bench evaluation, confidence-based failure routing and the safety signals a triage pipeline needs before its output reaches a human decision. [Write-up](https://axwolf13.github.io/writing/arabic-ocr-benchmarks/)
- **[dodi-analysis](https://github.com/Axwolf13/dodi-analysis):** DODI, a deterministic index scoring how hard a platform's Terms of Service works to hide that "Buy now" means "revocable licence". Ten platforms across 2015–2024, checked against ToS;DR's human grades and two LLM judges, then audited and corrected in v1.1. Also runs as an MCP server, so AI agents can call the scorer as a tool. [Write-up](https://axwolf13.github.io/writing/dodi/) · [LLM-judge write-up](https://axwolf13.github.io/writing/llm-judge/)
- **[dodi-web](https://github.com/Axwolf13/dodi-web):** the DODI scorer shipped as a public web service: FastAPI app, Dockerized, test suite, CI on every push, deployed on Render. [Score any ToS live](https://dodi-web.onrender.com/)
- **[Shadow-Correction-DaS-Project](https://github.com/Axwolf13/Shadow-Correction-DaS-Project):** Quantitative study of piracy as a market signal for the Data and Society seminar.

## Writing

Long-form write-ups of benchmarks and reproductions live at [axwolf13.github.io/writing](https://axwolf13.github.io/writing/), published when there's something real to show. When I find a mistake in one, I correct it in public.

Open to a Master's thesis topic from late 2027, research collaborations and conversations about evaluating models and agents.
