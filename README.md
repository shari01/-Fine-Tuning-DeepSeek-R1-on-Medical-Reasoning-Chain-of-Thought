# -Fine-Tuning-DeepSeek-R1-on-Medical-Reasoning-COTR _model
<h2>🚀 Fine-Tuning DeepSeek-R1 on Medical Reasoning (Chain-of-Thought) Dataset</h2>

<p>This project demonstrates <strong>fine-tuning the DeepSeek-R1-Distill-Llama-8B model</strong> using a 
<strong>medical clinical reasoning dataset</strong> (FreedomIntelligence/medical-o1-reasoning-SFT) with the help of 
<strong>LoRA adapters</strong> and the <strong>Unsloth</strong> library for fast and memory-efficient training.</p>

<h3>📋 Key Features:</h3>
<ul>
  <li><strong>Model:</strong> DeepSeek-R1-Distill-Llama-8B (4-bit quantized for efficient fine-tuning)</li>
  <li><strong>Method:</strong> LoRA (Low-Rank Adaptation) + Unsloth optimization</li>
  <li><strong>Dataset:</strong> Medical clinical reasoning and diagnostic questions</li>
  <li><strong>Prompt Style:</strong> Chain-of-thought (CoT) reasoning + structured answers</li>
  <li><strong>Tracking:</strong> Integrated Weights and Biases (WandB) experiment tracking</li>
  <li><strong>Testing:</strong> Tested on unseen medical pathway questions (e.g., PI3K-AKT, MAPK pathways)</li>
</ul>

<h3>🛠 Technologies Used:</h3>
<ul>
  <li>Python</li>
  <li>HuggingFace Transformers & Datasets</li>
  <li>Unsloth</li>
  <li>TRL (SFTTrainer)</li>
  <li>WandB for experiment logging</li>
</ul>

<h3>🎯 Goal:</h3>
<blockquote>
  Build a lightweight, domain-specific, reasoning-strong LLM for <strong>medical question answering</strong> and 
  <strong>clinical reasoning tasks</strong>.
</blockquote>
