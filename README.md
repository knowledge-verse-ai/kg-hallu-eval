# Knowledge Graph-Enhanced Hallucination Self-Detection in LLMs

## Abstract
Hallucinations, the generation of confident yet false statements, remain a major barrier to the safe and trustworthy deployment of large language models (LLMs). While existing self-detection methods show promise, we find that introducing structure into knowledge representation can greatly enhance their effectiveness. We propose a simple yet powerful approach that enriches hallucination self-detection with knowledge graphs, which organise facts as interconnected entities and relationships. By decomposing model outputs into these structured components, our method enables LLMs to analyse and verify their own claims with far greater precision than plain text. Across GPT-4o and Gemini-2.5-Flash, adding KGs to established self-detection methods boosts accuracy by up to 14% and F1 by 20%, while consistently improving AUC-PR. Our work shows that LLMs can recognise and analyse atomic facts in a knowledge graph even when their initial outputs contain inaccuracies, suggesting that KGs may unlock a latent fact-checking ability. This low-cost, model-agnostic approach paves the way toward safer, more trustworthy language models in real-world applications.

## Note
Our dataset and code will be made available publicly upon paper acceptance after the review process.
