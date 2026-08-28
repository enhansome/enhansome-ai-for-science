# Awesome ai for science with stars

<div align="center">
  <h1>✨ Awesome AI for Science (AI4Science) ✨</h1>

  <img src="assets/banner.jpg" alt="Awesome AI for Science Banner" width="100%">

  <p align="center">
    A curated list of awesome AI tools, libraries, papers, datasets, and frameworks that accelerate <strong>scientific discovery</strong> across all disciplines.
  </p>

  <!-- Keep these links. Translations will automatically update with the README. -->

  <p align="center">
    <a href="https://zdoc.app/de/ai-boost/awesome-ai-for-science">Deutsch</a> | 
    <a href="https://zdoc.app/en/ai-boost/awesome-ai-for-science">English</a> | 
    <a href="https://zdoc.app/es/ai-boost/awesome-ai-for-science">Español</a> | 
    <a href="https://zdoc.app/fr/ai-boost/awesome-ai-for-science">français</a> | 
    <a href="https://zdoc.app/ja/ai-boost/awesome-ai-for-science">日本語</a> | 
    <a href="https://zdoc.app/ko/ai-boost/awesome-ai-for-science">한국어</a> | 
    <a href="https://zdoc.app/pt/ai-boost/awesome-ai-for-science">Português</a> | 
    <a href="https://zdoc.app/ru/ai-boost/awesome-ai-for-science">Русский</a> | 
    <a href="https://zdoc.app/zh/ai-boost/awesome-ai-for-science">中文</a>
  </p>

  <p align="center">
    <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
    <a href="https://opensource.org/license/MIT"><img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT"></a>
    <a href="https://github.com/ai-boost/awesome-ai-for-science"><img src="https://img.shields.io/github/stars/ai-boost/awesome-ai-for-science.svg?style=social&label=Star" alt="GitHub stars"></a>
    <a href="https://github.com/ai-boost/awesome-ai-for-science"><img src="https://img.shields.io/github/forks/ai-boost/awesome-ai-for-science.svg?style=social&label=Fork" alt="GitHub forks"></a>
  </p>
</div>

> AI is revolutionizing scientific research - from drug discovery and materials design to climate modeling and astrophysics. This repository collects the best resources to help researchers leverage AI in their work.

## 📚 Contents

