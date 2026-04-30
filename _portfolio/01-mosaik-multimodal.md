---
title: "Mosaik Reverse Prompting + Multimodal Analysis"
excerpt: "Multimodal pipeline combining YOLO panel segmentation, OCR, and VLM/LLM-based reverse prompting to extract structured semantic representations from 26K–64K mid-20th-century German comic panels. Ongoing research at Stanford."
collection: portfolio
date: 2026-04-01
permalink: /portfolio/mosaik-multimodal/
---

**Role:** Lead researcher · **Affiliation:** Stanford University · **Status:** Ongoing

## Overview

Mosaik is a multimodal data pipeline built to process tens of thousands of mid-20th-century German comic panels at scale. The goal: turn unstructured visual-textual material into structured, queryable semantic representations that humanities researchers can actually analyze.

## What I built

- **Panel segmentation** using YOLO-based object detection paired with Magic3Comic to break full pages into individual panels and text boxes.
- **Text extraction** through OCR layered with NLP cleaning (BERTopic and MALLET) to handle noisy historical typography and German-language idioms.
- **Reverse prompting workflow** leveraging vision-language and large language models to generate structured semantic annotations — scene type, character interactions, focal objects, perspective — directly from panel images.
- **Scaled inference** to handle 26K–64K panels, with annotation reliability checks (inter-annotator agreement, Cohen's κ) to validate model output against human reviewers.

## Why it matters

The pipeline lets humanities researchers ask quantitative questions about visual narrative — how shot composition shifts across decades, which character archetypes recur, how "Otherness" is depicted across publishers — that were previously impossible without manual coding of every panel. It's also a working example of how VLM/LLM systems can produce labeling that rivals human annotators, when paired with the right validation infrastructure.

## Tech stack

YOLO · Magic3Comic · BERTopic · MALLET · OCR · Vision-language models · Python · Jupyter
