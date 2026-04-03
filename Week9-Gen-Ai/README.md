# Week 9 — Generative AI

Generative AI fundamentals, Prompt Engineering, RAG, and GANs for the AI/ML Fellowship at GDGOC COMSATS Attock.

## Task 15: GenAI Sprint Lab

### Topics Covered

#### Section 0: Foundation + Setup (Day 1)
- **GenAI Foundations & Model Landscape**
  - What is Generative AI?
  - Types of GenAI models (LLM, Diffusion, GAN)
  - API-based vs local models
  - Model comparison (Gemini, Llama, Mistral, Hugging Face)
  - Choosing a "default model" for the week

- **Prompt Engineering**
  - Anatomy of a prompt
  - System vs user instructions
  - Zero-shot / Few-shot prompting
  - Role prompting
  - Chain-of-thought prompting
  - Output formatting
  - Experiment: Bad prompt → Good prompt
  - Compare normal vs chain-of-thought prompting
  - Model comparison: Gemini vs Hugging Face

#### Section 1: Tokenization Lab (Day 2)
- Tokenize text using different models (BERT, GPT2)
- Compare token counts
- Understand tokenization impact on API costs

#### Section 2: Working with LLMs (Day 3)
- **Text Summarization**
  - Generate summary using LLM (Gemini + Hugging Face)
  - Experiment with prompts and role-playing

- **Chatbot**
  - Build a simple chatbot
  - Maintain conversation history

#### Section 3: RAG Fundamentals (Day 4)
- What is Retrieval Augmented Generation (RAG)?
- Why LLMs forget information
- Embeddings concept
- Vector search (similarity-based retrieval)

#### Section 4: Build Mini RAG App (Day 5)
- Create document collection (10+ documents)
- Generate embeddings using Sentence Transformers
- Implement similarity search
- Build RAG query system
- Ask custom questions from documents

#### Section 5: GAN Fundamentals (Day 6)
- What are GANs?
- Generator vs Discriminator roles
- Why GANs mattered historically
- GAN vs Diffusion comparison
- Simple GAN implementation in PyTorch
- GAN Image Generation
- Data Augmentation using GANs
- When synthetic data is risky

#### Section 6: Final Mini Project (Day 6-7)
- **Build: Text Analysis Tool**
  - Token Counter function
  - Summarizer (Gemini)
  - Combined analysis tool
  - Bonus: Sentiment Analysis (Hugging Face)

## Deliverables
- ✅ Notebook completed
- ✅ Tokenization outputs
- ✅ Summarization working
- ✅ Chatbot working
- ✅ Final project completed
- ✅ Short explanation (50-100 words)

## Tools Used
- **Google Gemini** - Free tier LLM API (https://makersuite.google.com/app)
- **Hugging Face** - Free local models and pipelines
- **Sentence Transformers** - For embeddings
- **PyTorch** - For GAN implementation

## Concepts Covered
- Generative AI fundamentals
- Prompt Engineering (Zero-shot, Few-shot, Chain-of-thought)
- Tokenization and token economics
- LLM APIs and local models
- Text summarization
- Chatbot implementation
- RAG (Retrieval Augmented Generation)
- Embeddings and vector search
- GANs (Generator, Discriminator)
- Data augmentation with GANs
- Text analysis tools

## Structure
```
Week9-gen-ai/
├── GenAI.ipynb
└── README.md
```

## Notes
- API key required from Google AI Studio
- All Hugging Face operations are free and local (no API needed)
- Notebook designed for Google Colab execution
- Gemini provides generous free tier for API-based operations

## Author
Meher Ali - AI/ML Fellowship, GDGOC COMSATS Attock