# Agentic Air × Microbiome Decision Support System (RAG + Tool-Using AI)

AI is no longer just a research concept — it’s becoming an essential part of how complex enterprises and mission organizations operate, integrate data, and make decisions. This project demonstrates an **AI-enabled, agentic decision-support system** built to help users explore and interpret relationships between **air pollution metrics** (EPA AQS) and **nasal microbiome measures** at scale.

This system combines:
- a real-world scientific workflow and data pipeline (cleaning, normalization, reshaping),
- an interactive visualization layer (Shiny + Leaflet + correlation panels),
- and an AI layer that operationalizes **RAG** and **tool-using agents** to produce grounded, traceable outputs.

Join us as we turn cutting-edge AI into operational reality.

## What This Project Does
- Ingests and validates an analysis-ready dataset (`combined.csv`) containing:
  - city, year, genus, pollutant, concentrationppm, lat/lon, and microbiome metrics
- Provides deterministic **analysis tools**:
  - filtering, correlation (Pearson/Spearman/Kendall), per-year correlation tables
  - time-period comparisons to explore longitudinal shifts (e.g., pre/post-1990s)
- Adds an AI layer that supports:
  - **Retrieval-Augmented Generation (RAG)** over a public knowledge base (methods + literature)
  - an **agent router** that selects tools and produces structured outputs
  - stakeholder-ready **Decision Memos** with findings, limitations, and recommended next steps
- Preserves an interactive explorer:
  - Shiny app with map layers, heatmaps, genus filtering, and correlation panels

## Why It Matters
Enterprise and mission environments rarely provide clean, single-source data. This project reflects operational realities:
- heterogeneous datasets and evolving schemas
- interpretability and traceability requirements
- decision outputs tailored to technical and non-technical stakeholders
- reproducible, reusable engineering patterns

## Live Demo
- Shiny App: Air × Microbiome Explorer (Genus/Raw)
  - https://cierrab2319.shinyapps.io/air-micro-explorer/

## Architecture (High Level)