* [🧪 AI Tools for Research](#-ai-tools-for-research)
* [📄 Paper→Poster / Slides / Graphical Abstract](#-paperposter--slides--graphical-abstract)
* [📊 Chart Understanding & Generation](#-chart-understanding--generation)
* [🔄 Paper-to-Code & Reproducibility](#-paper-to-code--reproducibility)
* [📋 Scientific Documentation & Parsing](#-scientific-documentation--parsing)
* [🧰 Research Workbench & Plugins](#-research-workbench--plugins)
* [🕸 Knowledge Extraction & Scholarly KGs](#-knowledge-extraction--scholarly-kgs)
* [🤖 Research Agents & Autonomous Workflows](#-research-agents--autonomous-workflows)
* [🏷 Data Labeling & Curation](#-data-labeling--curation)
* [⚗ Scientific Machine Learning](#-scientific-machine-learning)
* [📖 Papers & Reviews](#-papers--reviews)
* [🔬 Domain-Specific Applications](#-domain-specific-applications)
  * [🧬 Biology & Medicine](#-biology--medicine)
  * [⚛ Chemistry & Materials](#-chemistry--materials)
  * [🌌 Physics & Astronomy](#-physics--astronomy)
  * [🌍 Earth & Climate Science](#-earth--climate-science)
  * [🌾 Agriculture & Ecology](#-agriculture--ecology)
  * [🧠 Social Sciences](#-social-sciences)
  * [🏗 Engineering & Built Environment](#-engineering--built-environment)
* [🤖 Foundation Models for Science](#-foundation-models-for-science)
* [📈 Datasets & Benchmarks](#-datasets--benchmarks)
* [💻 Computing Frameworks](#-computing-frameworks)
* [🎓 Educational Resources](#-educational-resources)
* [🏛 Research Communities](#-research-communities)
* [📚 Related Awesome Lists](#-related-awesome-lists)

***

## 🧪 AI Tools for Research

### Literature & Knowledge Management

* [paper-search-mcp](https://github.com/openags/paper-search-mcp) ⭐ 2,511 | 🐛 53 | 🌐 Python | 📅 2026-08-17 - MCP server, CLI, and agent skills for searching and downloading academic papers from multiple open sources (arXiv, PubMed, bioRxiv, Semantic Scholar, OpenAlex, CORE, Europe PMC, etc.) with unified, deduplicated, LLM-friendly retrieval and an OA-first download fallback chain (OpenAGS, 1.9K+ stars, MIT License, 2025)
* [PaSa (ByteDance)](https://github.com/bytedance/pasa) ⭐ 1,651 | 🐛 25 | 🌐 Python | 📅 2025-05-27 - Advanced paper search agent powered by large language models, autonomously invoking search tools, reading papers, and selecting references to deliver comprehensive and accurate results for complex scholarly queries (1.5K+ stars, Apache 2.0, 2024)
* [Semantic Scholar](https://www.semanticscholar.org/) - AI-powered academic search (Allen AI)
* [arXiv](https://arxiv.org/) - Open-access repository of electronic preprints and postprints
* [OpenAlex](https://openalex.org/) - Open catalog of scholarly papers and authors
* [CORE](https://core.ac.uk/) - Aggregator of open access research papers
* [Connected Papers](https://www.connectedpapers.com/) - AI-powered visual graph for exploring academic papers and discovering connected research through citation networks and semantic similarity

### Data Analysis & Visualization

* [PandasAI](https://github.com/Sinaptik-AI/pandas-ai) ⭐ 23,774 | 🐛 22 | 🌐 Python | 📅 2025-10-28 - Conversational data analysis using natural language
* [DeepAnalyze](https://github.com/ruc-datalab/DeepAnalyze) ⭐ 4,569 | 🐛 23 | 🌐 Python | 📅 2026-08-28 - First agentic LLM for autonomous data science with end-to-end pipeline from data to analyst-grade reports
* [AutoViz](https://github.com/AutoViML/AutoViz) ⭐ 1,899 | 🐛 2 | 🌐 Python | 📅 2024-06-10 - Automated data visualization with minimal code
* [Chat2Plot](https://github.com/nyanp/chat2plot) ⭐ 281 | 🐛 8 | 🌐 Python | 📅 2023-11-19 - Secure text-to-visualization through standardized chart specifications

### Data Labeling & Annotation

* [Label Studio](https://github.com/heartexlabs/label-studio) ⭐ 28,164 | 🐛 927 | 🌐 TypeScript | 📅 2026-08-28 - Multi-type data labeling and annotation tool
* [Snorkel](https://github.com/snorkel-team/snorkel) ⭐ 6,003 | 🐛 19 | 🌐 Python | 📅 2026-06-08 - Programmatic data labeling and weak supervision

### Research Workbench & Plugins

* [Claude Scientific Skills](https://github.com/K-Dense-AI/claude-scientific-skills) ⭐ 35,640 | 🐛 11 | 🌐 Python | 📅 2026-08-24 - Comprehensive collection of 125+ ready-to-use scientific skill modules for Claude AI across bioinformatics, cheminformatics, clinical research, ML, and materials science
* [Scientific Agent Skills](https://github.com/K-Dense-AI/scientific-agent-skills) ⭐ 35,640 | 🐛 11 | 🌐 Python | 📅 2026-08-24 - Turn any AI agent into an AI Scientist. The #1 Agent Skills library for science with 140+ ready-to-use skills and 100+ scientific databases covering biology, chemistry, medicine, and drug discovery. Compatible with Cursor, Claude Code, Codex, Antigravity, and the open Agent Skills standard (K-Dense-AI, 26K+ stars, 2025)
* [GDM Science Skills](https://github.com/google-deepmind/science-skills) ⭐ 2,780 | 🐛 0 | 🌐 Python | 📅 2026-07-07 - Google DeepMind's official collection of agentic science skills accelerating scientific workflows with better grounding and higher token efficiency, integrating insights from AlphaGenome, AFDB, UniProt and 30+ other databases and tools (2026)
* [Medical Research Skills](https://github.com/aipoch/medical-research-skills) ⭐ 1,771 | 🐛 5 | 🌐 Python | 📅 2026-07-15 - Curated library of 550+ medical research agent skills spanning evidence insights, protocol design, omics/clinical data analysis, and academic writing; each skill is reviewed through MedSkillAudit and compatible with Claude Code, Codex, Open Code, OpenClaw, and SKILL.md-compatible agents (AIPOCH, 1.2K+ stars, MIT License, 2026)
* [bioSkills](https://github.com/GPTomics/bioSkills) ⚠️ Archived - Collection of SKILLS.md guiding AI coding agents (Claude Code, OpenAI Codex, Google Gemini, OpenCode, OpenClaw) through common bioinformatics workflows from basic sequence manipulation to advanced analyses such as single-cell RNA-seq and population genetics; evaluated on the Bio-Task Bench dataset (GPTomics, 969+ stars, MIT License, 2026)
* [SciAgent-Skills](https://github.com/jaechang-hits/SciAgent-Skills) ⭐ 347 | 🐛 7 | 🌐 Python | 📅 2026-08-27 - 197 bioinformatics and life science skills for Claude Code and AI agents, achieving 92.0% accuracy on BixBench. Covers RNA-seq, single-cell analysis, drug discovery, proteomics, and more. Powers OmicsHorizon (195+ stars, 2026)

***

## 📄 Paper→Poster / Slides / Graphical Abstract

### Poster Generation

* [Paper2Poster](https://github.com/Paper2Poster/Paper2Poster) ⭐ 3,925 | 🐛 27 | 🌐 Python | 📅 2026-06-08 - Multi-agent system with Parser-Planner-Painter architecture converting `paper.pdf` to editable `poster.pptx`, outperforms GPT-4o with 87% fewer tokens
* [mPLUG-PaperOwl](https://github.com/X-PLUG/mPLUG-DocOwl) ⭐ 2,411 | 🐛 73 | 🌐 Python | 📅 2025-05-30 - Multimodal LLM for scientific charts and diagrams understanding/generation

### Slides & Presentation Generation

* [PPTAgent](https://github.com/icip-cas/PPTAgent) ⭐ 4,959 | 🐛 12 | 🌐 Python | 📅 2026-08-24 - Beyond text-to-slides generation with PPTEval multi-dimensional evaluation (EMNLP 2025)
* [SlideDeck AI](https://github.com/barun-saha/slide-deck-ai) ⭐ 373 | 🐛 15 | 🌐 Python | 📅 2026-08-15 - Co-create PowerPoint presentations with Generative AI from documents or topics
* [paper2slides](https://github.com/takashiishida/paper2slides) ⭐ 93 | 🐛 1 | 🌐 Python | 📅 2026-03-17 - Transform arXiv papers into Beamer slides using LLMs
* [AI Multi-Agent Presentation Builder](https://github.com/Azure-Samples/ai-multi-agent-presentation-builder) ⭐ 52 | 🐛 13 | 🌐 Python | 📅 2026-02-11 - Azure Semantic Kernel multi-agent PPT generation reference
* [pdf2slides](https://github.com/ha0ranyu/pdf2slides) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2024-08-17 - Convert PDF files into editable slides with three lines of code
* [PaperToSlides](https://github.com/jxtse/PaperToSlides) ⭐ 16 | 🐛 1 | 🌐 Python | 📅 2025-05-03 - AI-powered tool that automatically converts academic papers (PDF) into presentation slides
* [Auto-Slides](https://auto-slides.github.io/) - Multi-agent academic paper to high-quality presentation slides with interactive refinement

### Video & Media Generation

* [Paper2Video](https://github.com/showlab/Paper2Video) ⭐ 2,369 | 🐛 4 | 🌐 Python | 📅 2026-03-05 - First benchmark for automatic video generation from scientific papers (NeurIPS 2025)
* [paper2video](https://github.com/mett29/paper2video) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2024-08-26 - Transform arXiv research papers into engaging presentations and YouTube-ready videos

### Website & Interactive Content Generation

* [Paper2All](https://github.com/YuhangChen1/Paper2All) ⭐ 385 | 🐛 5 | 🌐 Python | 📅 2025-10-24 - AI-powered pipeline converting papers into interactive websites, posters, and multimedia presentations with "Let's Make Your Paper Alive!" philosophy

### Figure & Illustration Generation

* [PaperBanana](https://github.com/dwzhu-pku/PaperBanana) ⭐ 7,009 | 🐛 18 | 🌐 Python | 📅 2026-06-25 - Automated academic illustration generation for AI scientists, converting research papers into publication-ready figures using VLMs and diffusion models with iterative refinement (PKU & Google Research, 6.2K+ stars, 2026)

### Chart & Visualization Generation

*Note: For comprehensive chart understanding and code generation tools, see [📊 Chart Understanding & Generation](#-chart-understanding--generation) section*

***

## 📊 Chart Understanding & Generation

### Chart-to-Code & Reproducibility

* [ChartAssistant / ChartAst (ACL 2024)](https://github.com/OpenGVLab/ChartAst) ⭐ 136 | 🐛 9 | 🌐 Python | 📅 2024-09-07 - Universal chart comprehension and reasoning model
* [Chart-to-Text Datasets](https://github.com/vis-nlp/Chart-to-text) ⭐ 129 | 🐛 13 | 🌐 OpenEdge ABL | 📅 2024-07-14 - Large-scale chart summarization datasets for training chart description capabilities
* [ChartCoder (ACL 2025)](https://aclanthology.org/2025.acl-long.363/) - Multimodal LLM for chart-to-code generation, 7B model outperforms larger open-source MLLMs

### Scientific Visualization Tools

* [Flint (Microsoft)](https://github.com/microsoft/flint-chart) ⭐ 4,028 | 🐛 23 | 🌐 TypeScript | 📅 2026-08-27 - Visualization intermediate language that lets AI agents create expressive, polished charts from simple, human-editable specs, compiling the same input to 30+ chart types across Vega-Lite, ECharts, and Chart.js with an MCP server for agent integration (1.9K+ stars, MIT License, 2026)
* [AutoViz](https://github.com/AutoViML/AutoViz) ⭐ 1,899 | 🐛 2 | 🌐 Python | 📅 2024-06-10 - Automated data visualization with minimal code
* [Chat2Plot](https://github.com/nyanp/chat2plot) ⭐ 281 | 🐛 8 | 🌐 Python | 📅 2023-11-19 - Secure text-to-visualization through standardized chart specifications
* [PlotlyAI](https://plotly.com/ai/) - AI-powered data visualization and dashboard creation

***

## 🔄 Paper-to-Code & Reproducibility

### Automated Code Generation

* [Paper2Code](https://github.com/going-doer/Paper2Code) ⭐ 4,930 | 🐛 15 | 🌐 Python | 📅 2026-03-25 - Automated code generation from machine learning research papers into runnable implementations (4.5K+ stars, 2025)
* [Paper2Agent](https://github.com/jmiao24/Paper2Agent) ⭐ 2,339 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-02-10 - Multi-agent system automatically transforming research papers into interactive AI agents with MCP server generation, tutorial auto-detection, and benchmark extraction (2.2K+ stars, MIT License, 2025)
* [AutoP2C](https://arxiv.org/abs/2504.20115) - LLM agent framework generating runnable repositories from academic papers
* [ResearchCodeAgent](https://arxiv.org/abs/2504.20117) - Multi-agent system for automated codification of research methodologies
* [ToolMaker](https://huggingface.co/papers/2502.11705) - Convert papers with code into callable agent tools

### Experiment Automation

* [BioProBench](https://huggingface.co/datasets/GreatCaptainNemo/BioProBench) - Comprehensive benchmark for automatic evaluation of LLMs on biological protocols and procedural understanding
* [Alhazen](https://chanzuckerberg.github.io/alhazen/) - Extract experimental metadata and protocol information from scientific documents

***

## 📋 Scientific Documentation & Parsing

### High-Performance Document Processing

* [PaddleOCR 3.0 (2024/2025)](https://github.com/PaddlePaddle/PaddleOCR) ⭐ 88,386 | 🐛 235 | 🌐 Python | 📅 2026-07-22 - Advanced OCR with PP-StructureV3 document parsing, 13% accuracy improvement, supports 80+ languages
* [MinerU (2024/2025)](https://github.com/opendatalab/MinerU) ⭐ 78,675 | 🐛 103 | 🌐 Python | 📅 2026-08-28 - SOTA multimodal document parsing with 1.2B parameters outperforming GPT-4o, converts PDFs to LLM-ready Markdown/JSON
* [Marker](https://github.com/datalab-to/marker) ⭐ 39,341 | 🐛 460 | 🌐 Python | 📅 2026-08-27 - High-accuracy PDF→Markdown/JSON/HTML conversion, specialized for tables/formulas/code blocks with benchmark scripts
* [OpenDataLoader PDF (OpenDataLoader, 2025)](https://github.com/opendataloader-project/opendataloader-pdf) ⭐ 28,844 | 🐛 78 | 🌐 Java | 📅 2026-08-28 - Open-source PDF parser for AI-ready data, converting PDFs into Markdown/JSON/HTML/Tagged PDF with layout analysis and reading-order detection; ranks #1 overall on extraction benchmarks with deterministic bounding boxes and hybrid AI mode (26K+ stars, Apache 2.0)
* [olmOCR (AllenAI)](https://github.com/allenai/olmocr) ⭐ 19,398 | 🐛 88 | 🌐 Python | 📅 2026-03-25 - Toolkit for linearizing academic PDFs into LLM-ready text with high accuracy and structure preservation, optimized for scientific literature extraction
* [Unstructured](https://github.com/Unstructured-IO/unstructured) ⭐ 15,356 | 🐛 296 | 🌐 HTML | 📅 2026-08-28 - Production-grade ETL for transforming complex documents into structured formats, with open-source API
* [Nougat (Meta AI)](https://github.com/facebookresearch/nougat) ⭐ 10,065 | 🐛 142 | 🌐 Python | 📅 2025-02-21 - Neural optical understanding for academic documents, transforms scientific PDFs to Markdown with mathematical formula support
* [PDF-Extract-Kit (2024)](https://github.com/opendatalab/PDF-Extract-Kit) ⭐ 10,000 | 🐛 107 | 🌐 Python | 📅 2025-01-03 - Comprehensive toolkit for high-quality PDF content extraction with layout detection, formula recognition, and OCR
* [GROBID](https://github.com/kermitt2/grobid) ⭐ 5,109 | 🐛 305 | 🌐 Java | 📅 2026-08-27 - Machine learning software for extracting structured metadata from scholarly documents
* [Science-Parse / SPv2 (AllenAI)](https://github.com/allenai/science-parse) ⭐ 703 | 🐛 28 | 🌐 Java | 📅 2024-05-26 - Parse scientific papers to structured fields (title/author/sections/references)
* [MinerU-Diffusion (OpenDataLab, ECCV 2026)](https://github.com/opendatalab/MinerU-Diffusion) ⭐ 615 | 🐛 9 | 🌐 Python | 📅 2026-06-18 - Diffusion-based document OCR framework replacing autoregressive decoding with block-level parallel diffusion decoding, enabling high-accuracy text recognition in scientific PDFs (613+ stars, MIT License)
* [S2ORC doc2json (AllenAI)](https://github.com/allenai/s2orc-doc2json) ⭐ 475 | 🐛 13 | 🌐 Python | 📅 2024-04-11 - Large-scale PDF/LaTeX/JATS parsing to standardized JSON for millions of papers
* [Docling (IBM, AAAI 2025)](https://research.ibm.com/publications/docling-an-efficient-open-source-toolkit-for-ai-driven-document-conversion) - Multi-format (PDF/DOCX/PPTX/HTML/Images) → structured data (Markdown/JSON) with layout reconstruction, table/formula recovery

### Production Pipelines & Data Preparation

* [Mozilla document-to-markdown](https://github.com/mozilla-ai/document-to-markdown) ⭐ 52 | 🐛 0 | 📅 2025-06-13 - Docling-powered parsing with UI/CLI demonstration for rapid prototyping
* [IBM Data Prep Kit: PDF→Parquet](https://ibm.github.io/data-prep-kit/transforms/language/pdf2parquet/) - Large-scale scientific document ingestion pipeline with optimization configurations

### Figure & Table Extraction

* [TableBank](https://github.com/doc-analysis/TableBank) ⭐ 1,084 | 🐛 30 | 📅 2024-08-12 - Large-scale table detection and recognition dataset with pre-trained models
* [PDFFigures2](https://github.com/allenai/pdffigures2) ⭐ 755 | 🐛 35 | 🌐 Scala | 📅 2024-03-10 - Extract figures, tables, captions, and section titles from scholarly PDFs

### Scientific Text Processing & NLP

* [scispacy (AllenAI)](https://github.com/allenai/scispacy) ⭐ 1,988 | 🐛 56 | 🌐 Python | 📅 2025-12-04 - Full spaCy pipeline and models for scientific/biomedical documents, enabling named entity recognition, abbreviation resolution, and UMLS linking for scientific literature mining (1.9K+ stars, Apache 2.0)

### Scientific Literature RAG & Analysis

* [STORM](https://github.com/stanford-oval/storm) ⭐ 31,146 | 🐛 107 | 🌐 Python | 📅 2025-09-30 - LLM agent system synthesizing Wikipedia-like long-form research articles from scratch through multi-perspective question asking, web retrieval, and citation-grounded report generation, with Co-STORM extension for collaborative human-LLM knowledge curation conversations (Stanford OVAL, NAACL 2024 & EMNLP 2024)
* [PaperQA2](https://github.com/future-house/paper-qa) ⭐ 9,115 | 🐛 144 | 🌐 Python | 📅 2026-08-26 - High-accuracy RAG for scientific PDFs with citation support, agentic RAG, and contradiction detection
* [OpenScholar](https://github.com/AkariAsai/OpenScholar) ⭐ 1,584 | 🐛 11 | 🌐 Python | 📅 2025-08-13 - Retrieval-augmented LM synthesizing scientific literature from 45M papers with human-expert-level citation accuracy, outperforming GPT-4o by 5% on ScholarQABench (Nature 2026, UW & Ai2)
* [paper-reviewer](https://github.com/deep-diver/paper-reviewer) ⭐ 848 | 🐛 3 | 🌐 Python | 📅 2025-02-20 - Generate comprehensive reviews from arXiv papers and convert to blog posts
* [Valsci](https://github.com/bricee98/Valsci) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2026-06-29 - Self-hostable scientific claim-verification and literature-review tool combining Semantic Scholar retrieval, bibliometric scoring, and LLM-based evidence synthesis for large-batch validation workflows

***

## 🧰 Research Workbench & Plugins

### Interactive Research Environments

* [Academic Research Skills (ARS)](https://github.com/Imbad0202/academic-research-skills) ⭐ 44,035 | 🐛 18 | 🌐 Python | 📅 2026-08-27 - Comprehensive Claude Code skill suite covering the full academic pipeline from deep research and paper writing to multi-perspective peer review, revision, and finalization; features multi-agent teams, PRISMA systematic review, style calibration, claim-level citation audits, integrity gates, and human-in-the-loop safeguards (38K+ stars, CC BY-NC 4.0, 2026)
* [SkillOpt (Microsoft, 2026)](https://github.com/microsoft/SkillOpt) ⭐ 16,428 | 🐛 34 | 🌐 Python | 📅 2026-08-26 - Text-space optimizer that treats agent skill documents as trainable parameters for frozen LLMs, using scored rollouts and held-out validation gates to iteratively improve reusable natural-language skills; includes SkillOpt-Sleep for nightly self-evolution and improves accuracy across Claude Code, Codex, Copilot, and direct-chat harnesses, making it a meta-tool for evolving scientific agent skill workflows (15.5K+ stars, MIT License, PyPI)
* [Claude Scholar](https://github.com/Galaxy-Dawn/claude-scholar) ⭐ 5,242 | 🐛 3 | 🌐 Python | 📅 2026-08-27 - Semi-automated research assistant for academic research and software development, supporting Claude Code, Codex CLI, Kimi Code CLI, and OpenCode across ideation, coding, experiments, writing, and publication (Galaxy-Dawn, 4.5K+ stars, MIT License, 2026)
* [Jupyter AI (JupyterLab Extension)](https://github.com/jupyterlab/jupyter-ai) ⭐ 4,384 | 🐛 301 | 🌐 Python | 📅 2026-08-28 - Official Jupyter extension with `%%ai` magic commands and sidebar chat assistant, connecting multiple model providers and local inference
* [OpenScience (Synthetic Sciences)](https://github.com/synthetic-sciences/openscience) ⭐ 3,349 | 🐛 15 | 🌐 TypeScript | 📅 2026-08-28 - Open-source AI workbench for scientific research that automates the full research loop — literature review, hypothesis generation, code writing, experiment execution, database querying, and report writing — with 290+ skills, specialized research agents, and a browser-based workspace (1453+ stars, Apache 2.0, 2026)
* [Open Science (AIPOCH)](https://github.com/aipoch/open-science) ⭐ 3,263 | 🐛 37 | 🌐 TypeScript | 📅 2026-08-28 - Open-source, local-first, model-agnostic AI research workbench for reproducible scientific discovery; runs Python/R notebooks, searches the web, calls scientific data connectors, and produces inspectable reports, tables, and figures in a self-hosted desktop workspace (1.5K+ stars, Apache 2.0, 2026)
* [open-science](https://github.com/ai4s-research/open-science) ⭐ 1,497 | 🐛 25 | 🌐 TypeScript | 📅 2026-08-28 - Local-first, open-source AI workbench for scientists — an open alternative to Claude Science (by ai4s-research, maintainers of this list; TypeScript, MIT, 2026)
* [OpenBioMed](https://github.com/PharMolix/OpenBioMed) ⭐ 1,103 | 🐛 38 | 🌐 Python | 📅 2026-07-22 - Open-source biomedical AI platform integrating multimodal foundation models (BioMedGPT, PharmolixFM, LangCell) with agentic workflows and 45+ Claude Code skills for drug discovery, protein engineering, and single-cell omics analysis (PharMolix & Tsinghua AIR, 1K+ stars, 2023-2026)
* [K-Dense BYOK](https://github.com/K-Dense-AI/k-dense-byok) ⭐ 1,066 | 🐛 3 | 🌐 TypeScript | 📅 2026-08-27 - Free, open-source desktop AI research assistant that runs locally and turns natural-language requests into real data analysis, literature search, figure generation, and manuscript review; ships with 149 scientific skills, 326 workflow templates, and 229 databases across genomics, proteomics, drug discovery, and materials science, plus a living lab notebook, 60+ scientific file previews, and LaTeX editing (K-Dense-AI, 908+ stars, MIT License, 2026)
* [Wisp Science](https://github.com/xuzhougeng/wisp-science) ⭐ 1,057 | 🐛 2 | 🌐 Rust | 📅 2026-08-28 - Open-source, local-first desktop AI research workbench for scientific computing with Python/R, MCP bioinformatics tools, SSH/WSL/GPU runtimes, and OpenAI/Anthropic models (857+ stars, 2026)
* [MATLAB Agentic Toolkit](https://github.com/matlab/matlab-agentic-toolkit) ⭐ 973 | 🐛 5 | 🌐 MATLAB | 📅 2026-08-27 - Official MathWorks toolkit connecting AI agents to MATLAB via the MATLAB MCP Server and curated skills, enabling trusted engineering and scientific computing workflows with idiomatic code generation, testing, and error diagnosis in Claude Code, GitHub Copilot, OpenAI Codex, and Gemini CLI (686+ stars, BSD-3-Clause, 2026)
* [Qinyan Academic Skills](https://github.com/LeonChaoX/qinyan-academic-skills) ⭐ 842 | 🐛 0 | 🌐 Python | 📅 2026-07-20 - Curated, multilingual library of 182 installable AI agent skills for end-to-end academic research spanning literature discovery, scientific writing, grant development, bioinformatics, drug discovery, clinical research, machine learning, and data analysis (779+ stars, MIT License, 2026)
* [MedgeClaw](https://github.com/xjtulyc/MedgeClaw) ⭐ 641 | 🐛 6 | 🌐 TeX | 📅 2026-03-12 - Open-source AI research assistant for biomedicine — chat to run RNA-seq, drug discovery, clinical analysis, and more; built on OpenClaw and Claude Code with 140 K-Dense scientific skills, real-time dashboard, and RStudio/JupyterLab integration (xjtulyc, 669+ stars, 2026)
* [BioMCP](https://github.com/genomoncology/biomcp) ⭐ 612 | 🐛 2 | 🌐 Rust | 📅 2026-08-28 - Biomedical Model Context Protocol (MCP) server unifying literature search across PubMed/Europe PMC, entity pivoting across genes/variants/drugs/diseases/pathways/proteins, local study analytics, and Claude Code/Codex integration for agentic biomedical research (531+ stars, MIT License, 2025-2026)
* [ScholarAIO](https://github.com/ZimoLiao/scholaraio) ⭐ 566 | 🐛 3 | 🌐 Python | 📅 2026-08-17 - Agent-agnostic research infrastructure providing AI agents with a structured scientific workspace for deep PDF parsing, hybrid semantic/keyword literature search, citation-graph analysis, topic discovery, and academic writing workflows; natively integrates with Claude Code, Codex, Cursor, Cline, and AgentSkills.io (530+ stars, MIT License, 2026)
* [BioNeMo Agent Toolkit (NVIDIA)](https://github.com/NVIDIA-BioNeMo/bionemo-agent-toolkit) ⭐ 434 | 🐛 5 | 🌐 Python | 📅 2026-08-27 - Turn any AI agent into a life science expert with NVIDIA BioNeMo skills, enabling agentic workflows for drug discovery, protein engineering, and biomolecular design (329+ stars, Apache 2.0 / CC-BY-4.0, 2026)
* [Notebook Intelligence (NBI)](https://github.com/notebook-intelligence/notebook-intelligence) ⭐ 332 | 🐛 43 | 🌐 Python | 📅 2026-08-28 - AI coding assistant for JupyterLab with agent mode, supporting arbitrary LLM providers (2025+)
* [Science Superpowers (K-Dense-AI)](https://github.com/K-Dense-AI/science-superpowers) ⭐ 301 | 🐛 1 | 🌐 Shell | 📅 2026-08-18 - Composable computational-science methodology skills for AI research agents emphasizing pre-registration, reproducible workspaces, and red-team review to guard against p-hacking and HARKing; zero third-party dependencies and runs with any agent harness plus a POSIX shell (281+ stars, MIT License, 2026)
* [OmicsClaw](https://github.com/TianGzlab/OmicsClaw) ⭐ 157 | 🐛 8 | 🌐 Python | 📅 2026-07-28 - Local-first, conversational AI research partner for multi-omics analysis with CLI, desktop app, and 95+ reproducible skills; keeps raw data local while routing natural-language requests to Python/R/CLI tools with persistent memory, autonomous analysis paths, and multi-method consensus workflows (TianGzlab, 155+ stars, Apache 2.0, 2026)
* [Google Colab AI Features](https://colab.research.google.com/) - Integrated AI assistance for data science and research notebooks
* [AutoR](https://github.com/AutoX-AI-Labs/AutoR) - Human-centered research OS with terminal-first harness and local browser Studio, turning research work into reproducible artifact-backed runs through a 9-stage workflow with human approval gates, resume/rollback controls, and venue-aware manuscript packaging (1K+ stars, 2026)

### Literature Management Plugins

* [Zotero-GPT (MuiseDestiny)](https://github.com/MuiseDestiny/zotero-gpt) ⭐ 7,366 | 🐛 247 | 🌐 TypeScript | 📅 2026-05-01 - Classic open-source plugin for document Q\&A and summarization within Zotero
* [llm-for-zotero](https://github.com/yilewang/llm-for-zotero) ⭐ 2,778 | 🐛 143 | 🌐 TypeScript | 📅 2026-08-25 - Research agent system deeply integrated with Zotero supporting Agent Mode, skills, multi-model backends (OpenAI-compatible, Claude Code, WebChat, Codex), and MinerU PDF parsing for literature Q\&A, summarization, figure inspection, and source comparison (1.3K+ stars, 2026)
* [PapersGPT for Zotero](https://github.com/papersgpt/papersgpt-for-zotero) ⭐ 2,616 | 🐛 75 | 🌐 JavaScript | 📅 2026-08-13 - Multi-PDF conversation, retrieval, and citation in Zotero with commercial/local models (Ollama), MCP support
* [Better BibTeX for Zotero](https://retorque.re/zotero-better-bibtex/) - Enhanced citation key management and LaTeX integration

### Scientific Writing & Collaboration

* [Obsidian Smart Connections](https://github.com/brianpetro/obsidian-smart-connections) ⭐ 5,407 | 🐛 489 | 🌐 JavaScript | 📅 2026-08-26 - AI-powered note linking and research graph navigation
* [PaperSpine](https://github.com/WUBING2023/PaperSpine) ⭐ 5,009 | 🐛 1 | 🌐 Python | 📅 2026-08-28 - Motivation-driven academic writing system for Claude Code, Codex, OpenClaw, and Hermes CLI that learns from strong papers, builds evidence-aware central-argument blueprints, and rewrites manuscripts with revision matrices and LaTeX-safe audits (4.9K+ stars, MIT License, 2026)
* [Claude Prism](https://github.com/delibae/claude-prism) ⭐ 1,760 | 🐛 34 | 🌐 TypeScript | 📅 2026-08-28 - Offline-first scientific writing workspace powered by Claude, integrating LaTeX, Python, and 100+ scientific skills with local execution, Zotero integration, and privacy-focused design (2026)
* [SciWrite](https://github.com/labarba/sciwrite) ⭐ 808 | 🐛 2 | 📅 2026-08-03 - Agent skill for AI-assisted scientific manuscript writing review distilled from Stanford's *Writing in the Sciences* course, performing five sequential editorial audit passes on clarity, voice, structure, consistency, and integrity (2026)
* [Notion AI](https://www.notion.so/product/ai) - AI-powered research note-taking and knowledge management
* [Research Rabbit](https://www.researchrabbit.ai/) - AI-powered literature discovery and research network mapping

***

## 🕸 Knowledge Extraction & Scholarly KGs

### Knowledge Graph Construction

* [GraphGen](https://github.com/open-sciencelab/GraphGen) ⭐ 1,213 | 🐛 10 | 🌐 Python | 📅 2026-08-17 - Knowledge graph-guided synthetic data generation for LLM fine-tuning, achieving strong performance on scientific QA (GPQA-Diamond) and math reasoning (AIME)
* [iText2KG](https://github.com/AuvaLab/itext2kg) ⭐ 960 | 🐛 5 | 🌐 Python | 📅 2026-04-30 - Incremental knowledge graph construction using LLMs with entity extraction and Neo4j visualization
* [KoPA](https://github.com/zjukg/KoPA) ⭐ 213 | 🐛 3 | 🌐 Python | 📅 2024-08-12 - Structure-aware prefix adaptation for integrating LLMs with knowledge graphs (ACM MM 2024)
* [SciAtlas](https://github.com/zjunlp/SciAtlas) ⭐ 145 | 🐛 1 | 🌐 Python | 📅 2026-07-16 - Large-scale knowledge graph and pip-installable client for literature-grounded automated scientific research, connecting papers, authors, institutions, venues, keywords, citations, and a four-level research taxonomy across medicine, social sciences, engineering, computer science, materials science, and more (ZJU NLP, arXiv 2026, 136+ stars, MIT License)
* [Scholarly KGQA](https://arxiv.org/abs/2311.09841) - LLM-powered question answering over scholarly knowledge graphs (ArXiv paper)

### Knowledge Graph Resources

* [Awesome-LLM-KG](https://github.com/RManLuo/Awesome-LLM-KG) ⭐ 2,614 | 🐛 6 | 📅 2025-05-02 - Comprehensive collection of papers on unifying LLMs and knowledge graphs

***

## 🤖 Research Agents & Autonomous Workflows

### Autonomous Research Systems (2023-2025 Breakthroughs)

* [autoresearch](https://github.com/karpathy/autoresearch) ⭐ 94,836 | 🐛 194 | 🌐 Python | 📅 2026-03-26 - Andrej Karpathy's autonomous LLM research framework: AI agent runs overnight experiments on a real training setup, auto-editing code→5min training→evaluation in a loop, \~100 experiments per night on a single GPU
* [ARIS (Auto-Research-In-Sleep)](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) ⭐ 15,374 | 🐛 62 | 🌐 Python | 📅 2026-08-26 - Lightweight Markdown-only skills for autonomous ML research with cross-model review loops, idea discovery, and experiment automation; no framework lock-in, works with Claude Code, Codex, OpenClaw, or any LLM agent (12.8K+ stars, MIT License, 2026)
* [The AI Scientist (SakanaAI)](https://github.com/SakanaAI/AI-Scientist) ⭐ 14,455 | 🐛 119 | 🌐 Jupyter Notebook | 📅 2025-12-19 - First fully autonomous open-ended scientific discovery system with official implementation: hypothesis→experiment→writing→review simulation (13.8K+ stars, 2024)
* [RD-Agent (Microsoft)](https://github.com/microsoft/rd-agent) ⭐ 14,351 | 🐛 199 | 🌐 Python | 📅 2026-08-04 - Open-source LLM-powered R\&D agent framework automating data-driven AI solution building through automated research, development, and evolution; achieves top open-source performance on MLE-Bench with dual Researcher-Developer agents and supports research copilot, data mining, Kaggle, and quant R\&D workflows (13.6K+ stars, MIT License, 2025-2026)
* [AutoResearchClaw](https://github.com/aiming-lab/AutoResearchClaw) ⭐ 14,266 | 🐛 8 | 🌐 Python | 📅 2026-08-19 - Fully autonomous research from idea to paper with multi-agent debate, citation verification, and OpenClaw integration (11K+ stars, 2026)
* [OpenEvolve](https://github.com/algorithmicsuperintelligence/openevolve) ⭐ 7,278 | 🐛 117 | 🌐 Python | 📅 2026-07-18 - Open-source implementation of AlphaEvolve's evolutionary coding agent paradigm, enabling LLMs to autonomously discover and optimize algorithms through iterative evolution, matching the approach behind DeepMind's breakthrough matrix multiplication discovery (6.2K+ stars, 2025)
* [The AI Scientist v2 (SakanaAI)](https://github.com/SakanaAI/AI-Scientist-v2) ⭐ 7,057 | 🐛 78 | 🌐 Python | 📅 2025-12-19 - Official implementation of the second-generation fully autonomous scientific discovery system, extending the original with agentic tree search and reduced template dependency to achieve workshop-level accepted papers (6.7K+ stars, 2025)
* [AI-Researcher](https://github.com/HKUDS/AI-Researcher) ⭐ 5,704 | 🐛 67 | 🌐 Python | 📅 2025-10-16 - Autonomous pipeline from literature review→hypothesis→algorithm implementation→publication-level writing with Scientist-Bench evaluation
* [EvoScientist](https://github.com/EvoScientist/EvoScientist) ⭐ 4,521 | 🐛 35 | 🌐 Python | 📅 2026-08-27 - Self-evolving AI scientist with 6 specialized sub-agents (plan/research/code/debug/analyze/write) and persistent memory, #1 on DeepResearch Bench II and AstaBench, supporting multi-provider LLMs and multi-channel deployment (Apache 2.0, 2026)
* [DeepScientist](https://github.com/ResearAI/DeepScientist) ⭐ 3,296 | 🐛 15 | 🌐 TypeScript | 📅 2026-06-28 - First system progressively surpassing human SOTA on frontier AI tasks (183.7%, 1.9%, 7.9% improvements), month-long autonomous discovery with 20,000+ GPU hours
* [FAROS (OpenNSWM-Lab)](https://github.com/OpenNSWM-Lab/FAROS) ⭐ 3,026 | 🐛 23 | 🌐 Python | 📅 2026-08-28 - Foundation AutoResearch Operating System: blueprint-driven runtime for orchestrating AI research workflows from idea generation and experiments to paper writing and peer review (OpenNSWM-Lab, 2.4K+ stars, 2026)
* [ResearchStudio (Microsoft)](https://github.com/microsoft/ResearchStudio) ⭐ 2,546 | 🐛 6 | 🌐 Python | 📅 2026-08-27 - AI co-author covering the entire research lifecycle — from an under-specified research direction to a published paper; includes ResearchStudio-Idea for evidence-grounded research ideation and ResearchStudio-Reel for turning finished papers into posters, narrated videos, blogs, and interactive reels; runs as skills on Claude Code and Codex (1.2K+ stars, MIT License, 2026)
* [ToolUniverse](https://github.com/mims-harvard/ToolUniverse) ⭐ 1,660 | 🐛 26 | 🌐 Python | 📅 2026-08-25 - Democratizing AI scientists by transforming any LLM into research systems with 600+ scientific tools (Harvard MIMS)
* [AIDE (WecoAI, arXiv 2025)](https://github.com/WecoAI/aideml) ⭐ 1,496 | 🐛 3 | 🌐 Python | 📅 2026-08-17 - LLM-driven machine learning engineering agent using agentic tree search to autonomously draft, debug and benchmark ML code; wins 4× more medals than the best linear agent on OpenAI's MLE-Bench (75 Kaggle competitions) (1.3K+ stars, MIT License)
* [InternAgent](https://github.com/Alpha-Innovator/InternAgent) ⭐ 1,416 | 🐛 3 | 🌐 Python | 📅 2026-07-29 - Closed-loop multi-agent system from hypothesis to verification across 12 scientific tasks, #1 on MLE-Bench (36.44%)
* [NanoResearch](https://github.com/OpenRaiser/NanoResearch) ⭐ 1,359 | 🐛 7 | 🌐 Python | 📅 2026-08-25 - End-to-end autonomous AI research engine that turns an idea into a complete LaTeX paper by dispatching real computational experiments to local GPUs or SLURM clusters, collecting actual results, generating figures/tables, and writing a data-grounded manuscript rather than LLM hallucinations (OpenRaiser, 1.5K+ stars, MIT License, 2026)
* [ASI-Arch (GAIR-NLP, arXiv 2025)](https://github.com/GAIR-NLP/ASI-Arch) ⭐ 1,183 | 🐛 5 | 🌐 Python | 📅 2025-12-03 - Autonomous multi-agent research loop for model architecture discovery that ran 1,773 experiments over 20,000 GPU hours and produced 106 state-of-the-art linear-attention architectures, surpassing human-designed baselines including Mamba2 and DeltaNet (1.1K+ stars, Apache 2.0)
* [FunSearch (DeepMind, Nature 2023)](https://github.com/google-deepmind/funsearch) ⭐ 1,111 | 🐛 8 | 🌐 Jupyter Notebook | 📅 2024-02-05 - First system to make novel, verifiable scientific discoveries by pairing LLMs with evolutionary search, solving open problems in combinatorics (cap set problem) and discovering faster matrix multiplication algorithms
* [LabClaw](https://github.com/wu-yc/LabClaw) ⭐ 1,048 | 🐛 4 | 📅 2026-03-19 - Skill operating layer for biomedical AI agents with 211 production-ready SKILL.md files across 7 domains (biology, pharmacology, medicine, data science, literature search), enabling modular dry-lab reasoning and protocol composition for Stanford LabOS-compatible agents
* [Arbor](https://github.com/RUC-NLPIR/Arbor) ⭐ 1,045 | 🐛 3 | 🌐 Python | 📅 2026-08-21 - Generalist autonomous research agent that grows a hypothesis tree to optimize any measurable task, beating Claude Code and Codex by 2.5× on the same compute budget across BrowseComp, Terminal-Bench 2.0, math reasoning, and MLE-Bench Lite; supports native CLI, keyless Claude Code/Codex integration, and an MCP tool server (RUC-NLPIR, 866+ stars, Apache 2.0, 2026)
* [CORAL (arXiv 2026)](https://github.com/Human-Agent-Society/CORAL) ⭐ 934 | 🐛 17 | 🌐 Python | 📅 2026-08-23 - Robust, lightweight infrastructure for multi-agent autonomous self-evolution, built for autoresearch; agents run in isolated git worktrees, share knowledge through a common state directory, and are scored by a grader daemon; natively integrated with Claude Code, Codex, Cursor Agent, OpenCode, and Kiro (672+ stars, Apache 2.0)
* [ScienceClaw](https://github.com/beita6969/ScienceClaw) ⭐ 885 | 🐛 9 | 🌐 TypeScript | 📅 2026-06-08 - Self-evolving AI research colleague built on OpenClaw with 285+ runtime-adaptive skills across 28+ disciplines, persistent cross-session research memory, and zero-hallucination citation protocols; agent autonomously writes new SKILL.md files based on research patterns without redeployment (828+ stars, MIT License, 2026)
* [Science-Star (USTC AI4Science, 2025)](https://github.com/ustc-ai4science/Science-Star) ⭐ 754 | 🐛 1 | 🌐 Python | 📅 2026-03-04 - Open-source platform for building, extending, and experimenting with scientific agents, providing modular agent construction tools and standardized evaluation pipelines for accelerating autonomous scientific discovery research (748+ stars, MIT License)
* [AutoScientists (Harvard MIMS, arXiv 2026)](https://github.com/mims-harvard/AutoScientists) ⭐ 730 | 🐛 9 | 🌐 Python | 📅 2026-05-28 - Decentralized self-organizing teams of AI agents for long-running computational scientific experimentation; agents critique each other's proposals before spending compute and share successes/failures to avoid redundant exploration, achieving +8.33% on BioML-Bench, 1.9× faster nanoGPT optimization, and +12.5% on ProteinGym ACE2-Spike (425+ stars, 2026)
* [Virtual Lab (Stanford Zou Group, Nature 2025)](https://github.com/zou-group/virtual-lab) ⭐ 727 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2025-12-31 - AI-human collaborative research platform where a human researcher works with a team of LLM agents via team and individual meetings to perform scientific research; demonstrated by designing new SARS-CoV-2 nanobodies with wet-lab validation
* [Principia](https://github.com/pzqpzq/Principia) ⭐ 697 | 🐛 4 | 🌐 Rich Text Format | 📅 2026-08-23 - Principle-first scientific idea discovery framework that extracts reusable principles from public literature and private research materials, composes them into traceable Idea Cards with prior-art comparisons, and exports validation-ready research packs; emphasizes inspectable scientific objects, risk disclosure, and falsification paths (ICML 2026, 411+ stars, MIT License)
* [Robin](https://github.com/Future-House/robin) ⭐ 686 | 🐛 5 | 🌐 Python | 📅 2026-04-21 - FutureHouse's end-to-end scientific discovery multi-agent system orchestrating literature search (Crow/Falcon) and data analysis (Finch) agents, first AI-generated drug discovery identifying ripasudil as novel dry AMD therapeutic (2025)
* [ARA (Agent-Native Research Artifact)](https://github.com/ARA-Labs/Agent-Native-Research-Artifact) ⭐ 669 | 🐛 9 | 🌐 Python | 📅 2026-08-24 - Research ecosystem for rigorous and trustworthy AI scientists — a protocol and skill bundle that makes autonomous research verifiable, crystallized, and observable through structured, machine-executable research artifacts and five agent skills for research management, compilation, verification, visualization, and publication (ARA-Labs, 447+ stars, MIT License, 2026)
* [SkyDiscover](https://github.com/skydiscover-ai/skydiscover) ⭐ 623 | 🐛 26 | 🌐 Python | 📅 2026-08-27 - Modular framework for AI-driven scientific and algorithmic discovery, providing a unified interface for implementing, running, and fairly comparing discovery algorithms across 200+ optimization tasks; introduces AdaEvolve and EvoX adaptive/evolutionary algorithms and natively supports OpenEvolve, GEPA, and Harbor-format benchmarks (skydiscover-ai, 568+ stars, Apache 2.0, 2026)
* [freephdlabor](https://github.com/ltjed/freephdlabor) ⭐ 620 | 🐛 1 | 🌐 Python | 📅 2026-05-14 - First fully customizable open-source multiagent framework automating complete research lifecycle from idea conception to LaTeX papers with dynamic workflows
* [Denario (AstroPilot-AI, Agents4Science 2025)](https://github.com/AstroPilot-AI/Denario) ⭐ 590 | 🐛 9 | 🌐 TeX | 📅 2026-06-02 - Modular multi-agent scientific research assistant that automates idea generation, literature review, methodology design, code execution in Docker, visualization, LaTeX paper writing, and peer-review simulation across 10+ disciplines; winner of the NeurIPS 2025 Fair Universe Competition (573+ stars, GPL-3.0, 2025-2026)
* [Kosmos](https://github.com/jimmc414/Kosmos) ⭐ 572 | 🐛 1 | 🌐 Python | 📅 2026-04-04 - Extended autonomy AI scientist with 200 parallel agent rollouts, 42K lines of code execution, 1.5K papers analyzed per run, achieving 79.4% accuracy and 7 scientific discoveries (Edison Scientific)
* [PantheonOS (Stanford, 2025)](https://github.com/aristoteleo/PantheonOS) ⭐ 481 | 🐛 21 | 🌐 Python | 📅 2026-08-28 - Evolvable and privacy-preserving multi-agent framework automating, scaling, and accelerating data sciences with a particular focus on end-to-end single-cell biology analyses; features agentic code evolution, multi-agent team orchestration, distributed architecture, and a community marketplace with 1,000+ curated agents and skills (428+ stars)
* [Scholar Loop](https://github.com/renee-jia/scholar-loop) ⭐ 468 | 🐛 0 | 🌐 Python | 📅 2026-06-23 - Autonomous multi-agent AI scientist that mirrors a PhD workflow: literature review → grounded hypothesis → real ML experiments → self-critique → write-up; features a deterministic harness with frozen-metric scoring, edit allowlists, and a verified registry to make reward-hacking and hallucination impossible, plus 108 unit tests runnable without API keys or GPUs (461+ stars, MIT License, 2026)
* [Curie](https://github.com/Just-Curieous/Curie) ⭐ 371 | 🐛 23 | 🌐 Python | 📅 2025-09-28 - Automated and rigorous experiments using AI agents for scientific discovery
* [CodeScientist (AllenAI)](https://github.com/allenai/codescientist) ⭐ 348 | 🐛 1 | 🌐 Python | 📅 2026-03-25 - End-to-end semi-automated scientific discovery system that designs, iterates, and analyzes code-based experiments via LLM-as-a-mutator over scientific articles and code examples; auto-creates, runs, and debugs experiment code in containers and writes meta-analysis reports (339+ stars, Apache 2.0)
* [POPPER](https://github.com/snap-stanford/POPPER) ⭐ 289 | 🐛 6 | 🌐 Python | 📅 2025-05-14 - Automated hypothesis testing with agentic sequential falsifications
* [Aviary](https://github.com/Future-House/aviary) ⭐ 276 | 🐛 13 | 🌐 Python | 📅 2026-08-26 - Language agent gymnasium for challenging scientific tasks including DNA manipulation, literature search, and protein engineering
* [EvoMaster (SJTU SAI, arXiv 2026)](https://github.com/sjtu-sai-agents/EvoMaster) ⭐ 219 | 🐛 3 | 🌐 Python | 📅 2026-05-28 - Foundational auto-research agent framework for agentic science at scale, providing modular agent construction, run-level self-evolution, and multiple SciMaster domain agents (ML-Master, X-Master, Browse-Master); outperforms general-purpose agents across authoritative benchmarks including the OpenAI Frontier Science Benchmark (206+ stars, Apache 2.0, 2026)
* [ai4s-skills](https://github.com/ai4s-research/ai4s-skills) ⭐ 186 | 🐛 0 | 🌐 Python | 📅 2026-07-28 - Agent skills (SKILL.md + deterministic tools) for the AI4S workflow — topic exploration, literature survey, runnable experiments, publication-grade papers, and integrity audit, with every citation and number traceable to its source (by ai4s-research, maintainers of this list; MIT, 2026)
* [UniScientist](https://github.com/UniPat-AI/UniScientist) ⭐ 171 | 🐛 1 | 🌐 Python | 📅 2026-03-14 - Universal scientific research intelligence covering 50+ disciplines, repositioning LLMs as cross-disciplinary generators with human experts as verifiers; 30B model outperforms Claude Opus and GPT on 5 research benchmarks
* [Hyra (Tencent Hunyuan, 2026)](https://hy.tencent.com/research/hyra) - Hunyuan Research Agent for autonomous open-ended discovery across AI4Science, mathematics, and engineering, releasing reproducible solution artifacts for autocorrelation constants, Erdős problems, PARP1 docking, qubit routing, and record-breaking packing problems ([Hyra-results](https://github.com/Tencent-Hunyuan/Hyra-results) ⭐ 145 | 🐛 0 | 🌐 Python | 📅 2026-08-19, 112+ stars, Apache 2.0)
* [XScientist](https://github.com/smileformylove/XScientist) ⭐ 128 | 🐛 0 | 🌐 Python | 📅 2026-08-28 - Local-first autonomous research system implementing a Git-like research protocol for long-running scientific discovery; explores competing explanations, executes experiments inside an isolation boundary, self-criticizes results, and exports the entire path as typed Agent-Native Research Artifacts (ARA) with exploration DAGs, claim-to-evidence anchors, content hashes, and re-execution hooks (126+ stars, Apache 2.0, arXiv 2026)
* [AlphaResearch](https://github.com/answers111/alpha-research) ⭐ 61 | 🐛 1 | 🌐 Python | 📅 2025-11-12 - Autonomous algorithm discovery combining evolutionary search with peer-review reward models, achieving best-known performance on circle packing problems
* [SR-Scientist (ICLR 2026)](https://github.com/GAIR-NLP/SR-Scientist) ⭐ 55 | 🐛 0 | 🌐 Python | 📅 2026-01-27 - Scientific equation discovery with agentic AI, elevating LLMs from equation proposers to autonomous scientists that write code, analyze data, implement equations, and optimize based on experimental feedback; outperforms baselines by 6-35% across four science disciplines with robustness to noise and out-of-domain generalization (GAIR-NLP / SJTU, 49+ stars, Apache 2.0)
* [Imbue Catalyst](https://github.com/imbue-ai/catalyst) ⭐ 32 | 🐛 5 | 🌐 Python | 📅 2026-08-15 - Semi-autonomous AI scientist for scientific theory discovery and verifiable goal solving, using adversarial review-refinement loops and evolution-inspired candidate populations; integrates with Claude Code, Gemini CLI, Antigravity, and Codex harnesses (Imbue, 31+ stars, AGPL-3.0, 2026)
* [AI Co-Scientist (Google DeepMind, Nature Medicine 2026)](https://deepmind.google/blog/co-scientist-a-multi-agent-ai-partner-to-accelerate-research/) - Multi-agent AI research partner that generates, reviews, ranks, and evolves research hypotheses alongside scientists, with experimental validation in biomedicine and other domains (2026)
* [The AI Scientist v1 (2024)](https://arxiv.org/abs/2408.06292) - First fully autonomous research system: hypothesis→experiment→writing→review simulation
* [The AI Scientist v2 (2025)](https://arxiv.org/abs/2504.08066) - Enhanced with Agentic Tree Search, reduced template dependency, first workshop-level accepted paper
* [Agent Laboratory](https://agentlaboratory.github.io/) - Multi-agent workflows for complete research cycles with AgentRxiv for cumulative discovery

### Evaluation & Benchmarking

* [MLE-Bench (OpenAI, 2024)](https://github.com/openai/mle-bench) ⭐ 1,724 | 🐛 10 | 🌐 Python | 📅 2026-04-24 - Benchmark evaluating AI agents on 75 curated Kaggle-style ML engineering competitions with reproducible Docker-based grading harness, human baselines, and end-to-end task lifecycle, used as a primary benchmark for autonomous ML research agents (e.g., InternAgent #1 at 36.44%)
* [PaperGuru (AutoTrustAI, 2026)](https://github.com/AutoTrustAI/PaperGuru-Benchmark) ⭐ 1,324 | 🐛 0 | 🌐 TeX | 📅 2026-06-08 - Lifecycle-Aware Memory (LAM) primitive and benchmark for long-horizon research agents, achieving 65.95% mean reproduction on PaperBench and 94.66% on SurveyBench through Capital Chunk Memory (CCM) with versioned content, structural multi-hop relevance, and provenance-grounded composition; 10 peer-reviewed acceptances at FSE/ICML/TOSEM/AEI/ICoGB (1.3K+ stars)
* [PaperBench (OpenAI, 2025)](https://github.com/openai/preparedness/tree/main/project/paperbench) ⭐ 1,289 | 🐛 66 | 🌐 Python | 📅 2026-04-21 - Benchmark evaluating AI agents' ability to replicate 20 ICML 2024 Spotlight/Oral papers from scratch, with 8,316 gradable tasks and author-co-developed rubrics
* [Terminal-Bench Science (Harbor Framework, 2026)](https://github.com/harbor-framework/terminal-bench-science) ⭐ 346 | 🐛 251 | 🌐 Python | 📅 2026-08-27 - Benchmark evaluating AI agents on complex real-world scientific workflows in terminal environments across life, physical, earth, and mathematical sciences; featured on model cards for Claude Opus 4.7, GPT-5.5, and Gemini 3.1 Pro (200+ stars, Apache 2.0)
* [ResearchClawBench (InternScience, arXiv 2026)](https://github.com/InternScience/ResearchClawBench) ⭐ 250 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2026-08-20 - Benchmark evaluating AI agents for end-to-end automated research from re-discovery to new-discovery, with 40 real-science tasks across 10 disciplines, curated datasets from published papers, and expert-curated multimodal rubrics (170+ stars, MIT License)
* [SciCode](https://github.com/scicode-bench/SciCode) ⭐ 224 | 🐛 21 | 🌐 Python | 📅 2026-08-24 - Research coding benchmark curated by scientists with 338 subproblems across 16 subdomains (physics, math, materials, biology, chemistry), evaluating LLMs on realistic scientific programming tasks with gold-standard solutions (NeurIPS 2024)
* [ScienceAgentBench (ICLR 2025)](https://github.com/OSU-NLP-Group/ScienceAgentBench) ⭐ 165 | 🐛 0 | 🌐 Python | 📅 2026-07-18 - 102 executable tasks from 44 peer-reviewed papers across 4 disciplines with containerized evaluation
* [NewtonBench (ICLR 2026)](https://github.com/HKUST-KnowComp/NewtonBench) ⭐ 155 | 🐛 1 | 🌐 Python | 📅 2026-02-27 - First benchmark evaluating LLMs' ability to rediscover scientific laws through interactive experimentation across 324 tasks in 12 physics domains, featuring memorization-resistant metaphysical shifts of canonical laws (HKUST)
* [ScienceBoard (ICLR 2026)](https://github.com/OS-Copilot/ScienceBoard) ⭐ 137 | 🐛 7 | 🌐 Python | 📅 2026-02-02 - Evaluating multimodal autonomous agents in realistic scientific workflows across real scientific software environments (KAlgebra, Celestia, Grass GIS, Lean 4, etc.) with VM-based evaluation infrastructure and agent trajectories
* [AIRS-Bench (Meta, 2026)](https://github.com/facebookresearch/airs-bench) ⭐ 112 | 🐛 0 | 🌐 Python | 📅 2026-05-05 - Benchmark quantifying end-to-end autonomous AI research abilities of LLM agents across 20 tasks from SOTA machine learning papers spanning NLP, code, math, biochemical modelling, and time series forecasting, with normalized score metrics against human SOTA and HuggingFace dataset
* [BuildArena](https://github.com/AI4Science-WestlakeU/BuildArena) ⭐ 98 | 🐛 0 | 🌐 Python | 📅 2026-05-04 - First physics-aligned interactive benchmark for LLM agents in engineering construction, designing rockets/cars/bridges in physics simulator with 3D spatial geometry library
* [SciTrust (2024)](https://impact.ornl.gov/en/publications/scitrust-evaluating-the-trustworthiness-of-large-language-models-) - Trustworthiness evaluation framework for scientific LLMs (truthfulness, hallucination, sycophancy)
* [SciBench](https://arxiv.org/abs/2307.10635) - College-level scientific problem-solving evaluation across multiple domains

### Academic Review & Evaluation

* [LLM-Peer-Review](https://github.com/VijayGKR/LLM-Peer-Review) ⭐ 2 | 🐛 0 | 🌐 TypeScript | 📅 2024-08-18 - Web application for LLM-assisted manuscript review and annotation
* [AgentReview](https://agentreview.github.io/) - LLM agents simulating academic peer review ecosystems

### Domain-Specific Research Agents

* [AlphaGeometry](https://github.com/google-deepmind/alphageometry) ⭐ 4,879 | 🐛 140 | 🌐 Python | 📅 2026-01-13 - DeepMind's Olympiad-level geometry theorem prover combining neural language model with symbolic deduction engine, AlphaGeometry2 solves 84% of IMO geometry problems (42/50) at gold-medalist level (Nature 2024)
* [Biomni](https://github.com/snap-stanford/Biomni) ⭐ 3,805 | 🐛 95 | 🌐 Python | 📅 2026-08-24 - General-purpose biomedical AI agent integrating LLM reasoning with retrieval-augmented planning and code-based execution to autonomously execute diverse biomedical research tasks and generate testable hypotheses (Stanford SNAP, bioRxiv 2025)
* [Lean Copilot](https://github.com/lean-dojo/LeanCopilot) ⭐ 1,316 | 🐛 0 | 🌐 C++ | 📅 2026-08-22 - LLMs as copilots for theorem proving in Lean 4, exposing native tactics (`suggest_tactics`, `search_proof`, `select_premises`) that embed language model inference and premise retrieval directly inside the Lean proof environment, supporting local CTranslate2/CUDA inference as well as remote model APIs for interactive and automated proof search (Caltech & NVIDIA, NeurIPS 2024, 1.2K+ stars)
* [DeepSeek-Prover-V2](https://github.com/deepseek-ai/DeepSeek-Prover-V2) ⭐ 1,297 | 🐛 12 | 📅 2025-07-18 - DeepSeek's open-source large language model for formal theorem proving in Lean 4, integrating informal and formal mathematical reasoning through recursive subgoal decomposition and reinforcement learning powered by DeepSeek-V3, with open weights and ProverBench evaluation (2025)
* [ClawBio](https://github.com/ClawBio/ClawBio) ⭐ 1,119 | 🐛 30 | 🌐 Python | 📅 2026-08-28 - First bioinformatics-native AI agent skill library enabling local-first, reproducible genomic and population-genetics research workflows built on OpenClaw (871+ stars, MIT License, 2026)
* [Get Physics Done (PSI)](https://github.com/psi-oss/get-physics-done) ⭐ 911 | 🐛 38 | 🌐 Python | 📅 2026-07-23 - First open-source agentic AI physicist turning research questions into structured workflows with rigorous verification and multi-step analytical work for long-horizon physics projects; integrates with Claude Code, Codex, Gemini CLI, and OpenCode (804+ stars, Apache 2.0, 2026)
* [LeanDojo](https://github.com/lean-dojo/LeanDojo) ⭐ 831 | 🐛 12 | 🌐 Python | 📅 2026-01-18 - Open-source toolkit and benchmark for learning-based theorem proving in Lean, providing programmatic Lean interaction, a 98K+ theorem dataset extracted from 217 Lean projects, and ReProver—the first retrieval-augmented LLM-based theorem prover for Lean—with reproducible training pipelines underpinning much subsequent Lean prover research (Caltech & NVIDIA, NeurIPS 2023 Outstanding Paper, Datasets & Benchmarks)
* [MathCode](https://github.com/math-ai-org/mathcode) ⭐ 733 | 🐛 1 | 🌐 Shell | 📅 2026-08-25 - Terminal AI coding assistant with a built-in math formalization engine that converts plain-language math problems into Lean 4 theorems and attempts formal proofs; bundles a local Lean toolchain and WebUI for interactive mathematical reasoning (math-ai-org, 582+ stars, 2026)
* [TxAgent](https://github.com/mims-harvard/TxAgent) ⭐ 652 | 🐛 22 | 🌐 Python | 📅 2025-07-30 - AI agent for therapeutic reasoning across a universe of tools, achieving 92.1% accuracy in drug reasoning and outperforming GPT-4o by 25.8% (Harvard MIMS, 2025)
* [SciAgents](https://github.com/lamm-mit/SciAgentsDiscovery) ⭐ 635 | 🐛 11 | 🌐 Python | 📅 2025-05-10 - Bioinspired multi-agent intelligent graph reasoning system that autonomously traverses ontological knowledge graphs to generate, critique, and refine novel research hypotheses, demonstrated on bio-inspired materials discovery with cross-disciplinary connection mining (MIT Lamm Group, 2024)
* [Camyla](https://github.com/yifangao112/Camyla) ⭐ 367 | 🐛 2 | 🌐 Python | 📅 2026-04-14 - Fully autonomous medical image segmentation research system that generates complete manuscripts end-to-end from datasets with zero human intervention, beating strongest baselines on 24 of 31 datasets and achieving T1-T2 tier manuscript quality in double-blind evaluations (USTC & Shanghai AI Lab, 2026)
* [Foam-Agent (NeurIPS 2025)](https://github.com/csml-rpi/Foam-Agent) ⭐ 308 | 🐛 4 | 🌐 Python | 📅 2026-08-14 - End-to-end composable multi-agent framework for automating OpenFOAM-based CFD simulations from natural language prompts, managing meshing, case setup, execution, error correction, and post-processing; achieves 100% success rate on 110 FoamBench tasks with Claude Opus 4.6 through Architect-Input Writer-Runner-Reviewer agent collaboration with RAG-enhanced generation and MCP tool integration (RPI CSML, 242+ stars, MIT License)
* [AlphaProof Nexus (Google DeepMind, arXiv 2026)](https://github.com/google-deepmind/alphaproof-nexus-results) ⭐ 292 | 🐛 1 | 🌐 Lean | 📅 2026-07-21 - LLM-driven formal proof search system that pairs large language models with Lean verification to solve open mathematics problems; autonomously resolved 9 of 353 Erdős problems and 44 of 492 OEIS conjectures, with proofs and natural-language prose released for combinatorics, optimization, graph theory, algebraic geometry, and quantum optics collaborations (282+ stars, Apache 2.0)
* [Goedel-Prover-V2](https://github.com/Goedel-LM/Goedel-Prover-V2) ⭐ 187 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2025-08-27 - Strongest open-source automated theorem prover in Lean 4, 8B model matches DeepSeek-Prover-V2-671B at 84.6% MiniF2F, 32B model achieves 90.4% with self-correction, using scaffolded data synthesis and verifier-guided proof refinement (Princeton, 2025)
* [BioAgents](https://github.com/bio-xyz/BioAgents) ⚠️ Archived - AI scientist framework for autonomous deep research in biological sciences, combining literature analysis agents with data scientist agents to enable iterative scientific discovery through user feedback integration; achieves state-of-the-art performance on BixBench benchmark (48.78% open-answer, 64.39% multiple-choice) outperforming Kepler and GPT-5 (bio-xyz, arXiv 2601.12542, 160+ stars, 2025-2026)
* [SRAgent](https://github.com/ArcInstitute/SRAgent) ⭐ 181 | 🐛 3 | 🌐 Python | 📅 2026-07-24 - LLM agents for working with the SRA (Sequence Read Archive) and associated bioinformatics databases, enabling natural language querying of high-throughput sequencing data and metadata across genomic repositories (Arc Institute, 169+ stars, 2024-2026)
* [Ten Proofs (OpenAI, 2026)](https://github.com/openai/ten-proofs) ⭐ 145 | 🐛 0 | 🌐 Lean | 📅 2026-08-05 - Lean 4 formalizations of ten major advances in mathematics and theoretical computer science, including improved sphere-packing bounds, non-sofic groups, a counterexample to Connes's rigidity conjecture, and quantum parallel repetition; released with the OpenAI paper and reasoning walkthroughs (57+ stars, Apache 2.0)
* [TorchLean (lean-dojo, 2026)](https://github.com/lean-dojo/TorchLean) ⭐ 131 | 🐛 7 | 🌐 Lean | 📅 2026-08-27 - First unified Lean 4 framework for neural-network specification, execution, and verification; tensor shapes are part of the types, models are executable Lean programs, and the same definitions can be used by training code, graph transformations, certificate checkers, and proofs with CPU/CUDA backends (123+ stars, MIT License)
* [BioDiscoveryAgent](https://github.com/snap-stanford/BioDiscoveryAgent) ⭐ 124 | 🐛 4 | 🌐 Python | 📅 2025-07-06 - AI agent for biological discovery and research automation
* [STAgent](https://github.com/LiuLab-Bioelectronics-Harvard/STAgent) ⭐ 63 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-05-22 - Multimodal LLM-based AI agent enabling deep research in spatial transcriptomics, automating analysis and interpretation of spatial gene expression data (Harvard LiuLab, bioRxiv 2025)
* [ATHENA-R1 (Harvard MIMS)](https://github.com/mims-harvard/ATHENA) ⭐ 63 | 🐛 1 | 🌐 Python | 📅 2026-07-17 - Reinforcement-learning-trained AI agent for treatment reasoning over a universe of 212 biomedical tools, performing multi-step evidence gathering and spawning parallel reasoning branches to reach evidence-grounded clinical decisions (55+ stars, MIT License, 2026)
* [MOOSE](https://github.com/ZonglinY/MOOSE) ⭐ 47 | 🐛 2 | 🌐 Python | 📅 2024-10-28 - Large Language Models for automated open-domain scientific hypotheses discovery (ACL 2024, ICML Best Poster)
* [AI CFD Scientist (RPI CSML, arXiv 2026)](https://github.com/csml-rpi/AI-CFD-Scientist) ⭐ 46 | 🐛 1 | 🌐 Python | 📅 2026-05-20 - Open-ended AI scientist for computational fluid dynamics that spans literature-grounded ideation, OpenFOAM execution via Foam-Agent, vision-language physics verification of rendered flow fields, source-code modification for new physical models, and figure-grounded LaTeX manuscript writing within a single inspectable workflow (43+ stars, Python)
* [Zephyrus (ICLR 2026)](https://github.com/Rose-STL-Lab/Zephyrus) ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2026-03-27 - First agentic framework for weather science, pairing an LLM with ZephyrusWorld (a code-execution environment exposing WeatherBench 2 data, geolocation, forecasting, simulation, and climatology tools) and ZephyrusBench (2,230 Q\&A pairs across 49 weather-science tasks); outperforms text-only baselines by up to 44.2 percentage points (UC San Diego Rose-STL-Lab, 99+ stars, MIT License, 2026)
* [Aletheia](https://arxiv.org/abs/2602.10177) - Google DeepMind's autonomous mathematics research agent powered by Gemini Deep Think, autonomously solving 4 open problems from 700 Erdős conjectures and generating complete research papers without human intervention (February 2026)
* [ChemCrow](https://arxiv.org/abs/2304.05376) - LLM agents for chemistry research with tool integration
* [Coscientist](https://www.nature.com/articles/s41586-023-06792-1) - Autonomous chemical experiment planning and execution

***

## 🏷 Data Labeling & Curation

### Weak Supervision & Auto-Labeling

* [PandasAI](https://github.com/Sinaptik-AI/pandas-ai) ⭐ 23,774 | 🐛 22 | 🌐 Python | 📅 2025-10-28 - Conversational data analysis and visualization using natural language
* [Cleanlab](https://github.com/cleanlab/cleanlab) ⭐ 11,637 | 🐛 122 | 🌐 Python | 📅 2026-01-13 - Standard data-centric AI package for data quality and machine learning, automatically detecting label errors, outliers, and dataset issues to improve scientific dataset reliability and model performance (11K+ stars, MIT License)
* [Snorkel](https://github.com/snorkel-team/snorkel) ⭐ 6,003 | 🐛 19 | 🌐 Python | 📅 2026-06-08 - Programmatic data labeling and weak supervision for scientific datasets

***

## ⚗ Scientific Machine Learning

### Neural Differential Equations

* [torchdiffeq](https://github.com/rtqichen/torchdiffeq) ⭐ 6,477 | 🐛 95 | 🌐 Python | 📅 2025-04-04 - PyTorch implementation of neural ODEs
* [DifferentialEquations.jl](https://github.com/SciML/DifferentialEquations.jl) ⭐ 3,151 | 🐛 127 | 🌐 Julia | 📅 2026-08-27 - Julia differential equations suite
* [diffrax](https://github.com/patrick-kidger/diffrax) ⭐ 2,091 | 🐛 239 | 🌐 Python | 📅 2026-06-21 - Numerical differential equation solving in JAX
* [torchdyn](https://github.com/DiffEqML/torchdyn) ⭐ 1,578 | 🐛 40 | 🌐 Jupyter Notebook | 📅 2024-05-02 - Neural differential equations in PyTorch
* [DiffEqFlux.jl](https://github.com/SciML/DiffEqFlux.jl) ⭐ 924 | 🐛 56 | 🌐 Julia | 📅 2026-08-28 - Neural differential equations in Julia

### Chemical Reaction Networks & Systems Biology

* [Catalyst.jl](https://github.com/SciML/Catalyst.jl) ⭐ 527 | 🐛 116 | 🌐 Julia | 📅 2026-08-28 - Chemical reaction network and systems biology interface for scientific machine learning (SciML), enabling high-performance, GPU-parallelized simulation and analysis of complex biochemical systems with O(1) solvers (SciML, 518+ stars, Julia)

### Physics-Informed Neural Networks

* [PINNs](https://github.com/maziarraissi/PINNs) ⭐ 6,114 | 🐛 51 | 🌐 Python | 📅 2026-02-11 - Physics-informed neural networks
* [DeepXDE](https://github.com/lululxvi/deepxde) ⭐ 4,390 | 🐛 316 | 🌐 Python | 📅 2026-08-18 - Deep learning library for solving PDEs
* [NVIDIA PhysicsNeMo](https://github.com/NVIDIA/physicsnemo) ⭐ 3,206 | 🐛 86 | 🌐 Python | 📅 2026-08-27 - Open-source framework for building physics-ML models at scale (renamed from Modulus, 2025)
* [NeuroMANCER (PNNL)](https://github.com/pnnl/neuromancer) ⭐ 1,370 | 🐛 17 | 🌐 Python | 📅 2026-08-05 - PyTorch-based differentiable programming framework for physics-informed system identification, parametric constrained optimization, and model predictive control, integrating neural operators, neural ODEs, KANs, SINDy, and differentiable predictive control with 30+ tutorials (1.3k+ stars, BSD License)
* [NeuralPDE.jl](https://github.com/SciML/NeuralPDE.jl) ⭐ 1,220 | 🐛 144 | 🌐 Julia | 📅 2026-08-27 - Physics-informed neural networks in Julia
* [PINA](https://github.com/mathLab/PINA) ⭐ 4 | 🐛 0 | 📅 2026-07-21 - Physics-Informed Neural networks for Advanced modeling in PyTorch
* [SciANN](https://github.com/sciann/sciann) ⭐ 2 | 🐛 0 | 📅 2024-09-26 - Keras-based scientific neural networks
* [Lang-PINN](https://openreview.net/forum?id=ONEyVpgK34) - LLM-driven multi-agent system that builds trainable PINNs from natural language task descriptions, achieving 3-5 orders of magnitude MSE reduction and 50%+ execution success improvement (ICLR 2026)

### Neural Operators & Model Discovery

* [pykan](https://github.com/KindXiaoming/pykan) ⭐ 16,334 | 🐛 266 | 🌐 Jupyter Notebook | 📅 2025-01-19 - Kolmogorov-Arnold Networks with learnable activation functions on edges instead of fixed node activations, achieving strong performance in function fitting, PDE solving, and scientific discovery with enhanced interpretability as an alternative to MLPs (MIT, 16.3K+ stars, 2024)
* [Fourier Neural Operator](https://github.com/neuraloperator/neuraloperator) ⭐ 3,843 | 🐛 44 | 🌐 Python | 📅 2026-08-06 - Learning operators in Fourier space
* [PySR](https://github.com/MilesCranmer/PySR) ⭐ 3,739 | 🐛 136 | 🌐 Python | 📅 2026-08-27 - High-performance symbolic regression for discovering interpretable scientific equations from data, multi-population evolutionary search with Python/Julia backend, widely used in physics and astronomy (Cambridge, NeurIPS 2023)
* [PhiFlow](https://github.com/tum-pbs/PhiFlow) ⭐ 1,928 | 🐛 30 | 🌐 Python | 📅 2026-07-16 - Differentiable PDE solving framework for machine learning with built-in fluid simulation, supporting PyTorch/JAX/TensorFlow backends and enabling neural network training within physical simulations (TUM, MIT License)
* [PySINDy](https://github.com/dynamicslab/pysindy) ⭐ 1,893 | 🐛 83 | 🌐 Python | 📅 2026-06-10 - Sparse identification of nonlinear dynamics
* [DeepONet](https://github.com/lululxvi/deeponet) ⭐ 838 | 🐛 28 | 🌐 Python | 📅 2022-06-25 - Learning nonlinear operators
* [LLM-SR](https://github.com/deep-symbolic-mathematics/LLM-SR) ⭐ 271 | 🐛 8 | 🌐 Python | 📅 2025-07-31 - Scientific equation discovery and symbolic regression using LLMs, combining code generation with evolutionary search (ICLR 2025 Oral)
* [exponax](https://github.com/Ceyron/exponax) ⭐ 230 | 🐛 17 | 🌐 Jupyter Notebook | 📅 2026-06-01 - Efficient differentiable n-dimensional PDE solvers built on JAX and Equinox, shipping 46+ built-in equations with Fourier spectral methods, exponential time differencing, and full auto-differentiation for physics-based deep learning workflows (MIT, 200+ stars, 2024)
* [TensorMesh (ETH Zurich CAMLab, arXiv 2026)](https://github.com/camlab-ethz/TensorMesh) ⭐ 218 | 🐛 3 | 🌐 Python | 📅 2026-08-04 - Fast, differentiable, JIT-free finite element library for PyTorch enabling GPU-native PDE solving with native autograd, tensorized assembly, and sparse linear algebra; part of the TensorGalerkin framework (218+ stars, Apache 2.0)
* [Poseidon](https://github.com/camlab-ethz/poseidon) ⭐ 195 | 🐛 2 | 🌐 Python | 📅 2025-04-10 - Efficient foundation models for PDEs with pretrained transformer-based neural operators and downstream task fine-tuning pipelines, HuggingFace integration for models and datasets (ETH Zurich CAMLab, arXiv 2024)
* [GAOT (NeurIPS 2025)](https://github.com/camlab-ethz/GAOT) ⭐ 105 | 🐛 2 | 🌐 Python | 📅 2025-10-23 - Geometry Aware Operator Transformer serving as an efficient and accurate neural surrogate for PDEs on arbitrary domains, combining geometric priors with transformer architectures for scientific computing (ETH Zurich CAMLab, 92+ stars)
* [PSRN](https://github.com/x66ccff/PSRN) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2026-05-17 - Parallel symbolic regression network evaluating millions of expressions on GPU with automated subtree reuse, Nature Computational Science cover article (MIT, 2026)

### Simulation-Based Inference

* [sbi](https://github.com/sbi-dev/sbi) ⭐ 859 | 🐛 65 | 🌐 Python | 📅 2026-08-20 - Python package for simulation-based inference enabling likelihood-free Bayesian parameter estimation from scientific simulators, with flexible interfaces for neural posterior estimation, sequential methods, and MCMC/variational backends (Mackelab, 825+ stars)

***

## 📖 Papers & Reviews

### Foundational Papers

* [Machine Learning for Scientometric Analysis](https://arxiv.org/abs/2109.10073) (2021.09) - Comprehensive review
* [AI for Science: Progress and Challenges](https://arxiv.org/abs/2303.04346) (2023.03) - State of the field
* [Foundation Models for Science](https://arxiv.org/abs/2205.15075) (2022.05) - Large models in research
* [Neural Ordinary Differential Equations](https://arxiv.org/abs/1806.07366) (2018.06) - Breakthrough in neural ODEs
* [Physics-Informed Neural Networks](https://arxiv.org/abs/1711.10561) (2017.11) - Physics-constrained deep learning
* [Scientific Discovery in the Age of Artificial Intelligence](https://www.nature.com/articles/s41586-023-06221-2) - Nature review on AI's role in science

### 📊 Comprehensive Surveys & Reviews (2024-2025)

#### AI for Scientific Research

* [A Survey on AI-assisted Scientific Discovery](https://arxiv.org/abs/2502.05151) (2025.02) - Comprehensive overview of LLMs in scientific research lifecycle from literature search to peer review
* [AI4Research: A Survey of Artificial Intelligence for Scientific Research](https://arxiv.org/abs/2507.01903) (2025.07) - Systematic taxonomy of AI in research
* [Artificial Intelligence for Science in Quantum, Atomistic, and Continuum Systems](https://arxiv.org/abs/2307.08423) (2023.07) - Unified technical survey across scientific scales with 63 contributors
* [From Automation to Autonomy: A Survey on Large Language Models in Scientific Discovery](https://arxiv.org/abs/2505.13259) (2025.05) - Three-level taxonomy (Tool, Analyst, Scientist)
* [From AI for Science to Agentic Science: A Survey on Autonomous Scientific Discovery](https://arxiv.org/abs/2508.14111) (2025.08) - Comprehensive survey on agentic science across life sciences, chemistry, materials, and physics
* [Agentic AI for Scientific Discovery: A Survey of Progress, Challenges, and Future Directions](https://arxiv.org/abs/2503.08979) (2025.03) - Comprehensive review of AI agents in science
* [Towards Scientific Intelligence: A Survey of LLM-based Scientific Agents](https://arxiv.org/abs/2503.24047) (2025.03) - Scientific AI agent systems

#### Scientific Large Language Models

* [A Comprehensive Survey of Scientific Large Language Models and Their Applications](https://arxiv.org/abs/2406.10833) (2024.06) - 260+ scientific LLMs across domains
* [A Survey of Scientific Large Language Models: From Data Foundations to Agent Frontiers](https://arxiv.org/abs/2508.21148) (2025.08) - Data-centric view of scientific LLMs
* [Scientific Large Language Models: A Survey on Biological & Chemical Domains](https://arxiv.org/abs/2401.14656) (2024.01) - Domain-specific scientific LLMs

#### Scientific Machine Learning

* [Scientific Machine Learning through Physics-Informed Neural Networks: Where we are and What's next](https://arxiv.org/abs/2201.05624) (2022.01) - Comprehensive PINN review
* [Physics-Informed Neural Networks and Extensions](https://arxiv.org/abs/2408.16806) (2024.08) - Recent PINN advances and variants
* [The frontier of simulation-based inference](https://www.pnas.org/doi/10.1073/pnas.1912789117) (PNAS 2020) - Foundational review on SBI for scientific computing by Cranmer et al.
* [From Theory to Application: A Practical Introduction to Neural Operators in Scientific Computing](https://arxiv.org/abs/2503.05598) (2025.03) - Implementation-focused guide to DeepONet, FNO, and PCANet
* [Architectures, variants, and performance of neural operators: A comparative review](https://www.sciencedirect.com/science/article/abs/pii/S0925231225011907) (2025) - Systematic analysis of DeepONets, integral kernel operators, and transformer-based neural operators
* [Foundation Models for Environmental Science: A Survey](https://arxiv.org/abs/2504.04280) (2025.04) - Environmental applications
* [Foundation Models in Bioinformatics](https://academic.oup.com/nsr/article/12/4/nwaf028/7979309) - Biological foundation models
* [Foundation Models for Materials Discovery](https://www.nature.com/articles/s41524-025-01538-0) (2025) - Perspective on materials AI

#### Uncertainty Quantification

* [Uncertainty quantification in scientific machine learning: Methods, metrics, and comparisons](https://www.sciencedirect.com/science/article/abs/pii/S0021999122009652) (J. Comput. Phys. 2023) - Comprehensive framework for UQ in PINNs and neural operators by Psaros et al.
* [A Survey on Uncertainty Quantification Methods for Deep Learning](https://arxiv.org/abs/2302.13425) (2023) - Systematic taxonomy of UQ methods from uncertainty source perspective

#### Automation & Self-Driving Laboratories

* [Self-Driving Laboratories for Chemistry and Materials Science](https://pubs.acs.org/doi/10.1021/acs.chemrev.4c00055) (Chem. Rev. 2024) - Comprehensive 100-page review on SDL technology, applications, and infrastructure
* [Autonomous 'self-driving' laboratories: a review of technology and policy implications](https://royalsocietypublishing.org/doi/10.1098/rsos.250646) (Royal Soc. Open Sci. 2025) - Technology review with policy and safety considerations

#### Policy & Strategic Perspectives

* [Artificial Intelligence for Science](https://www.csiro.au/-/media/d61/ai4science-report/ai-for-science-report-2022.pdf) (CSIRO 2022) - Landmark report analyzing AI adoption across 98% of scientific fields over 60 years
* [AI for Science 2025](https://www.nature.com/articles/d42473-025-00161-3) (Fudan University & Nature 2025) - Comprehensive report on AI's transformative impact across 7 scientific fields, 28 research directions, and 90+ challenges
* [AI in science evidence review](https://scientificadvice.eu/scientific-outputs/ai-in-science-evidence-review-report/) (European Scientific Advice 2024) - Policy-focused evidence review on AI's impact in research

### 🚀 AI Scientist & Autonomous Research (2024-2025 Breakthroughs)

* [The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery](https://arxiv.org/abs/2408.06292) (2024.08) - First fully autonomous research system
* [The AI Scientist-v2: Workshop-Level Automated Scientific Discovery via Agentic Tree Search](https://arxiv.org/abs/2504.08066) (2025.04) - Enhanced autonomous research with agentic tree search
* [AI-Researcher: Autonomous Scientific Innovation](https://arxiv.org/abs/2505.18705) (2025.05) - Autonomous research pipeline from literature to publication with Scientist-Bench evaluation framework
* [InternAgent: When Agent Becomes the Scientist -- Building Closed-Loop System from Hypothesis to Verification](https://arxiv.org/abs/2505.16938) (2025.05) - Multi-agent system achieving #1 on MLE-Bench with closed-loop research automation
* [Autonomous Scientific Discovery Through Hierarchical AI Scientist Systems](https://arxiv.org/abs/2507.15951) (2025.07) - Self-evolving multi-agent research systems
* [ChemCrow: Augmenting large-language models with chemistry tools](https://arxiv.org/abs/2304.05376) (2023.04) - LLM agents for chemistry research
* [Autonomous chemical research with large language models](https://www.nature.com/articles/s41586-023-06792-0) - Automated chemical experimentation
* [Coscientist: Autonomously planning and executing scientific experiments](https://www.nature.com/articles/s41586-023-06792-1) - Robotic lab automation
* [The AutoResearch Moment: From Experimenter to Research Director](https://www.preprints.org/manuscript/202603.1329) (2026.03) - Position paper on claim governance for autonomous research: proposes a research-director bundle (objective sheet, discovery trace, verification ledger, provenance bundle) for evaluating agent-driven science

### Recent Advances & Domain Applications

* [AlphaFold: Protein Structure Prediction](https://www.nature.com/articles/s41586-021-03819-2)
* [AI for Materials Discovery](https://www.nature.com/articles/s41578-023-00540-6)
* [Large Language Models in Chemistry](https://arxiv.org/abs/2402.05852) (2024.02)
* [Cell2Sentence: Teaching Large Language Models the Language of Biology](https://arxiv.org/abs/2405.06147) (ICML 2024) - LLMs for single-cell transcriptomics
* [Scaling Large Language Models for Next-Generation Single-Cell Analysis](https://www.biorxiv.org/content/10.1101/2025.04.14.648850v2) (2025.04) - 27B parameter biological language models
* [Boltz-1: Democratizing Biomolecular Interaction Modeling](https://www.biorxiv.org/content/10.1101/2024.11.19.624167v2) (bioRxiv 2024) - First fully open-source model achieving AlphaFold3-level accuracy
* [MOOSE: Large Language Models for Automated Open-domain Scientific Hypotheses Discovery](https://arxiv.org/abs/2309.02726) (ACL 2024) - First work showing LLMs can generate novel and valid scientific hypotheses, ICML Best Poster Award
* [Earth-Agent: Unlocking the Full Landscape of Earth Observation with Agents](https://arxiv.org/abs/2509.23141) (2025.09) - LLM agent framework for Earth Observation with 104 specialized tools and multi-modal analysis
* [MedAgents: Large Language Models as Collaborators for Zero-shot Medical Reasoning](https://arxiv.org/abs/2311.10537) (ACL 2024) - Multi-disciplinary collaboration framework for medical reasoning using role-playing LLM agents
* [MedAgentGym: A Scalable Agentic Training Environment for Code-Centric Reasoning in Biomedical Data Science](https://arxiv.org/abs/2506.04405) (2025.06) - Specialized training environment for biomedical AI agents with code-centric reasoning
* [Paper2Web: Let's Make Your Paper Alive!](https://arxiv.org/abs/2510.15842) (2025.10) - AI-powered transformation of academic papers into interactive websites with comprehensive evaluation framework
* [DeepAnalyze: Agentic Large Language Models for Autonomous Data Science](https://arxiv.org/abs/2510.16872) (2025.10) - First agentic LLM for autonomous data science with curriculum-based training
* [Democratizing AI scientists using ToolUniverse](https://arxiv.org/abs/2509.23426) (2025.09) - Universal ecosystem for building AI scientists from any LLM with 600+ scientific tools
* [TxAgent: An AI Agent for Therapeutic Reasoning Across a Universe of Tools](https://arxiv.org/abs/2503.10970) (2025.03) - AI agent achieving 92.1% accuracy in drug reasoning, outperforming GPT-4o by 25.8%
* [Aviary: Training Language Agents on Challenging Scientific Tasks](https://arxiv.org/abs/2412.21154) (2024.12) - Language agent training framework for scientific discovery
* [Galactica: A Large Language Model for Science](https://arxiv.org/abs/2211.09085) (2022.11)

### 📈 Evaluation & Benchmarking

* [Scientist-Bench](https://github.com/HKUDS/AI-Researcher) ⭐ 5,704 | 🐛 67 | 🌐 Python | 📅 2025-10-16 - Comprehensive benchmark for comparing LLM Agent-generated research outcomes with high-quality scientific work
* [ScienceAgentBench (ICLR 2025)](https://github.com/OSU-NLP-Group/ScienceAgentBench) ⭐ 165 | 🐛 0 | 🌐 Python | 📅 2026-07-18 - 102 executable tasks from 44 peer-reviewed papers across 4 disciplines with containerized evaluation
* [SciTrust: Evaluating the Trustworthiness of Large Language Models for Science](https://impact.ornl.gov/en/publications/scitrust-evaluating-the-trustworthiness-of-large-language-models-) (2024) - Scientific LLM trustworthiness evaluation framework
* [SciBench: Evaluating College-Level Scientific Problem-Solving Abilities](https://arxiv.org/abs/2307.10635) (2023) - Scientific reasoning benchmarks
* [ChartCoder Evaluation](https://aclanthology.org/2025.acl-long.363/) - Chart-to-code generation benchmarks

***

## 🔬 Domain-Specific Applications

### 🧬 Biology & Medicine

#### Protein & Drug Discovery

* [AlphaFold](https://github.com/google-deepmind/alphafold) ⭐ 14,813 | 🐛 307 | 🌐 Python | 📅 2026-04-22 - Protein structure prediction
* [AlphaFold3](https://github.com/google-deepmind/alphafold3) ⭐ 8,500 | 🐛 17 | 🌐 Python | 📅 2026-08-19 - AlphaFold 3 inference pipeline for unified biomolecular structure prediction of proteins, nucleic acids, small molecules, ions, and post-translational modifications (Google DeepMind, Nature 2024)
* [DeepChem](https://github.com/deepchem/deepchem) ⭐ 6,964 | 🐛 1,167 | 🌐 Python | 📅 2026-08-20 - Machine learning for chemistry
* [Boltz](https://github.com/jwohlwend/boltz) ⭐ 4,182 | 🐛 152 | 🌐 Python | 📅 2026-05-29 - First fully open-source model achieving AlphaFold3-level accuracy with 1000x faster binding affinity prediction (MIT)
* [Boltz-2 (MIT & Recursion, 2025)](https://github.com/jwohlwend/boltz) ⭐ 4,182 | 🐛 152 | 🌐 Python | 📅 2026-05-29 - Next-generation biomolecular foundation model jointly predicting protein-ligand complex structures and binding affinities in a single framework; achieves FEP-level accuracy with \~0.62 Pearson correlation on FEP+ benchmark in \~20 seconds, outperforming all methods at CASP16 affinity challenge and doubling average precision in MF-PCBA hit-discovery screens (MIT License)
* [ESMFold](https://github.com/facebookresearch/esm) ⚠️ Archived - Protein structure prediction from ESM models
* [RDKit](https://github.com/rdkit/rdkit) ⭐ 3,567 | 🐛 66 | 🌐 HTML | 📅 2026-08-28 - Cheminformatics toolkit
* [OpenFold](https://github.com/aqlaboratory/openfold) ⭐ 3,420 | 🐛 245 | 🌐 Python | 📅 2025-12-16 - Trainable, memory-efficient PyTorch reproduction and retraining of AlphaFold2 providing new insights into its learning dynamics and out-of-distribution generalization; widely used as the open-source AlphaFold2 backbone underpinning many downstream protein structure prediction and design pipelines (Columbia AlQuraishi Lab & OpenFold Consortium, Nature Methods 2024)
* [RFdiffusion3](https://github.com/RosettaCommons/RFdiffusion) ⭐ 3,028 | 🐛 244 | 🌐 Python | 📅 2026-07-15 - Latest RFdiffusion for protein structure design with 10× speedup and atom-level precision (December 2025)
* [ESM3](https://github.com/evolutionaryscale/esm) ⭐ 2,929 | 🐛 73 | 🌐 Jupyter Notebook | 📅 2026-08-27 - 98B-parameter frontier generative model jointly reasoning over protein sequence, structure, and function, trained on 2.78 billion proteins; generated a novel fluorescent protein (esmGFP) with only 58% sequence identity to known GFPs (EvolutionaryScale, 2024)
* [ColabFold (2025 Updates)](https://github.com/sokrypton/ColabFold) ⭐ 2,892 | 🐛 408 | 🌐 Jupyter Notebook | 📅 2026-08-28 - AlphaFold/ESMFold accessible implementation with AF3 JSON export, database updates
* [Graphormer](https://github.com/microsoft/Graphormer) ⭐ 2,473 | 🐛 101 | 🌐 Python | 📅 2026-06-12 - General-purpose deep learning backbone for molecular modeling
* [Chemprop](https://github.com/chemprop/chemprop) ⭐ 2,438 | 🐛 14 | 🌐 Python | 📅 2026-08-21 - Message passing neural networks for molecule property prediction, ADMET modeling, and reaction prediction, achieving SOTA on MoleculeNet and widely used in pharmaceutical drug discovery (MIT, 2.3K+ stars)
* [Protenix](https://github.com/bytedance/Protenix) ⭐ 2,041 | 🐛 121 | 🌐 Python | 📅 2026-08-01 - Trainable PyTorch reproduction of AlphaFold 3
* [Chai-1](https://github.com/chaidiscovery/chai-lab) ⭐ 1,987 | 🐛 93 | 🌐 Python | 📅 2026-06-30 - Multi-modal foundation model for biomolecular structure prediction (proteins, small molecules, DNA, RNA, glycans) achieving SOTA across benchmarks, with optional MSA/template support (Chai Discovery, 2024)
* [ProteinMPNN](https://github.com/dauparas/ProteinMPNN) ⭐ 1,835 | 🐛 88 | 🌐 Jupyter Notebook | 📅 2024-08-14 - Deep learning-based protein sequence design (inverse folding) from backbone structures, achieving 52.4% sequence recovery vs 32.9% for Rosetta, core tool in modern protein design pipelines (Baker Lab, Science 2022)
* [TorchDrug](https://github.com/DeepGraphLearning/torchdrug) ⭐ 1,587 | 🐛 124 | 🌐 Python | 📅 2024-08-12 - Powerful and flexible machine learning platform for drug discovery, providing comprehensive tools for molecular property prediction, generative models, knowledge graph reasoning, and reaction prediction with PyTorch backend (1.5K+ stars)
* [DiffDock](https://github.com/gcorso/DiffDock) ⭐ 1,569 | 🐛 132 | 🌐 Python | 📅 2025-05-02 - Diffusion-based molecular docking achieving SOTA blind docking performance, treating ligand pose prediction as generative diffusion over SE(3), with DiffDock-L update for improved generalization (MIT CSAIL, ICLR 2023)
* [ProtTrans](https://github.com/agemagician/ProtTrans) ⭐ 1,324 | 🐛 21 | 🌐 Jupyter Notebook | 📅 2025-05-22 - State-of-the-art pretrained language models for proteins trained on thousands of GPUs and Google TPUs using Transformer architectures, enabling protein property prediction, feature extraction, and transfer learning across diverse downstream tasks (1.3K+ stars, MIT, 2020-2026)
* [Foldseek](https://github.com/steineggerlab/foldseek) ⭐ 1,286 | 🐛 187 | 🌐 C | 📅 2026-08-24 - Fast and accurate protein structure search using a learned 3Di structural alphabet (VQ-VAE) that discretizes tertiary interactions into structural tokens, enabling protein-universe-scale structural alignment at sequence-search speeds (4-5 orders of magnitude faster than DALI/TM-align) and underpinning many AI4S tools such as SaProt, ESMAtlas search, and AFDB clustering pipelines (Steinegger Lab, Nature Biotechnology 2023)
* [BindCraft](https://github.com/martinpacesa/BindCraft) ⭐ 1,196 | 🐛 17 | 🌐 Python | 📅 2026-08-12 - Simple and accurate de novo protein binder design pipeline using AlphaFold2 backpropagation, MPNN, and PyRosetta for automated binder discovery (bioRxiv 2024)
* [Uni-Mol](https://github.com/deepmodeling/Uni-Mol) ⭐ 1,156 | 🐛 113 | 🌐 Python | 📅 2025-05-29 - Universal 3D molecular pretraining framework with 209M conformations, scaling to 1.1B parameters (Uni-Mol2) on 800M conformations for molecular property prediction, docking, and quantum chemistry (ICLR 2023, NeurIPS 2024)
* [AiCE (Cell 2025)](https://github.com/ScorpioLea/AiCE) ⭐ 1,144 | 🐛 10 | 🌐 Jupyter Notebook | 📅 2025-09-30 - AI-assisted mutation nomination approach optimizing protein function by integrating structural and evolutionary constraints into protein inverse folding models, compatible with ProteinMPNN, LigandMPNN, ESM-IF1, and SaProt (Chinese Academy of Sciences, 359+ stars)
* [HelixFold3](https://github.com/PaddlePaddle/PaddleHelix/tree/dev/apps/helixfold3) ⭐ 1,119 | 🐛 75 | 🌐 Python | 📅 2026-03-31 - Baidu's open-source reproduction of AlphaFold3 in PaddlePaddle, providing pretrained weights and inference pipelines for unified biomolecular structure prediction across proteins, nucleic acids, ligands, ions, and post-translational modifications within the PaddleHelix biocomputing platform (Baidu, bioRxiv 2024)
* [SimpleFold (Apple, arXiv 2025)](https://github.com/apple/ml-simplefold) ⭐ 986 | 🐛 39 | 🌐 Python | 📅 2026-02-24 - Flow-matching protein folding model using only general-purpose transformer layers, scaled to 3B parameters and trained on 8.6M+ distilled structures; challenges the reliance on complex domain-specific architectures and supports PyTorch and MLX backends with model sizes from 100M to 3B parameters (985+ stars, MIT License)
* [GNINA](https://github.com/gnina/gnina) ⭐ 966 | 🐛 24 | 🌐 C++ | 📅 2026-06-29 - Deep learning framework for molecular docking extending AutoDock Vina with convolutional neural network scoring functions, achieving superior virtual screening enrichment and pose prediction across diverse target classes; widely adopted in pharmaceutical structure-based drug design (J. Cheminformatics, 915+ stars, actively maintained)
* [ColabDesign](https://github.com/sokrypton/ColabDesign) ⭐ 933 | 🐛 65 | 🌐 Python | 📅 2026-08-28 - Accessible protein design platform via Google Colab integrating AlphaFold2, RoseTTAFold, and ProteinMPNN for de novo hallucination, fixed backbone design, and binder design (Sergey Ovchinnikov, 2022+)
* [BioEmu](https://github.com/microsoft/bioemu) ⭐ 872 | 🐛 1 | 🌐 Python | 📅 2026-08-27 - Microsoft's generative model for sampling protein equilibrium conformations 100,000× faster than MD simulations, predicting domain motions, local unfolding and cryptic binding pockets on a single GPU (Science 2025)
* [OpenFold3](https://github.com/aqlaboratory/openfold-3) ⭐ 843 | 🐛 73 | 🌐 Python | 📅 2026-08-28 - Fully open-source (Apache 2.0) biomolecular structure prediction reproducing AlphaFold3, free for academic and commercial use (Columbia AlQuraishi Lab & OpenFold Consortium, 2025)
* [Chroma](https://github.com/generatebio/chroma) ⭐ 828 | 🐛 27 | 🌐 Python | 📅 2024-04-11 - Generative model for programmable protein design using diffusion modeling, equivariant graph neural networks, and conditional random fields to efficiently sample diverse all-atom structures; supports conditional generation via composable conditioners for substructure, symmetry, shape, and neural-network predictions; validated crystallographically (Generate Biomedicines, Nature 2023)
* [RoseTTAFold-All-Atom](https://github.com/baker-laboratory/RoseTTAFold-All-Atom) ⭐ 818 | 🐛 112 | 🌐 Python | 📅 2026-05-18 - All-atom biomolecular structure prediction for protein-nucleic acid-small molecule-metal ion complexes, enabling accurate modeling of covalent modifications and assemblies beyond proteins (Baker Lab, Science 2024)
* [dynamicPDB (AAAI 2025)](https://github.com/fudan-generative-vision/dynamicPDB) ⭐ 785 | 🐛 5 | 🌐 Python | 📅 2025-08-11 - Dynamic Protein Data Bank integrating dynamic behaviors and physical properties into protein structures via a new dataset and SE(3) model extension, enabling richer understanding of protein conformational landscapes (Fudan University, 784+ stars)
* [EvoDiff](https://github.com/microsoft/evodiff) ⭐ 681 | 🐛 14 | 🌐 Python | 📅 2026-01-15 - Discrete diffusion framework for generative protein sequence design over evolutionary-scale databases, supporting unconditional generation, evolutionary-guided conditional design, motif scaffolding, and intrinsically disordered region generation through order-agnostic autoregressive diffusion, enabling sequence-only protein design without structural priors (Microsoft Research, Nature Communications 2024)
* [LigandMPNN](https://github.com/dauparas/LigandMPNN) ⭐ 627 | 🐛 48 | 🌐 Python | 📅 2025-02-06 - Extension of ProteinMPNN for protein sequence design in the context of small-molecule ligands, metal ions, and nucleic acids, enabling binding site engineering and co-factor redesign (Baker Lab)
* [SaProt](https://github.com/westlake-repl/SaProt) ⭐ 627 | 🐛 26 | 🌐 Python | 📅 2026-03-08 - Structure-aware protein language model using 3D structural vocabulary (Foldseek) for joint sequence-structure pretraining, achieving SOTA on protein engineering and fitness prediction benchmarks (ICML 2024, Westlake University & Repl)
* [AlphaFlow](https://github.com/bjing2016/alphaflow) ⭐ 543 | 🐛 31 | 🌐 Python | 📅 2026-03-22 - AlphaFold fine-tuned with flow matching for generating protein conformational ensembles, covering both experimental PDB states and molecular dynamics ensembles at physiological temperatures; includes ESMFlow variant (MIT, 526+ stars, 2024)
* [RFantibody](https://github.com/RosettaCommons/RFantibody) ⭐ 526 | 🐛 87 | 🌐 Python | 📅 2026-03-05 - Structure-based de novo antibody design pipeline built on RFdiffusion for computational generation of target-specific antibodies (RosettaCommons, 2025)
* [ChemBERTa](https://github.com/seyonechithrananda/bert-loves-chemistry) ⭐ 501 | 🐛 10 | 🌐 Jupyter Notebook | 📅 2024-10-27 - Chemical language model
* [OpenDDE (Aureka Research, 2026)](https://github.com/aurekaresearch/OpenDDE) ⭐ 432 | 🐛 10 | 🌐 Python | 📅 2026-08-16 - Open-source, all-atom biomolecular foundation model that turns co-folding into a scalable engine for structure prediction, design, and optimization across proteins, nucleic acids, and small molecules in drug discovery; ranked first on PXMeter-AB, FoldBench-AB, and 2026ARK-AB antibody-antigen benchmarks (263+ stars, Apache 2.0)
* [Proteina-Complexa](https://github.com/NVIDIA-Digital-Bio/Proteina-Complexa) ⭐ 420 | 🐛 31 | 🌐 Python | 📅 2026-08-27 - Flow-based generative model for atomistic protein binder design with test-time optimization, SOTA on binder benchmarks (ICLR 2026 Oral, NVIDIA)
* [CryoDRGN](https://github.com/ml-struct-bio/cryodrgn) ⭐ 388 | 🐛 113 | 🌐 Python | 📅 2026-08-04 - Neural network-based cryo-EM heterogeneous reconstruction, modeling continuous 3D structure distributions from single-particle images, with CryoDRGN-ET extending to in-cell cryo-electron tomography (MIT CSAIL, Nature Methods 2021/2024)
* [REINVENT](https://github.com/MolecularAI/Reinvent) ⚠️ Archived - Industrial-grade reinforcement-learning-based generative platform for de novo molecular design with transformer architectures, supporting multi-objective optimization, scaffold decoration, and curriculum learning (AstraZeneca MolecularAI, REINVENT 4, 2024)
* [EVOLVEpro](https://github.com/mat10d/EvolvePro) ⭐ 376 | 🐛 2 | 🌐 Python | 📅 2025-06-11 - In silico directed evolution framework using few-shot active learning to optimize protein activities, enabling rapid protein engineering with minimal experimental data (352+ stars, 2023)
* [mosaic](https://github.com/escalante-bio/mosaic) ⭐ 359 | 🐛 6 | 🌐 Python | 📅 2026-08-11 - Composite-objective protein design framework integrating Boltz, AlphaFold2, OpenFold3, ProteinMPNN, and ESM via JAX-based gradient optimization over continuous relaxed sequence space for multi-property binder design (319+ stars, MIT License, 2025)
* [targetdiff](https://github.com/guanjq/targetdiff) ⭐ 347 | 🐛 13 | 🌐 Python | 📅 2024-01-10 - 3D Equivariant Diffusion for Target-Aware Molecule Generation (ICLR2023)
* [DPLM (ByteDance, ICML 2024 / ICLR 2025)](https://github.com/bytedance/dplm) ⭐ 343 | 🐛 8 | 🌐 Python | 📅 2025-07-25 - Family of diffusion protein language models demonstrating versatile generative and predictive capabilities for protein sequences and structures, including multimodal co-generation, conditional folding, inverse folding, motif scaffolding, and representation learning, with open pretrained weights and training scripts (327+ stars, ICML 2024, ICLR 2025, ICML 2025 Spotlight)
* [NeuralPLexer](https://github.com/zrqiao/NeuralPLexer) ⭐ 336 | 🐛 41 | 🌐 Jupyter Notebook | 📅 2025-10-06 - State-specific protein-ligand complex structure prediction with a multi-scale deep generative model, enabling conformational state-aware modeling of molecular interactions (329+ stars, 2024)
* [ODesign (OTeam-AI4S, 2025)](https://github.com/OTeam-AI4S/ODesign) ⭐ 336 | 🐛 10 | 🌐 Python | 📅 2026-07-01 - All-atom generative world model for all-to-all biomolecular interaction design, enabling cross-modality generation of proteins, nucleic acids, small molecules, and cyclic peptides with fine-grained epitope-level control and 2-4 orders of magnitude faster design throughput than modality-specific baselines (316+ stars, Apache 2.0)
* [AlphaPulldown](https://github.com/KosinskiLab/AlphaPulldown) ⭐ 321 | 🐛 1 | 🌐 Python | 📅 2026-08-27 - Automated pipeline for proteome-scale protein-protein interaction screening with AlphaFold-Multimer and AlphaFold 3, supporting flexible inputs (UniProt IDs, FASTA, residue regions, multimers, AF3 JSON features) and integrated downstream analysis for hit prioritization (Kosinski Lab, EMBL, Nature Protocols 2024, 317+ stars, GPL-3.0)
* [ProstT5 (NAR Genomics and Bioinformatics 2024)](https://github.com/mheinzinger/ProstT5) ⭐ 320 | 🐛 18 | 🌐 Jupyter Notebook | 📅 2026-03-06 - Bilingual protein language model translating between protein sequence and structure, finetuned from ProtT5-XL on 17M AlphaFoldDB structures using Foldseek's 3Di structural alphabet, enabling sequence-to-structure prediction, structure-to-sequence inverse folding, and unified protein representation learning (RostLab, 310+ stars)
* [La-Proteina (NVIDIA)](https://github.com/NVIDIA-Digital-Bio/la-proteina) ⭐ 309 | 🐛 11 | 🌐 Python | 📅 2025-09-23 - Partially latent flow matching model for the joint generation of a protein's amino acid sequence and full atomistic structure, including both backbone and side chains (2025)
* [DynamicBind (NeurIPS 2024)](https://github.com/luwei0917/DynamicBind) ⭐ 306 | 🐛 40 | 🌐 Jupyter Notebook | 📅 2025-12-23 - Deep equivariant generative model predicting ligand-specific protein-ligand complex structures with dynamic receptor conformational flexibility, enabling accurate docking for flexible protein targets
* [InterPLM (Nature Methods 2025)](https://github.com/ElanaPearl/InterPLM) ⭐ 301 | 🐛 9 | 🌐 Python | 📅 2025-10-31 - Discovering interpretable features in protein language models via sparse autoencoders, enabling mechanistic understanding of PLM representations for protein engineering and design (288+ stars, MIT License)
* [Mol-Instructions](https://github.com/zjunlp/Mol-Instructions) ⭐ 294 | 🐛 1 | 🌐 Python | 📅 2024-10-28 - Large-scale biomolecular instruction dataset for chemistry/biology LLMs (ICLR2024)
* [nvMolKit (NVIDIA BioNeMo, 2025)](https://github.com/NVIDIA-BioNeMo/nvMolKit) ⭐ 273 | 🐛 14 | 🌐 Cuda | 📅 2026-08-27 - High-performance, GPU-accelerated library for key computational chemistry tasks including molecular similarity, conformer generation, and geometry relaxation, designed to accelerate drug-discovery and molecular-modeling workflows (264+ stars, Apache 2.0)
* [Proteina (NVIDIA, ICLR 2025 Oral)](https://github.com/NVIDIA-Digital-Bio/proteina) ⭐ 272 | 🐛 7 | 🌐 Python | 📅 2025-07-24 - Large-scale flow-based protein backbone generator utilizing hierarchical fold class labels for conditioning with a tailored scalable transformer architecture, enabling controllable de novo protein design (264+ stars)
* [PLACER](https://github.com/baker-laboratory/PLACER) ⭐ 263 | 🐛 9 | 🌐 Python | 📅 2025-11-05 - Graph neural network operating entirely at the atomic level for protein-ligand conformational ensemble prediction and docking, generating diverse solutions through rapid stochastic denoising to model conformational heterogeneity (Baker Lab, bioRxiv 2025)
* [PXDesign (ByteDance, 2025)](https://github.com/bytedance/PXDesign) ⭐ 250 | 🐛 14 | 🌐 Python | 📅 2025-12-31 - Fast, modular, and accurate de novo design of protein binders based on the Protenix foundation model, achieving 17-82% nanomolar hit rates across diverse targets with 2-6× improvement over prior methods like AlphaProteo and RFdiffusion (229+ stars, Apache 2.0)
* [IntelliFold](https://github.com/IntelliGen-AI/IntelliFold) ⭐ 228 | 🐛 0 | 🌐 Python | 📅 2026-06-23 - Controllable foundation model for general and specialized biomolecular structure prediction across proteins, nucleic acids, and complexes, featuring a public web server for interactive prediction workflows (IntelliGen AI, 223+ stars, Apache 2.0, 2025)
* [IgGM](https://github.com/TencentAI4S/IgGM) ⭐ 222 | 🐛 13 | 🌐 Python | 📅 2026-05-28 - Generative foundation model for functional antibody and nanobody design, supporting de novo generation, affinity maturation, inverse design, structure prediction, and humanization (Tencent AI4S, ICLR 2025)
* [DISCO](https://github.com/DISCO-design/DISCO) ⭐ 215 | 🐛 2 | 🌐 Python | 📅 2026-05-13 - General multimodal protein design framework enabling DNA-encoding of chemistry for programmable enzyme design and diverse protein generation through diffusion-based generative modeling (190+ stars, Apache 2.0, 2026)
* [GenMol](https://github.com/NVIDIA-Digital-Bio/genmol) ⭐ 198 | 🐛 2 | 🌐 Python | 📅 2026-01-14 - ICML 2025 drug discovery generalist using masked discrete diffusion and fragment-based generation with molecular context guidance (NVIDIA)
* [Genie 2](https://github.com/aqlaboratory/genie2) ⭐ 195 | 🐛 8 | 🌐 Python | 📅 2024-06-24 - Diffusion model for scalable protein structure design with multi-motif scaffolding capabilities, achieving state-of-the-art designability, diversity, and novelty through SE(3)-equivariant attention and massive data augmentation (AlQuraishi Lab, 2024)
* [DeepMol](https://github.com/BioSystemsUM/DeepMol) ⭐ 180 | 🐛 17 | 🌐 Python | 📅 2026-03-26 - Unified ML/DL framework for drug discovery workflows, integrating RDKit, DeepChem, and scikit-learn with SHAP explainability
* [ModelAngelo](https://github.com/3dem/model-angelo) ⭐ 173 | 🐛 44 | 🌐 Python | 📅 2026-06-15 - Automatic atomic model building program for cryo-EM maps using deep learning, enabling rapid de novo protein structure determination from electron density with high accuracy (3DEM/EMBL, 169+ stars)
* [mint](https://github.com/VarunUllanat/mint) ⭐ 155 | 🐛 3 | 🌐 Python | 📅 2026-06-15 - Learning the language of protein-protein interactions
* [DrugAssist](https://github.com/blazerye/DrugAssist) ⭐ 146 | 🐛 0 | 🌐 Python | 📅 2025-04-02 - LLM-based molecular optimization tool
* [RareFold](https://github.com/PatrickBryant1/RareFold) ⭐ 145 | 🐛 4 | 🌐 Python | 📅 2026-02-01 - Structure prediction and design of proteins with noncanonical amino acids, enabling AI-powered modeling of synthetic biology constructs and expanded genetic code systems (133+ stars, 2025)
* [Genie 3 (AlQuraishi Lab, 2026)](https://github.com/aqlaboratory/genie3) ⭐ 130 | 🐛 4 | 🌐 Python | 📅 2026-05-10 - Fast, all-atom SE(3)-equivariant diffusion model for protein design achieving state-of-the-art performance on unconditional generation, motif scaffolding, and binder design while retaining the computational efficiency of equivariant architectures (bioRxiv 2026)
* [SwitchCraft](https://github.com/bjing2016/switchcraft) ⭐ 89 | 🐛 2 | 🌐 Python | 📅 2026-06-01 - Programmatic framework for designing state-switching proteins via backpropagation through compositional design constraints parameterized by structure prediction models; enables de novo design of allosteric regulators and fluorescent biosensors for arbitrary small-molecule analytes (79+ stars, MIT License, ICML 2026)
* [ReQFlow](https://github.com/AngxiaoYue/ReQFlow) ⭐ 85 | 🐛 2 | 🌐 Python | 📅 2026-02-12 - Rectified Quaternion Flow for efficient protein backbone generation, 37× faster than RFDiffusion with 0.972 designability (ICML 2025)
* [MegaFold](https://github.com/Supercomputing-System-AI-Lab/MegaFold/) ⭐ 77 | 🐛 1 | 🌐 Python | 📅 2026-06-16 - Cross-platform system optimizations for accelerating AlphaFold3 training with 1.73x speedup and 1.23x memory reduction
* [STARLING (Holehouse Lab, Nature 2026)](https://github.com/idptools/starling) ⭐ 76 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2026-08-22 - Latent-space probabilistic denoising diffusion model for predicting coarse-grained conformational ensembles of intrinsically disordered proteins and regions from sequence, with GPU/CPU inference, trajectory export, and FAISS-based similarity search (67+ stars, LGPL-3.0)
* [xfold](https://github.com/Shenggan/xfold) ⭐ 58 | 🐛 2 | 🌐 Python | 📅 2026-07-03 - Democratizing AlphaFold3: PyTorch reimplementation to accelerate protein structure prediction research
* [ImmunoStruct (Nature Machine Intelligence 2025)](https://github.com/KrishnaswamyLab/ImmunoStruct) ⭐ 49 | 🐛 2 | 🌐 Python | 📅 2026-03-05 - Multimodal deep learning framework integrating peptide-MHC protein sequence, structure, and biochemical properties to predict class-I immunogenicity for infectious disease epitopes and cancer neoepitopes with cancer-wildtype contrastive learning, enabling personalized vaccine design (Krishnaswamy Lab, Yale University)
* [SeFMol (Science Advances 2026)](https://github.com/ispc-lab/SeFMol) ⭐ 34 | 🐛 1 | 🌐 Python | 📅 2026-05-02 - Semi-flexible molecular diffusion model for structure-based drug design with reinforcement learning, achieving 20× faster sampling and providing a no-code web platform for molecular design (ISPC Lab, Tongji University, 2026)
* [AlphaFold Server](https://alphafoldserver.com/) - Free, easy-to-use web platform by Google DeepMind and Isomorphic Labs for running AlphaFold 3 predictions of biomolecular structures and interactions, enabling researchers without local infrastructure to model proteins, nucleic acids, small molecules, ions, and post-translational modifications through a searchable proteome interface (2024)
* [AlphaProteo](https://github.com/google-deepmind/alphaproteo) - Deep learning system for de novo design of high-affinity protein binders, achieving strong binding across diverse target classes including challenging intracellular proteins with significantly higher success rates than traditional wet-lab screening methods (Google DeepMind, Nature 2024)
* [BoltzGen](https://arxiv.org/abs/2511.18345) - De novo protein binder design via generative model, achieving nanomolar binding for 66% of novel targets tested (MIT, 2025)
* [Open Targets](https://www.opentargets.org/) - Open-source data integration platform for systematic drug target identification and prioritization, combining genetics, genomics, chemistry, and pharmacology data from EMBL-EBI, Wellcome Sanger Institute, and pharmaceutical partners to accelerate therapeutic discovery

#### Genomics & Bioinformatics

* [Enformer](https://github.com/google-deepmind/deepmind-research/tree/master/enformer) ⭐ 15,170 | 🐛 358 | 🌐 Jupyter Notebook | 📅 2026-06-17 - Gene expression prediction
* [Evo 2](https://github.com/ArcInstitute/evo2) ⭐ 4,160 | 🐛 55 | 🌐 Jupyter Notebook | 📅 2026-06-19 - Arc Institute's 40B-parameter genome foundation model trained on 9 trillion nucleotides from all domains of life, supporting 1M base pair context for generalist DNA/RNA/protein prediction and design (Nature 2026)
* [DeepVariant](https://github.com/google/deepvariant) ⭐ 3,795 | 🐛 5 | 🌐 Python | 📅 2026-03-19 - Google DeepMind's deep learning analysis pipeline for calling genetic variants (SNPs and indels) from next-generation DNA sequencing data, achieving human expert-level accuracy and widely adopted in clinical genomics, population genetics, and precision medicine; pre-trained models available for multiple sequencing platforms and organismal genomes (Nature Biotechnology 2018, 3.7K+ stars)
* [AlphaGenome](https://github.com/google-deepmind/alphagenome) ⭐ 1,982 | 🐛 2 | 🌐 Python | 📅 2026-08-26 - Google DeepMind's unified DNA sequence foundation model predicting molecular consequences of genetic variants from single-base resolution up to 1 megabase context, jointly outputting thousands of regulatory tracks (RNA expression, splicing, chromatin accessibility, TF binding, contact maps) for human and mouse genomes via a Python client and non-commercial API (2025)
* [scvi-tools](https://github.com/scverse/scvi-tools) ⭐ 1,681 | 🐛 22 | 🌐 Python | 📅 2026-08-25 - Deep probabilistic framework for single-cell and spatial omics analysis, integrating scVI, scANVI, totalVI and other VAE-based models for batch correction, cell annotation, multi-omics integration, and RNA velocity (scverse/NumFOCUS, Nature Methods 2018/2024)
* [scGPT](https://github.com/bowang-lab/scGPT) ⭐ 1,621 | 🐛 176 | 🌐 Jupyter Notebook | 📅 2026-04-29 - Single-cell analysis with transformers
* [OpenCRISPR](https://github.com/profluent-ai/opencrispr) ⭐ 1,204 | 🐛 5 | 📅 2025-09-26 - First open-source AI-generated gene editing systems developed with protein language models, enabling programmable CRISPR-Cas nucleases for synthetic biology and therapeutic genome editing (Profluent, 2024)
* [OmicVerse](https://github.com/Starlitnightly/omicverse) ⭐ 1,190 | 🐛 12 | 🌐 Python | 📅 2026-08-28 - Unified Python framework for bulk, single-cell, and spatial RNA-seq multi-omics analysis with deep learning deconvolution (VAE) and graph neural networks, bridging Bindea, Bindea, scanpy and squidpy ecosystems (Nature Communications 2024)
* [Nucleotide Transformer](https://github.com/instadeepai/nucleotide-transformer) ⭐ 911 | 🐛 13 | 🌐 Jupyter Notebook | 📅 2026-02-24 - Foundation models for genomics and transcriptomics pretrained on 3,000+ human genomes and 850+ diverse species, enabling chromatin accessibility prediction, splice site detection, and promoter classification across multiple model scales (InstaDeep, NVIDIA & TUM, Nature Methods 2023)
* [Cell2Sentence](https://github.com/vandijklab/cell2sentence) ⭐ 878 | 🐛 13 | 🌐 Jupyter Notebook | 📅 2025-11-04 - Teaching Large Language Models the Language of Biology through single-cell transcriptomics (ICML 2024)
* [Dorado](https://github.com/nanoporetech/dorado) ⭐ 866 | 🐛 95 | 🌐 C++ | 📅 2026-08-26 - Oxford Nanopore's official deep-learning basecaller for nanopore sequencing, converting raw electrical signals into DNA/RNA sequences with integrated modified-base (methylation) detection and efficient CPU/GPU inference; foundational tool for long-read genomics, epigenetics, and real-time sequencing analysis (nanoporetech, 846+ stars, actively maintained)
* [HyenaDNA](https://github.com/HazyResearch/hyena-dna) ⭐ 807 | 🐛 38 | 🌐 Assembly | 📅 2025-04-22 - Long-range genomic foundation model using subquadratic Hyena operators instead of Transformer attention, enabling context lengths up to 1 million nucleotides for chromosome-scale DNA sequence modeling and downstream genomics tasks (Stanford Hazy Research, NeurIPS 2023, 784+ stars, Apache 2.0)
* [cellxgene (Chan Zuckerberg Initiative)](https://github.com/chanzuckerberg/cellxgene) ⭐ 785 | 🐛 137 | 🌐 JavaScript | 📅 2026-08-25 - Interactive explorer for single-cell transcriptomics data enabling visualization of UMAP/t-SNE embeddings, differential expression analysis, and cross-dataset comparison through a fast web-based interface; widely adopted for exploring atlas-scale single-cell datasets and integrating with AI/ML analysis workflows (773+ stars, MIT License)
* [DNABERT](https://github.com/jerryji1993/DNABERT) ⭐ 778 | 🐛 73 | 🌐 Python | 📅 2026-01-22 - DNA sequence analysis
* [mLLMCelltype](https://github.com/cafferychen777/mLLMCelltype) ⭐ 658 | 🐛 6 | 🌐 Python | 📅 2026-08-24 - Multi-LLM consensus framework for automated cell type annotation in single-cell transcriptomics, integrating predictions from 10+ large language models with iterative discussion and uncertainty quantification to reduce single-model biases, achieving up to 95% accuracy without reference datasets; available as CRAN R package and PyPI Python package with Scanpy/Seurat integration (2025)
* [State (Arc Institute, bioRxiv 2025)](https://github.com/ArcInstitute/state) ⭐ 651 | 🐛 62 | 🌐 Python | 📅 2026-07-24 - Machine learning model predicting cellular perturbation response across diverse contexts with State Transition (ST) and State Embedding (SE) variants, featuring CLI tooling, PyPI distribution, and Virtual Cell Challenge integration (575+ stars)
* [AlphaMissense](https://github.com/google-deepmind/alphamissense) ⚠️ Archived - Google DeepMind's AlphaFold-derived classifier for proteome-wide missense variant effect prediction, providing pathogenicity scores for all \~71M possible human missense variants and classifying 89% with 90% precision; pre-computed predictions are integrated into Ensembl VEP and UCSC Genome Browser to support clinical variant interpretation (Science 2023)
* [DNABERT-2 (ICLR 2024)](https://github.com/MAGICS-LAB/DNABERT_2) ⭐ 512 | 🐛 52 | 🌐 Shell | 📅 2026-01-01 - Efficient foundation model and benchmark for multi-species genome understanding with context-aware nucleotide representations, improving upon DNABERT for diverse genomic task transfer learning (UIUC MAGICS Lab, 484+ stars)
* [CellTypist](https://github.com/Teichlab/celltypist) ⭐ 502 | 🐛 48 | 🌐 Python | 📅 2026-05-22 - Automated cell type annotation tool for single-cell transcriptomics using gradient boosting and logistic regression with reference atlases, enabling standardized classification across datasets (Wellcome Sanger Institute, Nature Biotechnology 2022)
* [GENERator (bioRxiv 2026)](https://github.com/GenerTeam/GENERator) ⭐ 463 | 🐛 0 | 🌐 Python | 📅 2026-07-05 - Long-context generative genomic foundation model using 6-mer tokenization for DNA sequence modeling and generation, with v2 model families for prokaryote and eukaryote genomes and pretrained weights available on HuggingFace (GenerTeam, 460+ stars, MIT License, 2025-2026)
* [CellRank](https://github.com/scverse/cellrank) ⭐ 456 | 🐛 3 | 🌐 Python | 📅 2026-08-24 - Probabilistic framework for inferring cell fate decisions and trajectory dynamics from multi-view single-cell data using Markov chains and machine learning, integrating RNA velocity, pseudotime, and metabolic labeling to predict differentiation paths and terminal states (scverse/Theis Lab, 449+ stars, BSD 3-Clause)
* [scFoundation](https://github.com/biomap-research/scFoundation) ⭐ 427 | 🐛 31 | 🌐 Jupyter Notebook | 📅 2025-11-23 - 100M-parameter foundation model pretrained on 50M+ human single-cell transcriptomes covering \~20,000 genes, achieving SOTA on gene expression enhancement, drug response and perturbation prediction (Nature Methods 2024)
* [BioReason (NeurIPS 2025)](https://github.com/bowang-lab/BioReason) ⭐ 402 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-05-28 - First architecture deeply integrating a DNA foundation model with an LLM for multimodal biological reasoning, achieving 98% accuracy on KEGG disease pathway prediction and 15%+ average gains on variant effect prediction with interpretable step-by-step reasoning traces (bowang-lab, 390+ stars)
* [GEARS](https://github.com/snap-stanford/GEARS) ⭐ 399 | 🐛 21 | 🌐 Python | 📅 2025-02-01 - Geometric deep learning model predicting transcriptional outcomes of novel single- and multi-gene perturbations using gene–gene knowledge graphs, 40% higher precision than prior methods on combinatorial perturbation prediction (Stanford, Nature Biotechnology 2024)
* [RNA-FM (Nature Methods 2024)](https://github.com/ml4bio/RNA-FM) ⭐ 389 | 🐛 18 | 🌐 Jupyter Notebook | 📅 2025-05-27 - RNA foundation model trained on millions of RNA sequences for generalist RNA sequence understanding, enabling downstream structure prediction, function annotation, and representation learning for non-coding RNAs (ml4bio, 372+ stars)
* [LucaOne](https://github.com/LucaOne/LucaOne) ⭐ 368 | 🐛 2 | 🌐 Python | 📅 2026-05-25 - Generalized biological foundation model with unified nucleic acid and protein language, integrating DNA/RNA/protein sequences (Nature Machine Intelligence 2025)
* [gReLU (Genentech, 2024)](https://github.com/Genentech/gReLU) ⭐ 363 | 🐛 24 | 🌐 Python | 📅 2026-06-12 - Python library to train, interpret, and apply deep learning models to DNA sequences, providing a unified framework for regulatory genomics with support for CNN and transformer architectures, variant effect prediction, and attribution analysis (325+ stars)
* [scBERT](https://github.com/TencentAILabHealthcare/scBERT) ⭐ 361 | 🐛 26 | 🌐 Python | 📅 2023-12-13 - Single-cell BERT for gene expression
* [GPN-Star (Song Lab, UC Berkeley, bioRxiv 2025)](https://github.com/songlab-cal/gpn) ⭐ 353 | 🐛 7 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Phylogeny-aware genomic language model trained on whole-genome alignments across multiple evolutionary timescales, predicting functional constraints and variant effects for human, mouse, chicken, fly, worm, and Arabidopsis genomes (344+ stars, MIT License)
* [GenePT](https://github.com/yiqunchen/GenePT) ⭐ 324 | 🐛 17 | 🌐 Jupyter Notebook | 📅 2024-03-18 - Generative pre-training for genomics
* [gRNAde](https://github.com/chaitjo/geometric-rna-design) ⭐ 317 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-12-16 - Generative AI framework for inverse design of 3D RNA structure and function using geometric deep learning, learning design rules from 3D structures to capture complex tertiary interactions (pseudoknots, non-canonical base pairs) with expert-level accuracy for designing functional RNAs including aptamers and ribozymes (bioRxiv 2025)
* [GENERanno (bioRxiv 2025)](https://github.com/GenerTeam/GENERanno) ⭐ 316 | 🐛 0 | 🌐 Python | 📅 2026-06-15 - Genomic foundation model for metagenomic and genome annotation, featuring an 8k base-pair context and 500M parameters trained on 386B base pairs of eukaryotic DNA; provides expert models and a unified CLI for prokaryotic/eukaryotic coding-sequence annotation with strong performance on Genomic Benchmarks, Nucleotide Transformer tasks, and custom Gener tasks (GenerTeam, 314+ stars, MIT License)
* [Caduceus (ICML 2024)](https://github.com/kuleshov-group/caduceus) ⭐ 251 | 🐛 10 | 🌐 Python | 📅 2026-03-18 - Bi-directional DNA language model based on the Mamba state space architecture, enabling efficient long-range genomic sequence modeling with linear-time complexity and built-in reverse-complement equivariance; achieves strong performance on chromatin accessibility, enhancer, and promoter prediction benchmarks (Stanford & UC Berkeley, 500+ stars)
* [RhoFold+](https://github.com/ml4bio/RhoFold) ⭐ 245 | 🐛 9 | 🌐 Python | 📅 2025-05-29 - End-to-end RNA 3D structure prediction using RNA language model pretrained on 23.7M sequences, outperforming existing methods and human expert groups on RNA-Puzzles and CASP15 (Nature Methods 2024)
* [Helical](https://github.com/helicalAI/helical) ⭐ 230 | 🐛 7 | 🌐 Python | 📅 2026-08-22 - Unified framework for state-of-the-art pre-trained bio foundation models across genomics and transcriptomics, providing standardized interfaces and pipelines for DNA, RNA, and single-cell models including Evo 2, Geneformer, scGPT, and UCE with streamlined inference, benchmarking, and fine-tuning workflows (213+ stars, 2024-2025)
* [CellWhisperer (Nature Biotechnology 2025)](https://github.com/epigen/cellwhisperer) ⭐ 218 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-05-12 - Multimodal AI bridging transcriptomics data and natural language, enabling intuitive chat-based exploration and analysis of single-cell RNA-seq datasets through conversational interaction without coding; fine-tuned Mistral 7B LLaVA model emulating biologist-bioinformatician discussions (207+ stars, GPL-3.0)
* [Carbon (Hugging Face, 2026)](https://github.com/huggingface/carbon) ⭐ 214 | 🐛 4 | 🌐 Python | 📅 2026-06-06 - Family of causal genomic foundation models trained on 1T tokens (\~6T DNA base pairs) from the Carbon Pretraining Corpus, combining eukaryote genes, mRNA transcripts, and prokaryote genomes with a hybrid text/6-mer tokenizer; Carbon-3B matches or beats Evo2-7B on zero-shot DNA evaluations including sequence recovery, variant effect prediction, and perturbations (Apache 2.0, 201+ stars)
* [Casanovo](https://github.com/Noble-Lab/casanovo) ⭐ 197 | 🐛 28 | 🌐 Python | 📅 2026-08-26 - Transformer encoder-decoder for de novo peptide sequencing from tandem mass spectrometry, translating MS/MS spectra directly to peptide sequences without reference databases, enabling identification of novel peptides for immunopeptidomics, antibody repertoires, and metaproteomes (Noble Lab UW, Nature Communications 2024)
* [RiNALMo (Nature Communications 2025)](https://github.com/lbcb-sci/RiNALMo) ⭐ 173 | 🐛 1 | 🌐 Python | 📅 2026-05-04 - General-purpose RNA language model with 650M parameters pretrained on 36M non-coding RNA sequences, achieving strong generalization on structure prediction tasks including secondary structure prediction, splice-site prediction, mean ribosome loading, and ncRNA classification (lbcb-sci, 165+ stars, Apache-2.0)
* [Nicheformer](https://github.com/theislab/nicheformer) ⭐ 170 | 🐛 24 | 🌐 Jupyter Notebook | 📅 2025-11-23 - Foundation model jointly trained on single-cell and spatial transcriptomics data, enabling unified representation learning across cellular and tissue spatial contexts for cell type prediction, spatial domain inference, and cross-modal integration (theislab, bioRxiv 2024, 164+ stars)
* [Tahoe-x1](https://github.com/tahoebio/tahoe-x1) ⭐ 163 | 🐛 5 | 🌐 Python | 📅 2026-08-25 - Apache 2.0 single-cell foundation model family scaling to 3B parameters, pretrained on 266M cell profiles including perturbation data and released with training, embedding, and downstream benchmarking workflows for disease-relevant single-cell tasks (2025)
* [scPRINT (Nature Communications 2025)](https://github.com/cantinilab/scPRINT) ⭐ 157 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-08-11 - Large transformer-based single-cell foundation model pretrained on 50 million cells for robust gene network inference, expression denoising, cell embedding, and zero-shot label prediction, leveraging ESM2 protein embeddings and bidirectional transformer architecture (Cantini Lab, 148+ stars, GPL-3.0)
* [Stack](https://github.com/ArcInstitute/stack) ⭐ 153 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-04-28 - Arc Institute's single-cell foundation model enabling in-context learning at inference time via a novel tabular attention architecture, trained on 150M uniformly-preprocessed cells for generalizing biological effects and generating unseen cell profiles in novel contexts (2025)
* [AIDO.ModelGenerator](https://github.com/genbio-ai/ModelGenerator) ⭐ 125 | 🐛 4 | 🌐 Python | 📅 2026-08-19 - GenBio AI's software stack for the AI-Driven Digital Organism, supporting adaptation and finetuning of multiscale biological foundation models across DNA, RNA, protein, structure, and single-cell tasks with reproducible CLIs and pretrained model zoo (2025)
* [scTranslator (Nature Biomedical Engineering 2025)](https://github.com/TencentAILabHealthcare/scTranslator) ⭐ 99 | 🐛 11 | 🌐 Jupyter Notebook | 📅 2025-08-24 - Pre-trained large generative model translating single-cell transcriptomes to proteomes in an alignment-free manner, generating absent protein abundance data for CITE-seq, spatial CITE-seq, REAP-seq, and NEAT-seq across tissues and diseases; offers three model variants pretrained on 2M human cells, 160K PBMCs, or 18K bulk samples (Tencent AI Lab Healthcare, 96+ stars)
* [RNAPro (NVIDIA, 2026)](https://github.com/NVIDIA-Digital-Bio/RNAPro) ⭐ 94 | 🐛 1 | 🌐 Python | 📅 2026-06-05 - State-of-the-art RNA 3D folding model developed with Stanford Das Lab and Kaggle competition winners, featuring a 488M-parameter AF3-like architecture with MSA and template-based modeling, enabling structure-driven drug discovery and RNA therapeutics design (NVIDIA-Digital-Bio, Apache 2.0)
* [CodonFM (NVIDIA)](https://github.com/NVIDIA-Digital-Bio/CodonFM) ⭐ 90 | 🐛 0 | 🌐 Python | 📅 2025-11-01 - Family of codon-resolution language models trained on 130 million protein-coding sequences from over 20,000 species, enabling cross-species gene expression prediction and codon-level functional genomics (2025)
* [DNA Claude Analysis](https://github.com/shmlkv/dna-claude-analysis) ⭐ 56 | 🐛 0 | 🌐 Python | 📅 2026-03-04 - Interactive personal genome analysis toolkit using Claude Code and Python. Parses raw genotyping data from consumer DNA services and analyzes SNPs across 17 categories including health risks, pharmacogenomics, ancestry, and nutrition, with a terminal-style HTML dashboard.
* [NuFold (Nature Communications 2025)](https://github.com/kiharalab/NuFold) ⭐ 54 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2025-10-31 - End-to-end deep learning approach for RNA tertiary structure prediction with a flexible nucleobase center representation, achieving \~7 Å C1' RMSD across test RNAs and predicting \~545,000 structures covering 2,200+ RNA families (Kihara Lab, Purdue University, 50+ stars)
* [scDFM (ICLR 2026)](https://github.com/AI4Science-WestlakeU/scDFM) ⭐ 49 | 🐛 6 | 🌐 Python | 📅 2026-04-22 - Distributional flow matching model for robust single-cell perturbation prediction, modeling the full distribution of perturbed cellular expression profiles conditioned on control states via PAD-Transformer and multi-kernel MMD regularization; reduces MSE by 19.6% over the strongest baseline in combinatorial settings (Westlake University, 41+ stars, MIT License)
* [ChatSpatial](https://github.com/cafferychen777/ChatSpatial) ⭐ 44 | 🐛 13 | 🌐 Python | 📅 2026-08-15 - MCP server enabling spatial transcriptomics analysis via natural language, integrating 60+ methods including SpaGCN, Cell2location, LIANA+, CellRank for Visium, Xenium, MERFISH platforms
* [Geneformer](https://github.com/lcrawlab/Geneformer) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2024-12-14 - Single-cell transformer foundation model pretrained on 104M human transcriptomes via masked gene prediction, enabling transfer learning for cell type classification, gene network analysis, and in silico perturbation with limited labeled data (Nature 2023, V2 2024)

#### Neuroscience & Behavioral Analysis

* [DeepLabCut](https://github.com/DeepLabCut/DeepLabCut) ⭐ 5,747 | 🐛 46 | 🌐 Python | 📅 2026-08-28 - Markerless pose estimation of user-defined features with deep learning for all animals including humans, enabling quantitative behavioral analysis in neuroscience and ethology (Nature Neuroscience 2018, 5.6K+ stars)
* [TRIBE v2](https://github.com/facebookresearch/tribev2) ⭐ 3,176 | 🐛 46 | 🌐 Jupyter Notebook | 📅 2026-06-23 - Meta FAIR's foundation model of vision, audition, and language for in-silico neuroscience, predicting fMRI brain responses to naturalistic multimodal stimuli (video, audio, text) through unified Transformer architecture mapped to the cortical surface (2026)
* [snntorch](https://github.com/jeshraghian/snntorch) ⭐ 2,038 | 🐛 72 | 🌐 Python | 📅 2026-08-27 - Deep learning with spiking neural networks in Python, providing gradient-based training of SNNs via PyTorch autodifferentiation for brain-inspired computing and neuromorphic research, with online learning capabilities and extensive tutorials (1.9K+ stars, actively maintained)
* [nilearn](https://github.com/nilearn/nilearn) ⭐ 1,425 | 🐛 289 | 🌐 Python | 📅 2026-08-27 - Machine learning and statistical learning for neuroimaging in Python, providing easy-to-use tools for fMRI and MRI analysis including decoding, connectivity estimation, and parcellation with seamless scikit-learn integration (INRIA Parietal team, 1.4K+ stars)
* [braindecode](https://github.com/braindecode/braindecode) ⭐ 1,295 | 🐛 95 | 🌐 Python | 📅 2026-08-28 - Deep learning software to decode EEG, ECG or MEG signals, providing standardized neural network models, preprocessing pipelines, and evaluation workflows for brain-computer interfaces and cognitive neuroscience research (1.2K+ stars, BSD 3-Clause, actively maintained)
* [CEBRA (Nature 2023)](https://github.com/AdaptiveMotorControlLab/CEBRA) ⭐ 1,111 | 🐛 20 | 🌐 Python | 📅 2026-06-28 - Learnable latent embeddings for joint behavioral and neural analysis, enabling consistent and interpretable mapping of neural activity to behavior across modalities, species, and experiments (EPFL & Harvard, 1K+ stars)
* [Brain2Qwerty (Meta FAIR, Nature Neuroscience 2026)](https://github.com/facebookresearch/brain2qwerty) ⭐ 916 | 🐛 8 | 🌐 Python | 📅 2026-07-29 - Non-invasive decoding of typed sentences from MEG and EEG brain recordings using a convolutional encoder, transformer, and character-level language model; official code for the Nature Neuroscience paper and Meta blog post on brain-AI communication (Meta FAIR, 894+ stars, CC BY-NC 4.0, 2026)
* [SpikeInterface](https://github.com/SpikeInterface/spikeinterface) ⭐ 838 | 🐛 343 | 🌐 Python | 📅 2026-08-27 - Unified Python framework for extracellular electrophysiology, standardizing interfaces to 10+ ML-based spike sorting algorithms including Kilosort for reproducible neural spike sorting workflows (792+ stars, actively maintained)
* [CaImAn (Flatiron Institute)](https://github.com/flatironinstitute/CaImAn) ⭐ 734 | 🐛 101 | 🌐 Python | 📅 2026-08-02 - Computational toolbox for large scale Calcium Imaging Analysis, including movie handling, motion correction, source extraction, spike deconvolution and result visualization, using machine learning for automated neuron detection and activity inference in two-photon and one-photon calcium imaging data (723+ stars, actively maintained)
* [Kilosort (Nature Methods 2024)](https://github.com/MouseLand/Kilosort) ⭐ 624 | 🐛 15 | 🌐 Python | 📅 2026-04-27 - Fast spike sorting with drift correction for extracellular electrophysiology, enabling universal neural spike sorting via deep learning on high-density neural probe recordings (MouseLand, 609+ stars)
* [SLEAP](https://github.com/talmolab/sleap) ⭐ 610 | 🐛 25 | 🌐 Python | 📅 2026-08-27 - Deep learning-based multi-animal pose tracking and behavior classification, enabling automated quantification of social interactions and collective behavior across species (Nature Methods 2022, 2.2K+ stars)
* [NeuroAI (Meta FAIR)](https://github.com/facebookresearch/neuroai) ⭐ 293 | 🐛 69 | 🌐 Python | 📅 2026-08-21 - Modular Python suite for Neuro-AI research across all modalities, providing efficient data loaders (NeuralSet), curated datasets (NeuralFetch), scalable training (NeuralTrain), and unified benchmarking (NeuralBench) for building and evaluating neuroscience foundation models (Meta FAIR, 270+ stars, MIT License, 2026)
* [BrainIAC (Nature Neuroscience 2026)](https://github.com/AIM-KannLab/BrainIAC) ⭐ 152 | 🐛 15 | 🌐 Python | 📅 2026-02-05 - Self-supervised vision foundation model for generalized structural brain MRI analysis, pretrained on \~49,000 scans from diverse datasets and generalizing across brain age prediction, dementia/MCI classification, IDH mutation detection, glioma survival prediction, time-to-stroke estimation, MR sequence classification, and brain tumor segmentation; outperforms task-specific models especially with limited training data (Mass General Brigham & Harvard Medical School, 129+ stars)

#### Computational Pathology & Digital Pathology

* [UNI (Nature Medicine 2024)](https://github.com/mahmoodlab/UNI) ⭐ 769 | 🐛 32 | 🌐 Jupyter Notebook | 📅 2025-03-26 - General-purpose pathology foundation model pretrained on 100K+ diagnostic whole-slide images across 20 major tissue types, achieving state-of-the-art transfer learning across 30+ clinical tasks and serving as a universal feature extractor for digital pathology (Mahmood Lab, 722+ stars)
* [Prov-GigaPath (Nature 2024)](https://github.com/prov-gigapath/prov-gigapath) ⭐ 631 | 🐛 74 | 🌐 Python | 📅 2026-08-07 - Whole-slide pathology foundation model trained on 1.3 billion image tiles from 171K slides using a LongNet-based architecture to encode gigapixel-scale WSIs for cancer subtyping and biomarker prediction (Microsoft Research & Providence, 601+ stars)
* [TRIDENT (2025)](https://github.com/mahmoodlab/TRIDENT) ⭐ 624 | 🐛 41 | 🌐 Python | 📅 2026-08-28 - Toolkit for large-scale whole-slide image processing supporting 22+ patch encoders (UNI, CONCH, Virchow, H-Optimus-0, etc.), slide encoders (TITAN, GigaPath, PRISM, CHIEF, Madeleine, Feather), tissue segmentation, and multi-GPU inference with end-to-end pipeline and smart resume for standardized deployment of computational pathology foundation models (Mahmood Lab, Harvard Medical School, 553+ stars)
* [CONCH (Nature Medicine 2024)](https://github.com/mahmoodlab/CONCH) ⭐ 526 | 🐛 16 | 🌐 Python | 📅 2025-03-26 - Vision-language pathology foundation model using contrastive learning on histopathology image-text pairs, enabling zero-shot classification, slide-level retrieval, and multimodal reasoning across diverse cancer types (Mahmood Lab, 494+ stars)
* [HEST (NeurIPS 2024)](https://github.com/mahmoodlab/HEST) ⭐ 432 | 🐛 24 | 🌐 Jupyter Notebook | 📅 2026-04-16 - Dataset and benchmarking framework integrating histology and spatial transcriptomics, enabling multimodal analysis of whole-slide images with matched spatial gene expression for advancing computational pathology and tissue microenvironment research (Mahmood Lab, Harvard Medical School, 411+ stars)
* [GigaTIME (Cell 2025)](https://github.com/prov-gigatime/GigaTIME) ⭐ 406 | 🐛 7 | 🌐 Jupyter Notebook | 📅 2026-08-07 - Multimodal AI system generating virtual populations for tumor microenvironment modeling from H\&E and multiplex immunofluorescence pathology images, enabling large-scale spatial analysis of cancer biology and therapeutic response prediction (Microsoft Research & Providence, 370+ stars)
* [PLIP (Nature Medicine 2023)](https://github.com/PathologyFoundation/plip) ⭐ 382 | 🐛 6 | 🌐 Python | 📅 2023-09-20 - First vision-and-language foundation model for pathology AI, fine-tuned from CLIP on 249K image-caption pairs, enabling open-ended visual-semantic search and zero-shot diagnosis across histopathology (Pathology Foundation, 376+ stars)
* [TITAN (Nature Medicine 2024)](https://github.com/mahmoodlab/TITAN) ⭐ 369 | 🐛 3 | 🌐 Python | 📅 2025-12-13 - Multimodal whole-slide pathology foundation model jointly pretrained on H\&E histology and diagnostic text reports, enabling zero-shot cancer subtyping, biomarker prediction, and multimodal reasoning across diverse cancer types (Mahmood Lab, 341+ stars)
* [spmind (ICML 2026)](https://github.com/tomtommyyuan/spmind) ⭐ 277 | 🐛 0 | 🌐 Python | 📅 2026-07-13 - Autonomous AI agent for end-to-end spatial proteomics analysis, featuring SP-Bench for agentic multiplexed-imaging workflows (tomtommyyuan, 140+ stars, 2026)
* [Feather (Mahmood Lab, ICML 2025 Spotlight)](https://github.com/mahmoodlab/MIL-Lab) ⭐ 154 | 🐛 1 | 🌐 Python | 📅 2026-02-05 - Lightweight supervised slide foundation model with 0.9M parameters pretrained on 24K whole-slide images for pan-cancer morphological classification, achieving competitive performance with much larger self-supervised models (TITAN, GigaPath) while enabling finetuning on consumer-grade GPUs; includes standardized MIL implementations and benchmarking across 15+ classification tasks (Mahmood Lab, Harvard Medical School, 153+ stars)
* [SlideChat (CVPR 2025)](https://github.com/uni-medical/SlideChat) ⭐ 127 | 🐛 4 | 🌐 Python | 📅 2026-04-02 - First large vision-language assistant for gigapixel whole-slide pathology image understanding, released with the SlideInstruction dataset and SlideBench benchmark (uni-medical, Apache 2.0, 2025)
* [Virchow (Nature Medicine 2024)](https://huggingface.co/paige-ai/Virchow) - Self-supervised pathology foundation model (ViT-Huge, 632M parameters) pretrained via DINOv2 on 1.5M whole-slide images from Memorial Sloan Kettering across 17 cancer types, with Virchow2 follow-up scaling to 3.1M slides and mixed magnifications, achieving SOTA on biomarker prediction, mutation classification, and rare cancer detection (Paige AI & MSK)
* [H-Optimus (Bioptimus, Nature Medicine 2025)](https://huggingface.co/bioptimus/H-optimus-0) - Open-weights pathology foundation model family (H-Optimus-0: 1.1B-parameter ViT pretrained via DINOv2 on 500M+ diagnostic image tiles; H-Optimus-1 follow-up) for whole-slide image analysis, achieving strong zero-shot and fine-tuned transfer across biomarker prediction, cancer subtyping, and mutation classification (Bioptimus, Apache 2.0)
* [PathChat (Nature Medicine 2024)](https://github.com/MahmoodLab/PathChat) - Multimodal generative AI assistant for computational pathology enabling interactive visual-language conversations over histopathology images for diagnostic reasoning, case discussion, and education, built on a Mistral-7B backbone with domain-specific fine-tuning (Mahmood Lab, Harvard Medical School, 1.2K+ stars)

#### Medical AI & Clinical Applications

* [nnU-Net](https://github.com/MIC-DKFZ/nnUNet) ⭐ 8,836 | 🐛 86 | 🌐 Python | 📅 2026-07-23 - Self-configuring deep learning framework for semantic segmentation of biomedical images requiring no manual hyperparameter tuning; automatically adapts preprocessing, network topology, and training parameters to achieve state-of-the-art results across 120+ international competitions and benchmarks out-of-the-box (DKFZ, Nature Methods 2021, 8.3k+ stars)
* [MONAI](https://github.com/Project-MONAI/MONAI) ⭐ 8,637 | 🐛 529 | 🌐 Python | 📅 2026-08-26 - NVIDIA and King's College London's open-source AI toolkit for healthcare imaging, providing foundational frameworks for medical image annotation (MONAI Label), training (MONAI Core), and deployment (MONAI Deploy) across radiology, pathology, and endoscopy (8K+ stars, Apache 2.0)
* [OpenMed (2025-2026)](https://github.com/maziyarpanahi/openmed) ⭐ 5,174 | 🐛 549 | 🌐 Python | 📅 2026-08-26 - Local-first, open-source healthcare AI toolkit for clinical NLP and PHI/PII de-identification across 12 languages, running entirely on-device with 1,000+ specialized medical models; provides Python SDK, REST API, Docker deployment, and native Swift apps via OpenMedKit with Apple MLX/CoreML acceleration, supporting HIPAA-aware de-identification with 247 PII checkpoints (3K+ stars, Apache 2.0, arXiv 2508.01630)
* [MedSAM](https://github.com/bowang-lab/MedSAM) ⭐ 4,378 | 🐛 17 | 🌐 Jupyter Notebook | 📅 2025-05-07 - Universal medical image segmentation foundation model trained on 1.57M image-mask pairs across 10 imaging modalities and 30+ cancer types (Nature Communications 2024)
* [TotalSegmentator](https://github.com/wasserth/TotalSegmentator) ⭐ 2,955 | 🐛 70 | 🌐 Python | 📅 2026-08-13 - Robust deep learning-based segmentation of >100 anatomical structures in CT and MR images, built on nnU-Net and widely adopted in clinical radiology and surgical planning workflows (2.6K+ stars)
* [napari](https://github.com/napari/napari) ⭐ 2,746 | 🐛 1,239 | 🌐 Python | 📅 2026-08-25 - Fast, interactive, multi-dimensional image viewer for Python, foundational platform for scientific imaging AI with a rich plugin ecosystem integrating deep learning segmentation, object tracking, and microscopy analysis workflows (2.6K+ stars)
* [Cellpose](https://github.com/MouseLand/cellpose) ⭐ 2,331 | 🐛 67 | 🌐 Python | 📅 2026-06-14 - Generalist deep learning algorithm for cell and nucleus segmentation across diverse image types, with human-in-the-loop training (2.0) and one-click image restoration (3.0), 70K+ training objects (Nature Methods 2021/2022/2025)
* [HealthGPT (ICML 2025 Spotlight)](https://github.com/ZJU4HealthCare/HealthGPT) ⭐ 1,654 | 🐛 12 | 🌐 Python | 📅 2026-07-31 - Medical large vision-language model unifying comprehension and generation via heterogeneous knowledge adaptation, enabling holistic medical image understanding, visual question answering, and clinical report generation across diverse modalities (ZJU4HealthCare, 1.6K+ stars)
* [QuPath](https://github.com/qupath/qupath) ⭐ 1,429 | 🐛 34 | 🌐 Java | 📅 2026-08-22 - Open-source bioimage analysis platform for digital pathology and research, featuring AI-powered cell detection, tissue classification, and whole-slide image analysis with extensible scripting and plugin architecture (1.3K+ stars, actively maintained)
* [StarDist](https://github.com/stardist/stardist) ⭐ 1,257 | 🐛 70 | 🌐 Python | 📅 2026-02-14 - Deep learning-based object detection and segmentation for star-convex shapes, widely adopted for cell and nucleus segmentation in fluorescence and electron microscopy via a compact neural network architecture with non-maximum suppression and shape-based post-processing (Nature Methods 2020, 1.2K+ stars)
* [MedRAX (ICML 2025)](https://github.com/bowang-lab/MedRAX) ⭐ 1,218 | 🐛 6 | 🌐 Python | 📅 2025-10-31 - First versatile medical reasoning agent for chest X-ray interpretation, dynamically integrating state-of-the-art CXR analysis tools and multimodal LLMs into a unified framework; introduces ChestAgentBench with 2,500 complex medical queries across 7 categories (bowang-lab, 1.1K+ stars)
* [micro-sam](https://github.com/computational-cell-analytics/micro-sam) ⭐ 715 | 🐛 72 | 🌐 Jupyter Notebook | 📅 2026-08-28 - Segment Anything Model for microscopy: interactive and automatic segmentation of light, electron, and fluorescence microscopy images in 2D and 3D, with domain-specific fine-tuning workflows for scientific imaging (1.5K+ stars)
* [MedSAM2](https://github.com/bowang-lab/MedSAM2) ⭐ 706 | 🐛 14 | 🌐 Python | 📅 2025-07-11 - Segment Anything in 3D medical images and videos, extending SAM2 to volumetric and temporal medical imaging with state-of-the-art zero-shot segmentation performance across CT, MRI, and surgical video (arXiv 2025)
* [BiomedParse](https://github.com/microsoft/BiomedParse) ⭐ 695 | 🐛 41 | 🌐 Python | 📅 2026-01-22 - Foundation model for joint segmentation, detection, and recognition of biomedical objects across nine imaging modalities, with v2 introducing BoltzFormer architecture for end-to-end 3D inference (Microsoft, Nature Methods 2025)
* [ZeroCostDL4Mic](https://github.com/HenriquesLab/ZeroCostDL4Mic) ⭐ 649 | 🐛 59 | 🌐 Jupyter Notebook | 📅 2026-03-29 - Google Colab-based no-code toolbox democratizing deep learning in microscopy for biologists without programming experience, enabling AI-powered image segmentation, denoising, super-resolution, and object tracking across diverse imaging modalities (Henriques Lab, 640+ stars)
* [MedRAG](https://github.com/Teddy-XiongGZ/MedRAG) ⭐ 590 | 🐛 1 | 🌐 Python | 📅 2025-05-08 - Systematic medical RAG toolkit for question answering over PubMed, StatPearls, textbooks, and Wikipedia, supporting multiple retrievers, domain LLMs, and follow-up-query workflows for benchmarked clinical/biomedical QA (ACL Findings 2024)
* [Merlin (Stanford MIMI, Nature 2026)](https://github.com/StanfordMIMI/Merlin) ⭐ 467 | 🐛 3 | 🌐 Python | 📅 2026-05-23 - 3D vision-language model for computed tomography that leverages both structured electronic health records (EHR) and unstructured radiology reports for pretraining, enabling multimodal medical understanding and radiology report generation (447+ stars, MIT License, 2026)
* [MIRA (NeurIPS 2025)](https://github.com/microsoft/MIRA) ⭐ 418 | 🐛 3 | 🌐 Python | 📅 2026-07-02 - Medical time series foundation model pretrained on 454B time points from heterogeneous clinical corpora spanning ICU physiological signals and hospital EHR, with continuous-time rotary positional encoding, frequency-specialized Mixture-of-Experts, and neural ODE extrapolation for zero-shot forecasting across irregular and multimodal temporal health data (Microsoft, 399+ stars, MIT License)
* [MedAgents](https://github.com/gersteinlab/MedAgents) ⭐ 366 | 🐛 0 | 🌐 Python | 📅 2024-05-27 - Multi-disciplinary collaboration framework for zero-shot medical reasoning using role-playing LLM agents (ACL 2024)
* [VoxTell (MIC-DKFZ, 2025)](https://github.com/MIC-DKFZ/VoxTell) ⭐ 262 | 🐛 2 | 🌐 Python | 📅 2026-08-06 - Free-text promptable universal 3D medical image segmentation foundation model enabling zero-shot segmentation of diverse anatomical structures and pathologies via natural language prompts across CT, MRI, and other volumetric imaging modalities (DKFZ, 195+ stars, Apache 2.0)
* [InstanSeg (Nature Methods 2025)](https://github.com/instanseg/instanseg) ⭐ 236 | 🐛 14 | 🌐 Python | 📅 2026-07-30 - PyTorch-based embedding instance segmentation algorithm optimized for accurate, efficient, and portable cell and nucleus segmentation across fluorescence and brightfield microscopy images, achieving state-of-the-art speed and accuracy with lightweight model sizes suitable for edge deployment (224+ stars, Apache 2.0)
* [Medical SAM3 (AIM Research Lab, arXiv 2026)](https://github.com/AIM-Research-Lab/Medical-SAM3) ⭐ 218 | 🐛 9 | 🌐 Python | 📅 2026-06-21 - Foundation model for universal prompt-driven medical image segmentation extending SAM3 to clinical imaging, supporting 2D public benchmarks and 3D training/evaluation with text and box prompts; pretrained weights available on HuggingFace (189+ stars)
* [cellSAM](https://github.com/vanvalenlab/cellSAM) ⭐ 213 | 🐛 50 | 🌐 Python | 📅 2026-06-04 - Foundation model for universal cell segmentation achieving state-of-the-art performance across bacteria, tissue, yeast, cell culture, and diverse imaging modalities (brightfield, fluorescence, phase), with pip-installable inference and Napari plugin (vanvalenlab/Caltech, bioRxiv 2024)
* [BiaPy](https://github.com/BiaPyX/BiaPy) ⭐ 212 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Open-source deep learning toolbox for bioimage analysis providing a unified, configuration-driven framework for 2D/3D semantic segmentation, instance segmentation, classification, denoising, super-resolution, and self-supervised learning; integrates state-of-the-art architectures including U-Net, Vision Transformers, and ConvNeXt, designed for microscopy and biomedical imaging researchers without extensive coding expertise (MIT License, actively maintained)
* [NVIDIA Biomedical AI-Q Research Agent](https://github.com/NVIDIA-AI-Blueprints/biomedical-aiq-research-agent) ⭐ 143 | 🐛 1 | 🌐 Python | 📅 2026-05-15 - Deployable biomedical deep-research agent blueprint combining on-prem multimodal RAG, report generation, human-in-the-loop editing, and virtual screening with MolMIM and DiffDock for drug discovery workflows (2025)
* [MedAgentGym](https://github.com/wshi83/MedAgentGym) ⭐ 130 | 🐛 1 | 🌐 Python | 📅 2026-04-12 - Scalable agentic training environment for code-centric reasoning in biomedical data science
* [MedSegX](https://github.com/MedSegX/MedSegX-code) ⭐ 91 | 🐛 6 | 🌐 Python | 📅 2025-10-02 - Generalist foundation model and database for open-world medical image segmentation, enabling universal segmentation of diverse anatomical structures and pathologies with zero-shot generalization to unseen tasks and modalities (Nature Biomedical Engineering 2025)
* [UniBiomed (Nature Communications 2026)](https://github.com/Luffy03/UniBiomed) ⭐ 75 | 🐛 7 | 🌐 Python | 📅 2026-06-12 - Universal foundation model for grounded biomedical image interpretation, enabling comprehensive visual understanding, reasoning, and grounding across diverse biomedical imaging modalities with strong zero-shot generalization (55+ stars, Apache 2.0, 2025-2026)
* [BioImage.IO](https://github.com/bioimage-io/core-bioimage-io-python) ⭐ 40 | 🐛 66 | 🌐 Jupyter Notebook | 📅 2026-08-25 - Community-driven model zoo and deployment infrastructure for AI-powered bioimage analysis, enabling standardized sharing, validation, and cross-platform execution of deep learning models across Fiji, Ilastik, napari, and other scientific imaging tools (EPFL, EMBL, and global collaborators, actively maintained)

### ⚛ Chemistry & Materials

#### LLM for Chemistry

* [MoleCode](https://github.com/AtomFlow-AI/MoleCode) ⭐ 297 | 🐛 2 | 🌐 Python | 📅 2026-06-04 - LLM-native molecular language that represents molecules as explicit graph-based code, enabling LLMs to operate and reason on chemistry directly with 5× lower token cost and \~76-80% accuracy on novel molecules vs \~20% for SMILES; supports small molecules, polymers, and Markush structures with lossless RDKit interconversion and Claude Code/Codex agent skills (AtomFlow, arXiv:2605.16480, 281+ stars, MIT License, 2026)
* [LLM4Chemistry](https://github.com/OpenDFM/LLM4Chemistry) ⭐ 156 | 🐛 2 | 📅 2026-03-20 - Curated paper list about LLMs for chemistry covering fine-tuning, reasoning, multi-modal models, agents, and benchmarks (COLING 2025)
* [ChemMCP](https://github.com/OSU-NLP-Group/ChemMCP) ⭐ 71 | 🐛 0 | 🌐 Python | 📅 2025-06-09 - Extensible chemistry toolkit for MCP-enabled AI assistants, exposing molecule analysis, property prediction, and reaction synthesis tools through unified Python/MCP interfaces for chemistry agents and research workflows (Apache 2.0, 2025)

#### Materials Discovery

* [FAIRChem (OMat24)](https://github.com/FAIR-Chem/fairchem) ⭐ 2,231 | 🐛 34 | 🌐 Python | 📅 2026-08-28 - Meta's comprehensive ML ecosystem for materials/chemistry with 118M+ DFT calculations, EquiformerV2 models achieving top Matbench Discovery performance
* [pymatgen](https://github.com/materialsproject/pymatgen) ⭐ 1,945 | 🐛 131 | 🌐 Python | 📅 2026-08-27 - Python Materials Genomics: robust materials analysis library defining classes for structures and molecules with support for many electronic structure codes; foundational toolkit powering the Materials Project (Berkeley Lab, 1.8K+ stars)
* [MatterGen](https://github.com/microsoft/mattergen) ⭐ 1,804 | 🐛 14 | 🌐 Python | 📅 2026-08-27 - Diffusion-based generative model for inorganic materials design, steering generation by chemistry, symmetry, bulk modulus, band gap, or magnetic properties, 2× more likely to produce stable novel structures than prior methods, experimentally validated with synthesized TaCr₂O₆ (Microsoft, Nature 2025)
* [MACE](https://github.com/ACEsuit/mace) ⭐ 1,328 | 🐛 245 | 🌐 Python | 📅 2026-08-27 - Machine learning interatomic potentials
* [GNoME](https://github.com/google-deepmind/materials_discovery) ⭐ 1,230 | 🐛 33 | 🌐 Jupyter Notebook | 📅 2026-06-23 - DeepMind's graph neural network for materials exploration, discovering 2.2M new crystal structures (380K most stable) equivalent to 800 years of traditional research, with 520K+ materials dataset open-sourced (Nature 2023)
* [NequIP](https://github.com/mir-group/nequip) ⭐ 957 | 🐛 7 | 🌐 Python | 📅 2026-08-16 - E(3)-equivariant neural network interatomic potentials achieving DFT accuracy with up to 1000× less training data than invariant models, foundational architecture behind MACE and Allegro (Harvard, MIT, Nature Communications 2022)
* [SchNetPack](https://github.com/atomistic-machine-learning/schnetpack) ⭐ 936 | 🐛 16 | 🌐 Python | 📅 2026-08-25 - PyTorch toolkit for deep neural networks in atomistic simulations, implementing SchNet, DimeNet++, PaiNN, and GemNet for molecular dynamics and quantum chemistry (900+ stars)
* [Crystal Graph CNNs](https://github.com/txie-93/cgcnn) ⭐ 892 | 🐛 23 | 🌐 Python | 📅 2021-09-06 - Crystal property prediction
* [Best of Atomistic Machine Learning](https://github.com/JuDFTteam/best-of-atomistic-machine-learning) ⭐ 717 | 🐛 51 | 📅 2026-08-28 - Curated list of atomistic ML projects for materials science
* [ORB](https://github.com/orbital-materials/orb-models) ⭐ 616 | 🐛 11 | 🌐 Python | 📅 2026-08-07 - Universal machine learning interatomic potential for atomistic simulation of materials, molecules, and biomolecules across the periodic table, with open-source pretrained models and inference tools (Orbital Materials, 2024-2025)
* [MatterSim](https://github.com/microsoft/mattersim) ⭐ 588 | 🐛 7 | 🌐 Python | 📅 2026-08-20 - Deep learning atomistic model across elements, temperatures, and pressures
* [Allegro](https://github.com/mir-group/allegro) ⭐ 498 | 🐛 1 | 🌐 Python | 📅 2026-05-29 - Highly scalable equivariant deep learning interatomic potentials enabling million-atom molecular dynamics simulations with ab initio accuracy, building on E(3)-equivariant architectures for large-scale atomistic modeling (mir-group, MIT License, 480+ stars)
* [CHGNet](https://github.com/CederGroupHub/chgnet) ⭐ 401 | 🐛 5 | 🌐 Python | 📅 2026-02-19 - Universal pretrained neural network potential with charge and magnetic moment awareness, trained on 1.5M+ Materials Project inorganic structures for charge-informed molecular dynamics and phase diagram prediction (Berkeley, Nature Machine Intelligence 2023 Cover)
* [JARVIS](https://github.com/usnistgov/jarvis) ⭐ 397 | 🐛 53 | 🌐 Python | 📅 2025-08-25 - NIST's open-source platform for data-driven atomistic materials design, integrating DFT datasets (JARVIS-DFT), machine learning property prediction (JARVIS-ML), and a comprehensive leaderboard for benchmarking materials AI methods across the periodic table (384+ stars)
* [All-atom Diffusion Transformers (ADiT)](https://github.com/facebookresearch/all-atom-diffusion-transformer) ⭐ 315 | 🐛 8 | 🌐 Python | 📅 2026-04-13 - Unified latent diffusion transformer that jointly generates periodic crystals and non-periodic molecules, scaling to 500M parameters with SOTA results on QM9, MP20, and GEOM-DRUGS (Meta FAIR, ICML 2025, 310+ stars)
* [SevenNet (JCTC 2024)](https://github.com/MDIL-SNU/SevenNet) ⭐ 270 | 🐛 19 | 🌐 Python | 📅 2026-07-22 - Graph neural network interatomic potential package supporting efficient multi-GPU parallel molecular dynamics simulations, enabling large-scale atomistic modeling with machine learning potentials (MDIL-SNU, MIT License)
* [Skala 1.1 (Microsoft Research, 2026)](https://github.com/microsoft/skala) ⭐ 252 | 🐛 8 | 🌐 Python | 📅 2026-08-28 - Neural network-based exchange-correlation functional for density functional theory (DFT) that surpasses state-of-the-art hybrid functionals in accuracy for main-group thermochemistry, kinetics, and non-covalent interactions at semi-local DFT cost; includes PySCF/GPU4PySCF/ASE bindings and C++/Fortran integrations (248+ stars, MIT License)
* [MatBench](https://github.com/materialsproject/matbench) ⭐ 215 | 🐛 57 | 🌐 Python | 📅 2024-08-20 - Materials informatics benchmark
* [CatGo (UCSD)](https://github.com/Hello-QM/catgo-LRG) ⭐ 193 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-26 - AI-driven desktop workbench for computational materials science with an interactive 3D structure editor, natural-language CatBot assistant, visual DAG workflow engine, remote-cluster access, and HPC job submission for VASP, ORCA, CP2K, Quantum ESPRESSO, GPAW, DFTB+, SIESTA, and LAMMPS (172+ stars, AGPL-3.0, 2026)
* [NVIDIA ALCHEMI Toolkit](https://github.com/NVIDIA/nvalchemi-toolkit) ⭐ 150 | 🐛 22 | 🌐 Python | 📅 2026-08-24 - Developer toolkit for accelerating training and inference for AI in chemistry and material science, providing optimized GPU-accelerated workflows for molecular and materials machine learning (NVIDIA, 2026)
* [LLaMat (Nature Machine Intelligence 2026)](https://github.com/M3RG-IITD/llamat) ⭐ 66 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-07-03 - Family of large language models for materials research via continued pretraining of LLaMA-2/3 on \~30B materials science tokens, outperforming commercial LLMs on materials science tasks while identifying "adaptation rigidity" in overtrained models; includes MatNLP benchmark and CIF crystal generation capabilities (IIT Delhi M3RG, MIT License)

#### Chemical Synthesis

* [AiZynthFinder](https://github.com/MolecularAI/aizynthfinder) ⭐ 882 | 🐛 9 | 🌐 Python | 📅 2026-04-13 - AstraZeneca's industrial-grade retrosynthetic planning tool using MCTS to recursively decompose molecules into purchasable precursors, with multi-step route scoring and support for custom one-step models (v4.0, 2024)
* [Molecular Transformers](https://github.com/pschwllr/MolecularTransformer) ⭐ 429 | 🐛 3 | 🌐 Python | 📅 2022-04-18 - AI for chemical reaction prediction and synthesis planning
* [SyntheMol (Stanford, Nature Machine Intelligence 2024)](https://github.com/swansonk14/SyntheMol) ⭐ 232 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2026-04-27 - Generative AI system for antibiotic discovery that searches billions of synthesizable molecules by combining molecular building blocks through real chemical reactions, experimentally validating novel compounds active against drug-resistant bacteria

#### Lab Automation & Robotics

* [PyLabRobot](https://github.com/PyLabRobot/pylabrobot) ⭐ 516 | 🐛 98 | 🌐 Python | 📅 2026-08-28 - Interactive and hardware-agnostic SDK for laboratory automation, enabling programmatic control of liquid handlers, plate readers, and other lab instruments across multiple vendors; foundational infrastructure for self-driving laboratories and AI-driven experimental execution (447+ stars)
* [RoboChem-Flex](https://github.com/Noel-Research-Group/Robochem_Flex) ⭐ 37 | 🐛 0 | 🌐 Python | 📅 2026-03-24 - Low-cost, modular self-driving laboratory platform democratizing autonomous chemical experimentation with open control software, device CAD/PCB files, and example optimization campaigns (Noël Research Group, University of Amsterdam, Apache 2.0, 2026)

### 🌌 Physics & Astronomy

#### Machine Learning for Physics

* [Neural ODEs](https://github.com/rtqichen/torchdiffeq) ⭐ 6,477 | 🐛 95 | 🌐 Python | 📅 2025-04-04 - Differential equations with neural networks
* [Physics-Informed Neural Networks](https://github.com/maziarraissi/PINNs) ⭐ 6,114 | 🐛 51 | 🌐 Python | 📅 2026-02-11 - Physics-constrained ML
* [JAX-MD](https://github.com/jax-md/jax-md) ⭐ 1,458 | 🐛 37 | 🌐 Jupyter Notebook | 📅 2026-08-18 - Molecular dynamics in JAX
* [FermiNet](https://github.com/google-deepmind/ferminet) ⭐ 852 | 🐛 4 | 🌐 Python | 📅 2026-05-21 - DeepMind's neural network for ab-initio quantum chemistry, directly solving the many-electron Schrödinger equation via variational Monte Carlo with antisymmetric wavefunctions, extended to excited states (Phys. Rev. Research 2020, Science 2024)
* [TORAX](https://github.com/google-deepmind/torax) ⭐ 715 | 🐛 76 | 🌐 Python | 📅 2026-08-27 - Differentiable tokamak core transport simulator for fusion energy research, coupling PDE solvers with JAX auto-differentiation and neural-network surrogates for fast forward modelling, pulse-design, and trajectory optimization (Google DeepMind, Apache 2.0)
* [NetKet](https://github.com/netket/netket) ⭐ 693 | 🐛 100 | 🌐 Python | 📅 2026-08-18 - Machine learning toolkit for many-body quantum systems, implementing neural quantum states, variational Monte Carlo, and tensor network algorithms to solve ground-state and dynamical problems in condensed matter physics and quantum chemistry (EPFL & collaborators, Nature Physics 2019/2022+, 670+ stars)
* [DiffPhysDrone (Nature Machine Intelligence 2025)](https://github.com/HenryHuYu/DiffPhysDrone) ⭐ 603 | 🐛 32 | 🌐 Cuda | 📅 2025-06-25 - First real quadrotor robot trained end-to-end with differentiable physics for vision-based agile flight, bridging simulation-based learning and real-world deployment with physics-informed neural network controllers (558+ stars)
* [EquiformerV2](https://github.com/atomicarchitects/equiformer_v2) ⭐ 350 | 🐛 19 | 🌐 Python | 📅 2026-04-10 - Improved equivariant Transformer for 3D atomic graphs (ICLR2024)
* [Walrus (arXiv 2025)](https://github.com/PolymathicAI/walrus) ⭐ 306 | 🐛 8 | 🌐 Python | 📅 2026-06-23 - Cross-domain foundation model for continuum dynamics trained on 19 physical scenarios spanning 63 variables, featuring adaptive compute via stride modulation and patch jittering for long-run stability (Polymathic AI, 293+ stars, MIT License)
* [Equiformer](https://github.com/atomicarchitects/equiformer) ⭐ 289 | 🐛 11 | 🌐 Python | 📅 2025-02-11 - Equivariant graph attention Transformer (ICLR2023)
* [GeoPT (ICML 2026)](https://github.com/Physics-Scaling/GeoPT) ⭐ 253 | 🐛 3 | 🌐 Python | 📅 2026-05-20 - Unified pre-trained model for general physics simulation via lifted geometric pre-training, augmenting static geometry with synthetic dynamics to enable dynamics-aware self-supervision without physics labels; improves industrial-fidelity benchmarks spanning fluid mechanics and solid mechanics while reducing labeled data requirements by 20–60% (Physics-Scaling, 224+ stars)
* [EquiformerV3](https://github.com/atomicarchitects/equiformer_v3) ⭐ 119 | 🐛 4 | 🌐 Python | 📅 2026-04-17 - Scaling efficient, expressive, and general SE(3)-equivariant graph attention transformers for atomic systems and machine-learned interatomic potentials (MIT License, 2026)
* [AlphaQubit](https://github.com/google-deepmind/alphaqubit) - Google DeepMind and Google Quantum AI's transformer-based neural-network decoder for quantum error correction, trained on real Sycamore quantum processor data to outperform tensor-network and correlated matching decoders at code distances 3 and 5, demonstrating ML's role in enabling fault-tolerant quantum computing (Nature 2024)

#### Astronomy & Astrophysics

* [AstroPy](https://github.com/astropy/astropy) ⭐ 5,289 | 🐛 1,424 | 🌐 Python | 📅 2026-08-28 - Python astronomy tools
* [AstroCLIP](https://github.com/PolymathicAI/AstroCLIP) ⭐ 181 | 🐛 6 | 🌐 Python | 📅 2025-12-17 - Cross-modal self-supervised foundation model for galaxies by Polymathic AI, jointly embedding multi-band galaxy imaging and optical spectra into a shared latent space to enable zero/few-shot redshift estimation, galaxy property prediction, morphology classification, and cross-modal similarity search (MNRAS Letters 2024)
* [DeepSphere](https://github.com/deepsphere/deepsphere-pytorch) ⭐ 170 | 🐛 7 | 🌐 Python | 📅 2022-04-04 - Spherical CNNs for astronomy
* [AION (arXiv 2025)](https://github.com/PolymathicAI/AION) ⭐ 147 | 🐛 6 | 🌐 Jupyter Notebook | 📅 2026-07-03 - Polymathic AI's large omnimodal foundation model for astronomical surveys, seamlessly integrating 39 distinct data modalities including imaging, spectra, photometry, and catalog entries for similarity search, property prediction, and generative modeling across legacy surveys (MIT)
* [Gaia Archive](https://gea.esac.esa.int/archive/) - Stellar data for ML

### 🌍 Earth & Climate Science

#### Climate Modeling

* [GenCast](https://github.com/google-deepmind/graphcast) ⭐ 7,603 | 🐛 77 | 🌐 Python | 📅 2026-08-11 - Google DeepMind's diffusion-based ensemble weather forecasting model at 0.25° resolution, outperforming ECMWF ENS on 97.2% of targets up to 15 days ahead, with open-source code and weights (Nature 2024)
* [segment-geospatial](https://github.com/opengeos/segment-geospatial) ⭐ 4,124 | 🐛 6 | 🌐 Python | 📅 2026-08-24 - Python package for segmenting geospatial data with the Segment Anything Model (SAM), enabling zero-shot object segmentation in satellite and aerial imagery for remote sensing and Earth observation (MIT, 4k+ stars)
* [GeoAI](https://github.com/opengeos/geoai) ⭐ 3,332 | 🐛 8 | 🌐 Python | 📅 2026-08-24 - High-level open-source geospatial AI package for satellite/aerial imagery analysis, model training, inference, interactive visualization, and QGIS integration, bridging PyTorch/Transformers with remote sensing workflows (MIT, 2026)
* [Pangu-Weather](https://github.com/198808xc/Pangu-Weather) ⭐ 1,388 | 🐛 54 | 🌐 Python | 📅 2024-01-12 - Huawei's 3D high-resolution global weather forecast model at 0.25° resolution, first AI method to comprehensively outperform traditional NWP across all variables and lead times, integrated into ECMWF operational forecasts (Nature 2023)
* [NVIDIA Earth-2](https://github.com/NVIDIA/earth2studio) ⭐ 1,101 | 🐛 28 | 🌐 Python | 📅 2026-08-28 - World's first fully open, accelerated weather AI software stack with Medium Range forecasting and Nowcasting models using generative AI (January 2026)
* [Aurora](https://github.com/microsoft/aurora) ⭐ 1,014 | 🐛 69 | 🌐 Python | 📅 2026-08-19 - Microsoft's foundation model for the Earth system supporting weather, air pollution, and ocean wave forecasting at multiple resolutions, trained on 1M+ hours of diverse atmospheric data (Nature 2025)
* [NeuralGCM](https://github.com/neuralgcm/neuralgcm) ⭐ 1,008 | 🐛 67 | 🌐 Python | 📅 2026-07-14 - Google Research's hybrid ML/physics atmospheric model combining learned dynamics with physical constraints, outperforming traditional models on 2-15 day forecasts and 40-year climate simulation, developed with ECMWF (Nature 2024)
* [TerraTorch](https://github.com/IBM/terratorch) ⭐ 852 | 🐛 49 | 🌐 Python | 📅 2026-08-28 - Python toolkit for fine-tuning geospatial foundation models
* [WeatherBench](https://github.com/pangeo-data/WeatherBench) ⭐ 835 | 🐛 18 | 🌐 Jupyter Notebook | 📅 2023-12-08 - Weather prediction benchmark
* [ClimaX](https://github.com/microsoft/ClimaX) ⭐ 708 | 🐛 12 | 🌐 Python | 📅 2023-09-30 - First foundation model for weather and climate by Microsoft, Vision Transformer-based architecture trained on heterogeneous datasets (ICML 2023)
* [WeatherBench2](https://github.com/google-research/weatherbench2) ⭐ 632 | 🐛 85 | 🌐 Python | 📅 2026-08-01 - Next-generation benchmark for data-driven global weather models with standardized evaluation framework and curated datasets for ML forecasting (Google Research, 2024)
* [ai-models (ECMWF)](https://github.com/ecmwf-lab/ai-models) ⭐ 585 | 🐛 7 | 🌐 Python | 📅 2026-08-06 - ECMWF's unified framework and command-line tool to run AI-based weather forecasting models (GraphCast, Aurora, Pangu, NeuralGCM, FourCastNet) with operational ECMWF data infrastructure, enabling standardized inference and benchmarking across state-of-the-art meteorological AI systems (ECMWF, 576+ stars)
* [Awesome Large Weather Models](https://github.com/jaychempan/Awesome-LWMs) ⭐ 374 | 🐛 1 | 📅 2025-06-23 - Curated list of large weather models for AI Earth science
* [Earth-Agent](https://github.com/opendatalab/Earth-Agent) ⭐ 194 | 🐛 11 | 🌐 Python | 📅 2026-04-02 - LLM agent framework for Earth Observation with 104 specialized tools across 5 functional kits
* [Earth-Copilot](https://github.com/microsoft/Earth-Copilot) ⭐ 187 | 🐛 7 | 🌐 Python | 📅 2026-08-11 - Microsoft's AI-powered geospatial Earth science application for natural-language exploration, visualization, and analysis of 130+ satellite collections, with STAC integration, multi-agent backend, MCP server, and deployable React/FastAPI stack (MIT, 2025)
* [FuXi (Nature 2023)](https://github.com/tpys/FuXi) ⭐ 186 | 🐛 7 | 🌐 Python | 📅 2026-06-18 - Fudan University's cascade machine learning forecasting system for 15-day global weather prediction, employing a 3D Earth-specific transformer with hard-constraint techniques to achieve state-of-the-art accuracy against traditional NWP and AI baselines
* [FengWu](https://github.com/OpenEarthLab/FengWu) ⭐ 178 | 🐛 5 | 🌐 Python | 📅 2025-12-18 - Shanghai AI Lab's deep learning-based global weather forecasting model pushing skillful forecasts beyond 10 days lead, with open-source inference code and pretrained ONNX model weights (arXiv 2023)
* [WeatherGFT](https://github.com/black-yt/WeatherGFT) ⭐ 172 | 🐛 0 | 🌐 Python | 📅 2025-02-04 - Physics-AI hybrid modeling for fine-grained weather forecasting (NeurIPS'24)
* [ClimateBench](https://github.com/duncanwp/ClimateBench) ⭐ 115 | 🐛 4 | 🌐 Jupyter Notebook | 📅 2024-04-23 - Climate data benchmark for ML models
* [Prithvi WxC](https://huggingface.co/ibm/prithvi-wxc) - IBM-NASA open-source 2.3B parameter weather and climate foundation model trained on 160 MERRA-2 variables, runs on desktop with fine-tuned variants for climate downscaling and gravity wave parameterization
* [AI for Earth](https://planetarycomputer.microsoft.com/) - Microsoft's environmental AI

#### Geophysics & Seismology

* [SeisBench](https://github.com/seisbench/seisbench) ⭐ 414 | 🐛 22 | 🌐 Jupyter Notebook | 📅 2026-08-19 - A toolbox for machine learning in seismology, providing unified interfaces for deep learning seismic phase picking, earthquake detection, and waveform analysis across multiple benchmark datasets and pretrained models (397+ stars, actively maintained)

#### Remote Sensing & Geospatial AI

* [TorchGeo](https://github.com/microsoft/torchgeo) ⭐ 4,162 | 🐛 206 | 🌐 Python | 📅 2026-08-28 - PyTorch domain library for geospatial deep learning providing standardized datasets, samplers, transforms, and pre-trained models for remote sensing, land cover mapping, and environmental monitoring (Microsoft, 4K+ stars)
* [Awesome Remote Sensing Foundation Models](https://github.com/Jack-bo1220/Awesome-Remote-Sensing-Foundation-Models) ⭐ 1,927 | 🐛 18 | 📅 2026-05-07 - Curated collection of papers, datasets, benchmarks, code, and pre-trained weights for Remote Sensing Foundation Models (RSFMs), tracking the rapidly evolving landscape of vision, vision-language, generative, and agent-based geospatial AI (1.9K+ stars, 2024-2026)
* [TESSERA (CVPR 2026)](https://github.com/ucam-eo/tessera) ⭐ 718 | 🐛 4 | 🌐 Python | 📅 2026-08-17 - University of Cambridge's foundation model for time-series satellite imagery, enabling efficient extraction of temporal patterns from Earth observation for land classification, canopy height prediction, and other remote sensing tasks
* [Clay Foundation Model](https://github.com/Clay-foundation/model) ⭐ 610 | 🐛 40 | 🌐 Python | 📅 2026-05-11 - Open-source self-supervised vision foundation model for Earth observation by Clay Foundation (non-profit), a Masked Autoencoder ViT pretrained on multimodal satellite imagery (Sentinel-1/2, Landsat 8-9, NAIP, MODIS, LINZ DEM) with location/time embeddings, supporting classification, segmentation, change detection, similarity search, and few-shot downstream geospatial tasks (Apache 2.0, v1.5 2024-2025)
* [GeoAgent (opengeos, 2026)](https://github.com/opengeos/GeoAgent) ⭐ 472 | 🐛 2 | 🌐 Python | 📅 2026-08-23 - Shared multimodal AI agent layer for geospatial Python packages (leafmap, geoai, geemap, STAC, NASA Earthdata) and QGIS, exposing geospatial tools to LLMs with structured metadata, confirmation hooks, and support for OpenAI, Anthropic, Google Gemini, Ollama, and more; includes the OpenGeoAgent QGIS plugin (456+ stars, MIT License)
* [TerraMind (IBM & ESA, 2025)](https://github.com/IBM/terramind) ⭐ 312 | 🐛 17 | 🌐 Jupyter Notebook | 📅 2026-08-24 - First any-to-any generative foundation model for Earth Observation, enabling unified multimodal understanding and generation across diverse satellite sensors and geospatial tasks through a single architecture (258+ stars)
* [Prithvi-EO-2.0 (IBM & NASA, 2024)](https://github.com/NASA-IMPACT/Prithvi-EO-2.0) ⭐ 295 | 🐛 10 | 📅 2025-02-13 - Versatile multi-temporal geospatial foundation model for Earth observation, built on a ViT-based masked autoencoder with 3D spatiotemporal patch embeddings and geolocation/temporal metadata encoding; pretrained on 4.2M global time-series samples from NASA's Harmonized Landsat and Sentinel-2 archive at 30m resolution, with 300M/600M parameter variants and fine-tuning configs for flood detection, wildfire scar, landslide detection, crop segmentation, land cover, and biomass estimation (258+ stars, MIT License)
* [Satlas](https://github.com/allenai/satlas) ⭐ 283 | 🐛 4 | 🌐 Python | 📅 2026-03-27 - Allen Institute for AI's global geospatial foundation model for satellite imagery analysis, enabling large-scale mapping of buildings, wind turbines, trees, and land cover from Sentinel-2 data with open-source weights and inference tools (2024)
* [SkySensePlusPlus](https://github.com/kang-wu/SkySensePlusPlus) ⭐ 240 | 🐛 9 | 🌐 Python | 📅 2025-09-18 - Semantic-enhanced multi-modal remote sensing foundation model for Earth observation (Nature Machine Intelligence 2025), enabling universal interpretation across diverse satellite imagery modalities with open-source weights and benchmarks

### 🌾 Agriculture & Ecology

#### Agricultural AI

* [FarmVibes.AI](https://github.com/microsoft/farmvibes-ai) ⭐ 895 | 🐛 43 | 🌐 Jupyter Notebook | 📅 2026-08-27 - Multi-modal geospatial ML platform for agriculture and sustainability, fusing satellite imagery (RGB, SAR, multispectral), drone imagery, weather data, and sensor data for crop identification, carbon footprint estimation, and microclimate prediction (Microsoft Research, MIT License)
* [PlantCV](https://github.com/danforthcenter/plantcv) ⭐ 818 | 🐛 134 | 🌐 Python | 📅 2026-08-25 - Open-source image analysis toolkit for high-throughput plant phenotyping, extracting morphological, color, and texture traits from RGB, hyperspectral, and thermal imagery with modular Python workflows for crop improvement, stress detection, and plant biology research (Donald Danforth Plant Science Center, 795+ stars, MPL-2.0)
* [AgML](https://github.com/Project-AgML/AgML) ⭐ 332 | 🐛 14 | 🌐 Python | 📅 2026-08-13 - Agricultural machine learning platform
* [Virdis](https://github.com/Thanas-R/Virdis) ⭐ 146 | 🐛 9 | 🌐 TypeScript | 📅 2026-08-23 - Satellite-powered agricultural and land analytics platform combining Sentinel-2 imagery, Google Earth Engine processing, real-time weather data, soil science databases, and AI-driven crop planning into a unified web dashboard (145+ stars, AGPL-3.0, 2026)
* [Agribound](https://github.com/montimaj/agribound) ⭐ 84 | 🐛 0 | 🌐 Python | 📅 2026-07-13 - AI-powered field boundary delineation toolkit combining satellite foundation models, embeddings, and global training data for accurate agricultural parcel/field boundary mapping, with Google Earth Engine integration and PyPI distribution (84+ stars, Apache 2.0, 2026)
* [PlantNet](https://plantnet.org/) - Plant identification using AI and citizen science

#### Ecological Modeling

* [BirdNET-Analyzer](https://github.com/birdnet-team/BirdNET-Analyzer) ⭐ 1,683 | 🐛 80 | 🌐 Python | 📅 2026-08-27 - Deep learning-based bioacoustic monitoring framework for automated bird species identification from audio recordings, supporting 6,000+ species globally with real-time analysis, batch processing, and API deployment; foundational tool in biodiversity research, conservation biology, and ecological acoustic monitoring (Cornell Lab of Ornithology, 1.5K+ stars, MIT License)
* [Microsoft Biodiversity](https://github.com/microsoft/Biodiversity) ⭐ 1,067 | 🐛 33 | 🌐 Python | 📅 2026-08-25 - Microsoft AI for Good Lab's open-source biodiversity research hub providing AI models, edge devices, and tools for wildlife monitoring and conservation, including MegaDetector (camera trap animal detection), SPARROW (species recognition), PytorchWildlife (conservation AI toolkit), and bioacoustics analysis pipelines (1K+ stars)
* [BioCLIP (CVPR 2024)](https://github.com/Imageomics/bioclip) ⭐ 273 | 🐛 5 | 🌐 Python | 📅 2026-08-07 - Vision foundation model for the tree of life, pretrained on diverse biological imagery across taxa for zero-shot species identification, trait extraction, and biodiversity research (Ohio State University Imageomics Institute)
* [BioCLIP 2 (NeurIPS 2025 Spotlight)](https://github.com/Imageomics/bioclip-2) ⭐ 87 | 🐛 3 | 🌐 Python | 📅 2026-07-27 - Biological vision foundation model trained on TreeOfLife-200M, yielding extraordinary accuracy on diverse biological visual tasks including habitat classification and trait prediction despite a narrow training objective (Ohio State University Imageomics Institute)
* [BioSimulators](https://github.com/biosimulators/Biosimulators) ⭐ 16 | 🐛 23 | 🌐 Python | 📅 2026-08-27 - Biological simulation tools
* [EcoNet](https://github.com/microsoft/EcoNet) - Ecological modeling and conservation AI

### 🧠 Social Sciences

#### Social Science Research & Simulation

* [Auto-Empirical-Research-Skills](https://github.com/brycewang-stanford/Auto-Empirical-Research-Skills) ⭐ 3,584 | 🐛 2 | 🌐 Stata | 📅 2026-08-27 - Curated collection of 23,000+ agent skills for empirical research across 8 social science disciplines, enabling reproducible social science research with AI agents (Stanford REAP & CoPaper.AI, 3K+ stars, 2026)
* [AgentSociety](https://github.com/tsinghua-fib-lab/AgentSociety) ⭐ 1,239 | 🐛 44 | 🌐 Python | 📅 2026-08-18 - Modern LLM-native agent simulation platform for social science research and experimental design, providing a flexible framework for creating and managing intelligent agents in simulated environments (Tsinghua FIB Lab, 984+ stars, 2025)
* [EDSL](https://github.com/expectedparrot/edsl) ⭐ 491 | 🐛 45 | 🌐 Python | 📅 2026-08-26 - Design, conduct and analyze results of AI-powered surveys and experiments. Simulate social science and market research with large numbers of AI agents and LLMs (460+ stars, 2024)
* [GABRIEL (OpenAI, 2026)](https://github.com/openai/GABRIEL) ⭐ 425 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2026-07-15 - Generalized Attribute Based Ratings Information Extraction Library; official OpenAI toolkit that turns messy qualitative corpora into analysis-ready datasets for social scientists and data scientists, measuring quantitative attributes in text, images, or audio using the GPT API. See the [official blog post](https://openai.com/index/scaling-social-science-research/) and [NBER working paper](http://www.nber.org/papers/w34834) (413+ stars, Apache 2.0)

***

## 🏗 Engineering & Built Environment

### Mechanical, Aerospace & Industrial Engineering

* [Noether (Emmi AI)](https://github.com/Emmi-AI/noether) ⭐ 236 | 🐛 3 | 🌐 Python | 📅 2026-07-01 - Open software framework for Engineering AI built on transformer building blocks, enabling teams to build, train, and operate industrial simulation models across engineering verticals; includes ready-to-use recipes for CFD (AB-UPT on DrivAerML), external aerodynamics, and heat transfer (234+ stars, ENPL non-commercial license, 2026)

### Structural & Civil Engineering

* [StructureClaw](https://github.com/structureclaw/structureclaw) ⭐ 178 | 🐛 4 | 🌐 Python | 📅 2026-08-12 - AI-assisted structural engineering workspace for AEC workflows: natural language to structural model, analysis, code-check, and report (171+ stars, MIT License, 2026)

### Construction & Built Environment Management

* [OpenConstructionERP](https://github.com/datadrivenconstruction/OpenConstructionERP) ⭐ 720 | 🐛 18 | 🌐 TypeScript | 📅 2026-08-28 - Open-source construction ERP with AI-powered cost matching, BOQ generation, and PDF/CAD/BIM takeoff; 42 regional catalogues, 21 languages, 71 modules (DataDrivenConstruction, 717+ stars, AGPL-3.0, 2026)

### Architectural Design & BIM

* [Aedifex](https://github.com/TangSY/aedifex) ⭐ 69 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-25 - Open-source 3D architectural editor with an AI design assistant; build floor plans with walls, doors, windows, and furniture using natural language, with real-time WebGPU-powered previews (TangSY, 59+ stars, MIT License, 2026)

### Electrical & Electronics Engineering

* [kicad-happy](https://github.com/aklofas/kicad-happy) ⭐ 1,034 | 🐛 4 | 🌐 Python | 📅 2026-08-20 - AI coding agent skills for KiCad electronics design that turn Claude Code, Codex, Gemini CLI, and other coding agents into full electronics design assistants; parses schematics and PCB layouts, builds power trees, audits connectors/ESD protection, validates passive networks, runs SPICE simulation, sources components from major distributors, and prepares boards for fabrication (aklofas, 974+ stars, MIT License, 2026)

***

## 🤖 Foundation Models for Science

### General Science Models

* [TimesFM (Google Research)](https://github.com/google-research/timesfm) ⭐ 28,285 | 🐛 225 | 🌐 Python | 📅 2026-08-28 - Pretrained time series foundation model for long-horizon forecasting across diverse scientific domains including climate variables, biomedical signals, and physical observations; decoder-only Transformer architecture with strong zero-shot generalization (19.8K+ stars, Apache 2.0, 2024-2025)
* [TabPFN (Prior Labs, Nature 2025)](https://github.com/PriorLabs/tabpfn) ⭐ 7,858 | 🐛 28 | 🌐 Python | 📅 2026-08-28 - Foundation model for tabular data that predicts on unseen real-world tables in a single forward pass, achieving accurate small-data classification and regression without task-specific training; widely applicable to scientific datasets with limited samples (7.4K+ stars, 2022-2026)
* [Chronos (Amazon Science, NeurIPS 2024)](https://github.com/amazon-science/chronos-forecasting) ⭐ 5,770 | 🐛 36 | 🌐 Python | 📅 2026-08-14 - Pretrained time series foundation model for zero-shot forecasting across diverse scientific and real-world domains; tokenizes continuous time series into discrete bins to train transformer language models on large-scale corpora, achieving strong zero-shot generalization and competitive performance with task-specific supervised models on climate, energy, and health benchmarks (5.3K+ stars, Apache 2.0, 2024-2026)
* [Galactica](https://github.com/paperswithcode/galai) ⭐ 2,741 | 🐛 30 | 🌐 Jupyter Notebook | 📅 2023-03-05 - Large language model for science
* [TabFM (Google Research, 2026)](https://github.com/google-research/tabfm) ⭐ 2,558 | 🐛 41 | 🌐 Python | 📅 2026-08-18 - Scikit-learn compatible tabular foundation model for zero-shot classification and regression on mixed-type tabular datasets via in-context learning; applicable to diverse scientific datasets (1.8K+ stars, Apache 2.0)
* [Llemma](https://github.com/EleutherAI/math-lm) ⭐ 1,097 | 🐛 15 | 🌐 Python | 📅 2024-03-12 - Open language model for mathematics (7B/34B) trained on Proof-Pile-2, outperforming Minerva at equal scale on MATH benchmark, with tool use and formal theorem proving in Lean without finetuning (EleutherAI, ICLR 2024)
* [Intern-S1](https://github.com/InternLM/Intern-S1) ⭐ 852 | 🐛 21 | 📅 2026-07-17 - Open-source scientific multimodal foundation model built on a 235B MoE LLM and 6B vision encoder, continually pretrained on 5T tokens including 2.5T scientific-domain tokens, with strong results across chemistry, materials, life science, and earth science benchmarks (2025)
* [AI Can Learn Scientific Taste (OpenMOSS, arXiv 2026)](https://github.com/tongjingqi/AI-Can-Learn-Scientific-Taste) ⭐ 431 | 🐛 0 | 📅 2026-07-22 - Scientific taste learning framework showing AI can judge and propose research ideas with long-term impact; trains Scientific Judge as a generative reward model and Scientific Thinker as an ideation policy using Reinforcement Learning from Community Feedback (RLCF) on large-scale citation signals, with SciJudgeBench and released HuggingFace model weights (425+ stars, Apache 2.0, 2026)
* [DeepInnovator (HKUDS, arXiv 2026)](https://github.com/HKUDS/DeepInnovator) ⭐ 286 | 🐛 0 | 🌐 Python | 📅 2026-03-06 - Scientific foundation model and AI research copilot for idea generation, cross-disciplinary connection discovery, and hypothesis formation; trained with a decoupled reward-comment RL architecture and achieves GPT-4o-competitive novelty/rationale on STEM and social-science idea-generation benchmarks (270+ stars, MIT License, 2026)
* [LOGOS (arXiv 2026)](https://github.com/LOGOS-Hub/LOGOS) ⭐ 143 | 🐛 1 | 🌐 Python | 📅 2026-06-25 - First multi-domain generative foundation model for the natural sciences built on a unified scientific grammar, encoding proteins, antibodies, small molecules, chemical reactions, materials, and their spatial interactions into a shared token vocabulary; enables unified generation, prediction, and design across domains under a purely autoregressive paradigm (134+ stars, Apache 2.0, 2026)
* [MinervaAI](https://github.com/google-research/minerva) - Mathematical reasoning
* [PaLM-2](https://ai.google/discover/palm2) - Scientific reasoning capabilities

### Domain-Specific Models

* [BioGPT](https://github.com/microsoft/BioGPT) ⭐ 4,488 | 🐛 75 | 🌐 Python | 📅 2024-07-25 - Biomedical text generation
* [ESM](https://github.com/facebookresearch/esm) ⚠️ Archived - Protein language models
* [HuatuoGPT-o1 (2025)](https://github.com/FreedomIntelligence/HuatuoGPT-o1) ⭐ 1,352 | 🐛 27 | 🌐 Python | 📅 2025-01-20 - Open-source medical large language model for complex clinical reasoning, extending the o1 long-chain-of-thought paradigm to biomedical question answering and diagnostic inference (FreedomIntelligence, 1.3K+ stars)
* [BioNeMo Framework](https://github.com/NVIDIA/bionemo-framework) ⭐ 847 | 🐛 232 | 🌐 Python | 📅 2026-08-28 - NVIDIA's open-source platform for building and adapting biological AI models at scale, bundling ESM-2, Geneformer, MolMIM and DNA embedding models with recipes for single-GPU to multi-node training (2025)
* [IBM FM4M](https://github.com/IBM/materials) ⭐ 315 | 🐛 18 | 🌐 Python | 📅 2026-05-13 - IBM's open foundation model family for materials and chemistry, covering SMILES, SELFIES, molecular graphs, 3D atom positions, and electron density grids, with a unified toolkit for representation learning and downstream prediction/generation (Apache 2.0, 2024-2025)
* [AntAngelMed (2026)](https://github.com/MedAIBase/AntAngelMed) ⭐ 218 | 🐛 5 | 📅 2026-06-22 - 103B-parameter open-source medical language model with 1/32 Mixture-of-Experts architecture, achieving HealthBench-leading performance among open-source models with only 6.1B active parameters; jointly developed by Ant Group and Zhejiang Province Health Information Center (MIT License)
* [ChemGPT](https://huggingface.co/ncfrey/ChemGPT-1.2B) - Chemistry-focused language model

***

## 📈 Datasets & Benchmarks

### Multidisciplinary

* [Hugging Face Datasets](https://huggingface.co/datasets) - Comprehensive ML research datasets and scientific data collections
* [Google Dataset Search](https://datasetsearch.research.google.com/) - Find scientific datasets

### Biology & Medicine

* [TDC](https://github.com/mims-harvard/TDC) ⭐ 1,277 | 🐛 66 | 🌐 Jupyter Notebook | 📅 2025-07-13 - Therapeutics Data Commons: 66 AI-ready datasets across 22 drug discovery tasks with 29 leaderboards, covering target identification, molecular generation, ADMET prediction, and clinical trial outcomes (Harvard MIMS, NeurIPS 2021/2024)
* [Arc Virtual Cell Atlas](https://github.com/ArcInstitute/arc-virtual-cell-atlas) ⭐ 582 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2026-07-01 - Curated open dataset collection of 602M+ observational and perturbational single-cell profiles for accelerating virtual cell model creation, integrating Tahoe-100M and scBaseCount data with Google Cloud Marketplace distribution (Arc Institute, 2025-2026)
* [ProteinGym](https://github.com/OATML-Markslab/ProteinGym) ⭐ 467 | 🐛 32 | 🌐 HTML | 📅 2026-03-25 - Large-scale benchmark suite for protein fitness prediction and design, aggregating 200+ deep mutational scanning assays and clinical variant datasets across diverse protein families and taxa, with standardized zero-shot and supervised leaderboards for variant effect prediction, mutation effect prediction, and protein language model evaluation (OATML & Marks Lab, NeurIPS 2023 Spotlight, Datasets & Benchmarks)
* [Chinese Medical Dataset](https://github.com/Mengqi97/chinese-medical-dataset) ⭐ 301 | 🐛 0 | 📅 2026-08-20 - Comprehensive collection of Chinese medical datasets for AI research
* [ProteinWorkshop](https://github.com/a-r-j/ProteinWorkshop) ⭐ 278 | 🐛 8 | 🌐 Python | 📅 2025-04-27 - Unified benchmarking framework for protein representation learning, providing standardized interfaces for pre-training and diverse downstream tasks including structure prediction, fitness prediction, and property prediction across multiple protein datasets and model architectures (ICLR 2024, 273+ stars, MIT License)
* [Protein Data Bank](https://www.rcsb.org/) - Protein structures
* [ChEMBL](https://www.ebi.ac.uk/chembl/) - Chemical bioactivity data
* [Human Protein Atlas](https://www.proteinatlas.org/) - Protein expression data

### Chemistry & Materials

* [Materials Project](https://next-gen.materialsproject.org/) - Computational materials database
* [QM9](https://quantum-machine.org/datasets/) - Small molecule properties
* [Open Catalyst Project](https://opencatalystproject.org/) - Catalyst discovery

### Physics

* [The Well](https://github.com/PolymathicAI/the_well) ⭐ 4,392 | 🐛 22 | 🌐 Jupyter Notebook | 📅 2026-07-23 - 15TB collection of 16 large-scale numerical simulation datasets spanning fluid dynamics, MHD, astrophysics, biological systems, and acoustic scattering, with unified PyTorch dataloaders and benchmarks for training foundation models on physical sciences (Polymathic AI, NeurIPS 2024)
* [RealPDEBench (ICLR 2026 Oral)](https://github.com/AI4Science-WestlakeU/RealPDEBench) ⭐ 118 | 🐛 0 | 🌐 Python | 📅 2026-07-16 - First scientific ML benchmark with paired real-world measurements and matched numerical simulations for complex physical systems, featuring 5 scenarios, 700+ trajectories, 10 baseline models, and 9 evaluation metrics with HuggingFace datasets and model checkpoints (Westlake University, CC BY-NC 4.0)
* [LIGO Open Science Center](https://gwosc.org/) - Gravitational wave data
* [Particle Data Group](https://pdg.lbl.gov/) - Particle physics data
* [OpenQuantumMaterials](https://www.quantum-materials.org/) - Quantum materials data

***

## 💻 Computing Frameworks

### Machine Learning

* [JAX](https://github.com/jax-ml/jax) ⭐ 36,219 | 🐛 2,488 | 🌐 Python | 📅 2026-08-28 - High-performance ML research
* [PyTorch](https://pytorch.org/) - Deep learning framework
* [TensorFlow](https://tensorflow.org/) - End-to-end ML platform

### Scientific Computing

* [NumPy](https://numpy.org/) - Numerical computing
* [SciPy](https://scipy.org/) - Scientific computing
* [Scikit-learn](https://scikit-learn.org/) - Machine learning library

### Scientific Machine Learning Frameworks

* [Flux.jl](https://github.com/FluxML/Flux.jl) ⭐ 4,740 | 🐛 45 | 🌐 Julia | 📅 2026-08-16 - Machine learning in Julia
* [DifferentialEquations.jl](https://github.com/SciML/DifferentialEquations.jl) ⭐ 3,151 | 🐛 127 | 🌐 Julia | 📅 2026-08-27 - Multi-language suite for high-performance differential equation solving and scientific machine learning (3.0k+ stars)
* [ModelingToolkit.jl](https://github.com/SciML/ModelingToolkit.jl) ⭐ 1,663 | 🐛 644 | 🌐 Julia | 📅 2026-08-28 - Acausal modeling framework for automatically parallelized scientific machine learning (1.5k+ stars)
* [NeuralPDE.jl](https://github.com/SciML/NeuralPDE.jl) ⭐ 1,220 | 🐛 144 | 🌐 Julia | 📅 2026-08-27 - Physics-informed neural networks (PINNs) for solving partial differential equations (1.1k+ stars)
* [DiffEqFlux.jl](https://github.com/SciML/DiffEqFlux.jl) ⭐ 924 | 🐛 56 | 🌐 Julia | 📅 2026-08-28 - Neural ordinary differential equations with O(1) backprop and GPU support (900+ stars)
* [Optimization.jl](https://github.com/SciML/Optimization.jl) ⭐ 835 | 🐛 129 | 🌐 Julia | 📅 2026-08-28 - Unified interface for local, global, gradient-based and derivative-free optimization (800+ stars)
* [PaddleScience](https://github.com/PaddlePaddle/PaddleScience) ⭐ 450 | 🐛 8 | 🌐 Python | 📅 2026-07-22 - SDK & library for AI-driven scientific computing applications
* [SciMLBenchmarks.jl](https://github.com/SciML/SciMLBenchmarks.jl) ⭐ 345 | 🐛 39 | 🌐 MATLAB | 📅 2026-08-28 - Scientific machine learning benchmarks & differential equation solvers
* [Tesseract Core (Pasteur Labs, SciPy 2025 / JOSS)](https://github.com/pasteurlabs/tesseract-core) ⭐ 127 | 🐛 32 | 🌐 Python | 📅 2026-08-28 - Universal components for differentiable scientific computing, packaging heterogeneous scientific tools into self-contained, portable, gradient-propagating components with auto-generated schemas, CLI/REST API/Python SDK interfaces, and reproducible deployment across local, cloud, and HPC environments (105+ stars, Apache 2.0)
* [SciML](https://sciml.ai/) - Scientific machine learning ecosystem

### Specialized Frameworks

* [PyTorch Geometric](https://github.com/pyg-team/pytorch_geometric) ⭐ 24,043 | 🐛 1,314 | 🌐 Python | 📅 2026-08-24 - Graph neural network library for PyTorch enabling molecular modeling, materials discovery, protein interaction networks, and scientific knowledge graph learning (23.7k+ stars)
* [DGL](https://github.com/dmlc/dgl) ⭐ 14,281 | 🐛 607 | 🌐 Python | 📅 2025-07-31 - Deep Graph Library for scalable deep learning on graphs, powering molecular modeling, materials discovery, protein interaction networks, and scientific knowledge graph learning across PyTorch, TensorFlow, and MXNet backends (14K+ stars)
* [PyMC](https://github.com/pymc-devs/pymc) ⭐ 9,727 | 🐛 488 | 🌐 Python | 📅 2026-08-24 - Probabilistic programming
* [Qiskit](https://github.com/Qiskit/qiskit) ⭐ 7,754 | 🐛 1,164 | 🌐 Python | 📅 2026-08-28 - Open-source SDK for working with quantum computers at the level of extended quantum circuits, operators, and primitives, enabling quantum algorithm development for quantum chemistry, materials science, and optimization research (IBM, 7.4K+ stars, Apache 2.0)
* [Newton](https://github.com/newton-physics/newton) ⭐ 5,551 | 🐛 413 | 🌐 Python | 📅 2026-08-28 - GPU-accelerated differentiable physics simulation engine built on NVIDIA Warp, supporting rigid/soft body, cloth, and gradient-based optimization for scientific ML, initiated by Disney Research, DeepMind, and NVIDIA (Linux Foundation, Apache 2.0, 2025)
* [PennyLane](https://github.com/PennyLaneAI/pennylane) ⭐ 3,440 | 🐛 429 | 🌐 Python | 📅 2026-08-28 - Cross-platform library for differentiable programming of quantum computers with automatic differentiation, enabling hybrid quantum-classical machine learning for quantum chemistry, quantum physics, and NISQ algorithm research (Xanadu, 3k+ stars)
* [DeePMD-kit](https://github.com/deepmodeling/deepmd-kit) ⭐ 2,024 | 🐛 218 | 🌐 Python | 📅 2026-08-28 - Deep learning package for many-body potential energy representation and molecular dynamics, achieving quantum-mechanical accuracy with classical MD efficiency (DeepModeling, Gordon Bell Prize 2020, 1.9k+ stars)
* [OpenMM](https://github.com/openmm/openmm) ⭐ 1,960 | 🐛 431 | 🌐 C++ | 📅 2026-08-26 - High-performance molecular simulation toolkit
* [MDAnalysis](https://github.com/MDAnalysis/mdanalysis) ⭐ 1,638 | 🐛 534 | 🌐 Python | 📅 2026-08-18 - Molecular dynamics analysis
* [e3nn](https://github.com/e3nn/e3nn) ⭐ 1,280 | 🐛 33 | 🌐 Python | 📅 2026-02-13 - Euclidean neural networks for arbitrary point transformations enabling E(3)-equivariant deep learning, foundational library for building geometry-aware neural networks in molecular dynamics, materials science, and physics
* [JAX-CFD](https://github.com/google/jax-cfd) ⭐ 961 | 🐛 31 | 🌐 Jupyter Notebook | 📅 2026-07-08 - Computational fluid dynamics in JAX, enabling differentiable Navier-Stokes simulations with automatic differentiation for ML-accelerated CFD research, supporting turbulence modeling, convection-diffusion, and complex boundary conditions on CPUs and GPUs (Google Research, 947+ stars)
* [Nano World Model](https://github.com/simchowitzlabpublic/nano-world-model) ⭐ 719 | 🐛 6 | 🌐 Python | 📅 2026-06-15 - Minimalist, batteries-included repository for training video world models with diffusion-forcing, supporting long-horizon rollouts, 3D point-cloud generation, and model-predictive control with pretrained checkpoints (Simchowitz Lab, 700+ stars, MIT License, 2026)
* [TorchMD](https://github.com/torchmd/torchmd) ⭐ 718 | 🐛 10 | 🌐 Python | 📅 2026-04-21 - End-to-end molecular dynamics engine built on PyTorch, enabling differentiable simulations with neural network potentials and GPU acceleration for machine learning-accelerated molecular dynamics (MIT License, 707+ stars)
* [AI2BMD](https://github.com/microsoft/AI2BMD) ⭐ 582 | 🐛 26 | 🌐 Python | 📅 2025-02-18 - Microsoft's AI-powered ab initio biomolecular dynamics simulation achieving quantum-mechanical accuracy for proteins with 10,000+ atoms, orders of magnitude faster than DFT using protein fragmentation and ML force fields (Nature 2024)
* [TorchSim](https://github.com/TorchSim/torch-sim) ⭐ 487 | 🐛 25 | 🌐 Python | 📅 2026-08-21 - PyTorch-native atomistic simulation engine for the machine-learned interatomic potential (MLIP) era, enabling batched molecular dynamics and structural relaxation with automatic GPU memory management; supports MACE, Fairchem, SevenNet, ORB, MatterSim and other popular MLIPs with up to 100x speedup over ASE (Radical AI, AI for Science 2026, 468+ stars, MIT License)
* [SO3LR](https://github.com/general-molecular-simulations/so3lr) ⭐ 231 | 🐛 12 | 🌐 Python | 📅 2026-04-17 - Pretrained machine-learned force field for (bio)molecular simulations combining the fast SO3krates neural network for semi-local interactions with universal pairwise force fields for short-range repulsion, long-range electrostatics, and dispersion interactions; supports geometry optimization, NVT/NPT/NVE MD, fine-tuning, ASE calculator, and JAX-MD integration (JACS 2025, 218+ stars, MIT License)
* [MDtrajNet](https://arxiv.org/abs/2505.16301) - Neural network foundation model that directly generates MD trajectories bypassing force calculations, accelerating simulations by up to 100× with equivariant Transformer architecture (2025)
* [ASE](https://wiki.fysik.dtu.dk/ase/) - Atomic Simulation Environment for materials modeling

***

## 🎓 Educational Resources

### Courses & Tutorials

* [AI for Everyone (Coursera)](https://www.coursera.org/learn/ai-for-everyone) - Basic AI concepts
* [CS229 Machine Learning](https://cs229.stanford.edu/) - Stanford ML course
* [MIT 6.034 Artificial Intelligence](https://ocw.mit.edu/courses/6-034-artificial-intelligence-fall-2010/) - AI fundamentals

### Open Access Educational Materials

* [SciML Book](https://github.com/SciML/SciMLBook) ⭐ 2,036 | 🐛 10 | 🌐 HTML | 📅 2026-08-26 - Parallel Computing and Scientific Machine Learning: MIT 18.337J/6.338J course materials (1.9k+ stars)
* [Dive into Deep Learning](https://d2l.ai/) - Interactive deep learning book with code implementations
* [The Elements of Statistical Learning](https://hastie.su.stanford.edu/ElemStatLearn/) - Classic ML textbook freely available
* [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) - Free online book by Michael Nielsen

### 📋 Paper Collections & Repositories

* [Physics-Informed Neural Networks Papers](https://github.com/idrl-lab/PINNpapers) ⭐ 1,535 | 🐛 6 | 🌐 Python | 📅 2023-12-08 - PINN research collection
* [Awesome Scientific Language Models](https://github.com/yuzhimanhua/Awesome-Scientific-Language-Models) ⭐ 664 | 🐛 3 | 📅 2025-06-21 - Curated scientific LLM papers (260+ models)
* [Awesome LLM Scientific Discovery](https://github.com/HKUST-KnowComp/Awesome-LLM-Scientific-Discovery) ⭐ 433 | 🐛 4 | 📅 2026-07-03 - LLM papers for scientific discovery
* [Awesome AI Scientist Papers](https://github.com/openags/Awesome-AI-Scientist-Papers) ⭐ 170 | 🐛 7 | 📅 2026-06-25 - Autonomous AI scientist research
* [AI4Research Papers](https://github.com/du-nlp-lab/LLM4SR) ⭐ 132 | 🐛 2 | 📅 2025-01-22 - LLM for scientific research papers
* [Awesome Agents for Science](https://github.com/OSU-NLP-Group/awesome-agents4science) ⭐ 99 | 🐛 6 | 📅 2024-12-11 - LLM agents across scientific domains
* [Scientific Computing with ML Papers](https://sciml.ai/papers/) - Scientific ML paper repository
* [Simulation-Based Inference Papers & Tools](https://simulation-based-inference.org/papers/) - Community-maintained SBI research portal with papers and software

### YouTube Channels

* [Two Minute Papers](https://www.youtube.com/c/KárolyZsolnai) - AI research summaries
* [3Blue1Brown](https://www.youtube.com/c/3blue1brown) - Mathematical concepts
* [AI Coffee Break](https://www.youtube.com/c/AICoffeeBreak) - AI paper reviews
* [Steve Brunton](https://www.youtube.com/c/Eigensteve) - Data-driven methods
* [Nathan Kutz](https://www.youtube.com/c/NathanKutz) - Applied mathematics
* [Physics Informed Machine Learning](https://www.youtube.com/c/PIML) - SciML tutorials

***

## 🏛 Research Communities

### Conferences

* [NeurIPS](https://neurips.cc/) - Machine learning conference
* [ICML](https://icml.cc/) - International Conference on Machine Learning
* [AI for Science Workshop](https://ai4sciencecommunity.github.io/) - Specialized workshops

### Organizations

* [Partnership on AI](https://partnershiponai.org/) - AI research collaboration
* [Allen Institute for AI](https://allenai.org/) - AI research institute
* [OpenAI](https://openai.com/) - AI research and deployment

### Online Communities

* [r/MachineLearning](https://reddit.com/r/MachineLearning) - ML discussions
* [AI Alignment Forum](https://www.alignmentforum.org/) - AI safety research
* [Distill](https://distill.pub/) - Visual explanations of ML

***

## 📚 Related Awesome Lists

This project builds upon and complements several excellent resources:

### 🎯 Specialized Collections

* [awesome-ai4s](https://github.com/hyperai/awesome-ai4s) ⭐ 3,338 | 🐛 11 | 📅 2026-07-22 - 200+ AI for Science papers with Chinese interpretations
* [Awesome Scientific Skills](https://github.com/InternScience/Awesome-Scientific-Skills) ⭐ 522 | 🐛 8 | 📅 2026-08-13 - Curated collection of agent skills for scientific research (InternScience, 493+ stars, 2026)
* [Awesome Foundation Models for Weather and Climate](https://github.com/shengchaochen82/Awesome-Foundation-Models-for-Weather-and-Climate) ⭐ 298 | 🐛 0 | 📅 2025-02-03 - Comprehensive survey of foundation models for weather and climate data understanding
* [Awesome AI Scientist Papers](https://github.com/openags/Awesome-AI-Scientist-Papers) ⭐ 170 | 🐛 7 | 📅 2026-06-25 - Autonomous AI scientist research
* [Awesome Agents for Science](https://github.com/OSU-NLP-Group/awesome-agents4science) ⭐ 99 | 🐛 6 | 📅 2024-12-11 - LLM agents across scientific domains
* [Awesome Scientific Machine Learning](https://github.com/MartinuzziFrancesco/awesome-scientific-machine-learning) ⭐ 89 | 🐛 2 | 📅 2023-12-22 - Physics-informed ML and SciML
* [Awesome LLM Agents Scientific Discovery](https://github.com/zhoujieli/Awesome-LLM-Agents-Scientific-Discovery) ⭐ 80 | 🐛 4 | 📅 2026-07-28 - Biomedical AI agents

### 📊 Paper & Research Collections

* [PINNs Paper Collection](https://github.com/idrl-lab/PINNpapers) ⭐ 1,535 | 🐛 6 | 🌐 Python | 📅 2023-12-08 - Physics-informed neural networks research
* [Scientific LLM Papers](https://github.com/yuzhimanhua/Awesome-Scientific-Language-Models) ⭐ 664 | 🐛 3 | 📅 2025-06-21 - 260+ scientific language models
* [LLM4SR Repository](https://github.com/du-nlp-lab/LLM4SR) ⭐ 132 | 🐛 2 | 📅 2025-01-22 - LLM for scientific research survey materials
* [Awesome Scientific LLM Benchmarks](https://github.com/subinium/Awesome-Scientific-LLM-Benchmarks) ⭐ 33 | 🐛 0 | 🌐 TypeScript | 📅 2026-08-03 - Curated, accuracy-first collection of benchmarks for evaluating LLMs on scientific reasoning and discovery across mathematics, physics, chemistry, materials science, biology, and agentic science (subinium, 29+ stars, MIT License, 2026)
* [SciML Papers](https://sciml.ai/papers/) - Scientific computing and machine learning papers

### 🌟 Key Insights from These Collections

* **Current Focus**: Shift from tool-level assistance to autonomous scientific agents
* **Emerging Trends**: Multi-modal scientific models, self-improving research systems
* **Research Gaps**: Evaluation frameworks, ethical governance, human-AI collaboration
* **Future Directions**: Fully autonomous discovery cycles, robotic lab integration

***

## 🤝 Contributing

We welcome contributions! Please see our [Contributing Guidelines](CONTRIBUTING.md) for details.

### How to Contribute

1. Fork this repository
2. Add your resource in the appropriate section
3. Ensure the format matches existing entries
4. Submit a pull request with a clear description

### Contribution Guidelines

* Ensure the resource is actively maintained
* Include a brief, clear description
* Check for duplicates before adding
* Use proper markdown formatting

***

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

***

## 🙏 Acknowledgments

Special thanks to all researchers and developers pushing the boundaries of AI for Science. This list is inspired by the awesome community and the transformative potential of AI in scientific discovery.

**Star ⭐ this repository if you find it helpful!**

***

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-28._
