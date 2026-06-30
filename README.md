# Time-Series Sustainability Analysis

## Project Overview
This repository contains an independent time-series forecasting project designed to predict hourly electricity consumption. Utilizing **IBM's Granite TinyTimeMixers (TTM)**—a cutting-edge, lightweight foundation model with under 1 million parameters—the model performs zero-shot forecasting on real-world energy data to identify consumption patterns and predict future trends efficiently on standard hardware.

## Project Context
This project was developed independently to explore the intersection of AI and environmental sustainability, directly aligning with the core skills and values championed by the **IBM SkillsBuild and 1M1B (1 Million Brighter Lives) partnership**. By moving beyond theoretical concepts, this analysis applies generative AI principles to real-world datasets to tackle modern energy challenges.

## Tech Stack & Tools
* **Language:** Python 3
* **Environment:** Google Colab
* **AI Model:** IBM Granite TinyTimeMixers (`granite-tsfm`)
* **Libraries:** `torch`, `pandas`, `matplotlib`, `datasets`

## Dataset
The model analyzes historical hourly electricity demand data from Spain, focusing on evaluating the actual total load to generate accurate, multi-step future forecasts.
