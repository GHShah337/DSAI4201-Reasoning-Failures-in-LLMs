# Reasoning Failures in LLMs

## Overview
This project investigates reasoning failures in Large Language Models (LLMs) and Vision-Language Models (VLMs) across three domains:
- Physics and scientific reasoning
- Perception-based visual understanding
- Visual spatial reasoning

We evaluate multiple models including:
- ChatGPT
- Claude
- Gemini
- Grok

## Methodology
We designed benchmark-style tasks inspired by research papers such as AutoBench, MoRA, BlindTest, and SVAT.

Each problem was tested across multiple models using identical prompts and inputs. The responses were recorded and evaluated based on correctness and reasoning ability.

## Tasks
The tasks include:
- Character detection (fine-grained perception)
- Counting objects and intersections
- Spatial positioning (left/right, alignment)
- Dynamic reasoning (object movement and stability)

## Results
Our experiments show that:
- Models struggle with fine-grained visual tasks
- Performance drops in spatial reasoning tasks
- Models are sensitive to prompt variations
- Gemini performed better in visual perception tasks

## Repository Structure
- `problem_sets/` → contains test cases
- `images/` → test images used
- `responses/` → model outputs
- `results/` → compiled results
- `analysis/` → insights and observations
- `report/` → final report

## Key Insight
Models can recognize objects, but struggle to understand relationships, spatial structure, and dynamic interactions.

## Authors
- Ghulam Shah(60106493)
- Syed Abdullah(60104641)
