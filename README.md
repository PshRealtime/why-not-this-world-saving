# Why not this way of world saving? A Novel Approach to Hydrogen Production Using Multistage Catalytic Cycles

## 🌍 Motivation

Hydrogen is essential for maintaining an industrialized society while mitigating climate change. Current large-scale hydrogen production attempts rely on electricity and require vast areas of land—up to 300 square kilometers per facility. Moreover, scaling this to meet the needs of agriculture, aviation, shipping, and steel industries would demand thousands of such facilities.

These methods, based on electrolysis and renewable electricity, face several challenges:

- High energy losses  
- Significant carbon footprint during ramp-up  
- Rapid electrode degradation due to the high binding energy of hydrogen  
- Underutilization of direct heat sources like geothermal or solar furnaces  

## 🎯 Project Goal

This project explores an alternative method: using **multistage catalytic reactions** to split water into hydrogen without relying solely on electricity. The goal is to investigate:

- Why conventional catalysts are not typically used for molecular hydrogen production  
- Whether breaking down water-splitting into incremental chemical steps is feasible  

### Key Hypothesis

- If starting from water: **reduce the hydrogen binding energy** step by step  
- If starting from molecular hydrogen: **increase the binding energy** step by step to form water  

The *(very likely unreachable)* goal is to identify catalytic reaction chains that form a closed loop, consuming water and heat while producing molecular hydrogen.

## 🤖 Leveraging Language Models

Large Language Models (LLMs) already demonstrate capabilities in chemical reasoning. This project leverages these models to:

- Identify candidate molecules that may release hydrogen at ~250 °C  
- Propose recycling steps for leftover molecules to regenerate prior reactants  
- Develop multistage chemical reaction chains forming a closed catalytic cycle  

In future stages, specialized AI tools like [ChemCrow](https://github.com/ur-whitelab/chemcrow-public) may be integrated for more precise modeling.

## 💡 Expectations

This project is not intended to replace industrial hydrogen production. Instead, it aims to:

- Serve as a **proof of concept** for identifying novel catalytic cycles  
- Provide a **framework or tool** for exploring chemical reaction paths using AI  
- Demonstrate the **potential of LLMs** in supporting chemical innovation

## 🧪 Code

This project includes **two parallel implementations** of the core functionality:

- 🦀 `rust/` — An implementation using Rust, along with the original Jupyter notebook prototype. The author likes to learn Rust and has a strong background in system programming, why it is used here.
- 🐍 Root directory — A Python-based version of the notebook, adapted to align with specific project constraints.

Both versions explore the same chemical logic but differ in language and execution strategy. The Python version is designed for easier experimentation and integration with AI models, while the Rust version emphasizes speed and scalability.