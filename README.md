# vibe_matcher
AI-powered vibe-based fashion recommender prototype

# 🎧 Vibe Matcher – AI Fashion Recommender

**Built by:** Pratik Pattanayak  
**Date:** 11 November 2025  
**Task:** Nexora AI Prototype Challenge  

## 🧠 Project Overview
Vibe Matcher is an AI-powered mini recommendation system that matches fashion products to a user’s “vibe” query using text embeddings and cosine similarity.

## ⚙️ Tech Stack
- Python (Pandas, NumPy, scikit-learn)
- OpenAI Embeddings (`text-embedding-ada-002`)
- Matplotlib for evaluation

## 🚀 How to Run
1. Clone repo  
2. Install dependencies:  
   ```
   pip install -r requirements.txt
   ```
3. add .env file
  ```OPENAI_API_KEY=your_api_key_here```
4. Run notebook
  ```jupyter notebook vibe_matcher.ipynb```
5.Sample Output
  ```
  	query	best_score	good_match	latency_ms	top_1	top_2	top_3	fallback
0	energetic urban chic	0.430749	False	3.7147	Urban Bomber Jacket	Minimalist Slip Dress	Sporty Mesh Sneakers	None
1	cozy weekend knit	0.467050	False	2.2034	Cozy Knit Sweater	Plaid Wool Coat	Silk Scarf	None
2	earthy festival boho	0.440874	False	1.9485	Boho Dress	Plaid Wool Coat	Silk Scarf	None
  ```

<img width="778" height="440" alt="image" src="https://github.com/user-attachments/assets/8b6618df-ae6b-42e4-8d55-08c5e0097528" />

##✨Why AI @ Nexora
AI at Nexora represents the intersection of innovation, creativity, and real-world problem solving. Nexora’s focus on building intelligent systems that understand human intent and deliver personalized, data-driven experiences deeply aligns with my passion for applied AI. I’m inspired by how Nexora integrates technology with empathy — designing solutions that not only automate but also elevate user experience. Joining this environment would allow me to contribute to impactful AI products while learning from a culture that values experimentation, precision, and continuous growth.

