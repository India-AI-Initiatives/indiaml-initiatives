# India AI Initiatives
Roadmap and sessions information of India AI Initiatives 

### Core thought: 
- try something real in respect to foundational AI models, 100% open(MIT) so anyone can use.

### People Criteria: 
- Researchers(DL,ML,AI), AI PMs, Dev+Infra(Inference+GPUs), Resources(Grants, Infra) people.

### Guidelines: 
- Be respectful to each other, be kind, feel free ask question curiously but don't probe/cross examine. 
- Every ones ideas are welcome, and there is nothing called stupid ideas. 
- No spamming to each other or in group, post things focused on AI Initiatives.
### Initiatives: 
- Learning - Sessions on GenAI/LLM by group. members every alternative week.
- releaseV1 - We will release v1 on LLM front.


# Session 01 - Building an AI DeepTech Community - Notes

Sat, 08 Feb 25

[Recording](#https://drive.google.com/file/d/1om9RkGsHi643uYcMmlXqEB24KO7CkFSj/view)


### I1 - Hardware Optimization Discussion

- Two main optimization paths discussed:
  - Training time optimization
  - Inference time optimization (recommended focus area)
- Hardware-level challenges:
  - Limited access to bare metal on cloud providers
  - Risk of hardware damage when testing optimizations
  - H100s and CM100s have overheating issues that reduce performance
  - GPUs perform better hot for inference but worse for training

### Model Architecture & Clustering Approaches

- Discussion of clustering approach for model optimization:
  - Combining sparse matrices into clusters while preserving context
  - Using mathematical functions to maintain contextual information
  - Example: Converting 10x10 grid with sparse data points into efficient clusters
  - Similar to approaches used in Grok with 2ms inference time vs standard 10ms
- Technical optimization methods mentioned:
  - CUDA kernel fusion
  - CUDA graphs
  - Triton fish kernel for training
  - V-Ray Singh for page attention

### Distributed Computing Proposal

- Suggestion to explore peer-to-peer training approach:
  - Utilizing consumer GPUs across multiple locations
  - Target audiences: gamers, former crypto miners
- Platforms mentioned:
  - Ray
  - Hugging Face’s Petal project
  - Hyperbolic platform
- Challenge: Need to effectively break down models into smaller modules

### Education & Community Building Initiatives

- Agreement to focus on two immediate priorities:
  - Hardware inference level optimization project
  - Developing 5-7 session AI learning curriculum
- Resources to be compiled:
  - Training data sources
  - Research paper repository
  - Hardware access guidelines
- Research sources mentioned:
  - arXiv
  - Research Gate
  - Mendeley
- Plan to hold regular meetings every 2-4 weeks
- Focus on building persistent community engagement

---
