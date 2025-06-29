# debate-AI
# AI Debate Simulator 🎤

A dynamic debate system where two AI agents (Scientist vs Philosopher) argue on any topic, with an AI judge declaring a winner.

## Features
-  Two distinct AI personas
-  Impartial judge evaluation
-  No repeated arguments
-  Fast execution (~20 sec on Colab)

## Installation
```bash
!pip install transformers accelerate
```
## Usage
Run in Google Colab: https://colab.research.google.com/assets/colab-badge.svg

Enter your debate topic when prompted

Watch 4 rounds of debate (2 arguments per side)

Receive final judgment

## Customization
Change roles: Modify Scientist (pro)/Philosopher (anti) in code

Adjust rounds: Edit range(2) in main loop

Try different models: Replace TinyLlama-1.1B with other HuggingFace models

## Output Example

Enter topic: Should TikTok be banned?

Scientist: TikTok's algorithm poses national security risks...
Philosopher: Banning apps sets dangerous precedent for censorship...
...
=== JUDGE ===
Winner: Scientist - demonstrated clearer security concerns
