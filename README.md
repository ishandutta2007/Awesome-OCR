# Awesome-OCR
## Top OCR Engines & Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Optical Character Recognition, Document Intelligence & Text Extraction*  
**Last updated: June 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** building **OCR Engines & Tools**. These solutions extract text from scanned documents, images, PDFs, handwritten notes, and complex layouts with high accuracy, layout analysis, and multilingual support.

**Examples** include Tesseract, EasyOCR, PaddleOCR, Kraken, SmolDocling OCR, MiniCPM-o, and LlamaOCR (the category leaders). Tools listed here emphasize **accuracy**, speed, layout preservation, table detection, and integration with document workflows.

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local execution, fine-tuning, and full customization — ideal for developers, researchers, and enterprises seeking privacy and unlimited usage.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS Products](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS Products

### OCR SaaS Pricing Comparison (2026)

| Product | Description | Pricing (Paid Tier) | Free Tier Limit |
| :--- | :--- | :--- | :--- |
| **[Google Cloud Vision](https://cloud.google.com/vision)** | General-purpose OCR with excellent multilingual support and handwriting recognition. | ~$1.50 per 1,000 units (billed per image/page) | **1,000 units/month** (Free forever) |
| **[Amazon Textract](https://aws.amazon.com/textract/)** | Specialized in extracting text, tables, and forms from structured documents. | $0.0015 - $0.015 per page (tiered by feature) | **1,000 pages/month** (First 3 months only) |
| **[Microsoft Azure AI Vision](https://azure.microsoft.com/en-us/products/ai-services/ai-vision)** | Enterprise OCR with layout analysis and seamless Azure integration. | ~$1.50 per 1,000 transactions | **5,000 transactions/month** (F0 tier) |
| **[OCR.space](https://ocr.space/)** | Lightweight web-based OCR API with a generous free tier for developers. | $30/month for 300,000 requests | **25,000 requests/month** (Free) |
| **[Nanonets](https://nanonets.com/)** | AI-driven IDP platform for automated invoice and receipt processing. | $0.30/page + $499/mo starter fee | **500 pages** (One-time trial) |
| **[ABBYY Vantage](https://www.abbyy.com/vantage/)** | High-accuracy enterprise Intelligent Document Processing (IDP). | Custom (~$0.02/page + setup) | **2,000 pages** (60-day trial) |
| **[Rossum](https://rossum.ai/)** | AI-native document extraction focused on Accounts Payable and logistics. | Starts at ~$1,500/month (Annual commitment) | **14-day trial** (No perpetual free tier) |

### Key Considerations
- **"Free Forever" vs. Trial:** Google and Azure offer perpetual monthly limits, while AWS and ABBYY use time-limited trials.
- **Structured Data:** Use **Amazon Textract** or **Nanonets** if you need to extract tables and forms specifically.
- **High Volume / Low Cost:** **OCR.space** offers the highest number of free requests for basic OCR needs.

## Open-Source GitHub Projects

### Dedicated OCR Engines & Tools

- **[Tesseract](https://github.com/tesseract-ocr/tesseract)**  
  The most widely used open-source OCR engine. Highly accurate, supports 100+ languages, and serves as the foundation for many document intelligence pipelines.

- **[EasyOCR](https://github.com/JaidedAI/EasyOCR)**  
  Ready-to-use OCR library with excellent multilingual support and simple Python API. Great for quick integration and production use.

- **[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)**  
  State-of-the-art OCR toolkit from PaddlePaddle with ultra-high accuracy, layout analysis, and support for 80+ languages.

- **[Kraken](https://github.com/mittagessen/kraken)**  
  Advanced open-source OCR engine focused on historical documents, manuscripts, and complex layouts with strong layout segmentation.

- **[SmolDocling OCR](https://github.com/ds4sd/docling)**  
  Lightweight, high-performance document understanding model optimized for structure-aware text extraction from PDFs and images.

- **[MiniCPM-o](https://github.com/OpenBMB/MiniCPM-o)**  
  Multimodal open-source model with excellent OCR and document understanding capabilities running efficiently on local hardware.

- **[LlamaOCR](https://github.com/search?q=LlamaOCR)**  
  Community-driven OCR solutions built on Llama models for high-accuracy text extraction and reasoning over documents.

- **[DocTR](https://github.com/mindee/doctr)**  
  End-to-end document text recognition library with powerful detection and recognition models.

- **[RapidOCR](https://github.com/RapidAI/RapidOCR)**  
  Ultra-fast OCR engine optimized for real-time applications and mobile/edge deployment.

- **[Calamari](https://github.com/Calamari-OCR/calamari)**  
  High-performance OCR engine based on deep learning, particularly strong for historical and degraded documents.

### Additional Strong Open-Source Options

- **[TrOCR (Microsoft)](https://github.com/microsoft/unilm/tree/master/trocr)** — Transformer-based OCR model.
- **[Pytesseract** wrappers and advanced pipelines.
- **[LayoutParser](https://github.com/Layout-Parser/layout-parser)** — Unified toolkit for document layout analysis.
- **[Unstructured](https://github.com/Unstructured-IO/unstructured)** — Library for preprocessing and extracting elements from complex documents.
- **[OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF)** — Adds searchable OCR layers to existing PDFs.
- Many **Ollama + Vision** and **Llama 3.2 Vision** based OCR agents for multimodal document understanding.

**Frameworks for building custom OCR systems**: Combine **PaddleOCR**, **EasyOCR**, or **DocTR** with **Unstructured**, **LayoutParser**, and **LangChain** for complete document intelligence pipelines.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- OCR accuracy varies significantly based on document quality, language, and font. Always validate extracted text for critical applications.
- Self-hosted open-source solutions may require GPU acceleration for best performance on large documents.

---

**Made for developers, data scientists, archivists, and document automation teams.**  
Let's make text extraction more accurate, accessible, and open.