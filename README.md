# Abbas Aamir

CS undergraduate in Berlin. Interested in machine learning, backend systems, and building things that are actually useful.

Currently looking for Werkstudent roles in Berlin and nearby cities.

---

## Projects

**[RAG Bench](https://github.com/aamirabbas858/rag-bench)** &nbsp;·&nbsp; [Live](https://rag-bench-byabbasaamir1.streamlit.app)  
RAG evaluation dashboard that measures pipeline quality across four metrics from the RAGAS paper — faithfulness, answer relevancy, context precision, and context recall. The RAGAS library was the obvious choice but it fails with the newer Google AI Studio key format. Instead of working around it, I implemented all four metrics from scratch using Gemini as the judge via direct REST calls, one prompt per metric. Results on 20 test questions: faithfulness 1.000, answer relevancy 0.975, context recall 0.980, context precision 0.367 — the low precision is intentional signal, not a bug.  
`Python` `ChromaDB` `Gemini API` `Streamlit` `Plotly`

**[Wayfare](https://github.com/aamirabbas858/wayfare)** &nbsp;·&nbsp; [Live](https://wayfare-xi.vercel.app)  
AI travel planner that forces real-time web search before every recommendation — so it knows what an Oyster card costs this week instead of guessing from training data. Features a day-color-coded Mapbox map, honest budget reality checks, and streaming output. Went through three LLM backends deliberately: started on Claude for output quality, migrated to Groq (Llama 3.3 70B) to bring infrastructure costs to zero, then moved to Gemini for cleaner structured JSON output and consistency with the rest of my stack.  
`Next.js` `TypeScript` `Gemini API` `Groq` `Tavily` `Mapbox`

**[FIFA World Cup 2026 Predictor](https://github.com/aamirabbas858/FIFA-World-Cup-2026-Prediction-ML-Model)** &nbsp;·&nbsp; [Live](https://fifa-world-cup-2026-prediction-ml-model-001.streamlit.app)  
End-to-end ML pipeline trained on 49,000+ historical match results, FIFA world rankings, and EA Sports FC 24 player ratings. Compared Logistic Regression, Random Forest, and XGBoost — XGBoost scored highest at 60.4% accuracy, but Logistic Regression was used for the final simulation because its probability outputs are better calibrated for win/draw/loss distributions. Runs 10,000 Monte Carlo simulations of the full 48-team bracket including group stage, knockouts, and final.  
`Python` `scikit-learn` `XGBoost` `Streamlit` `Pandas`

---

## Stack

`Python` `JavaScript` `Next.js` `scikit-learn` `Streamlit` `SQL` `Git`

---

[LinkedIn](https://www.linkedin.com/in/abbasaamir) &nbsp;·&nbsp; Berlin, Germany
