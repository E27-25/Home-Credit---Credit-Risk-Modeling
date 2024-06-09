# Overview
The goal of this competition is to predict which clients are more likely to default on their loans. The evaluation will favor solutions that are stable over time.

Your participation may offer consumer finance providers a more reliable and longer-lasting way to assess a potential client’s default risk.

This Competition uses data from the official Kaggle competition: Home Credit - Credit Risk Model Stability

https://www.kaggle.com/competitions/home-credit-credit-risk-model-stability/overview

# Requirement: You need to
• Clarify the (quantifiable) benefit from leveraging LLM in the workflow e.g., scientist productivity,
model performance, etc.
• In the last 4 minutes of pitching, demonstrate using LLM on the editor up to 1 requests from
committee.

# Description
Sponsor by :
![alt text]([http://url/to/img.png](https://www.googleapis.com/download/storage/v1/b/kaggle-user-content/o/inbox%2F8266388%2F73dadc33233d4a062e29bf791c3b593c%2FLogo_KBTG-AIAT-01.png?generation=1716207228004823&alt=media))

# Evaluation
เราใช้ AUC Score แทน Gini Stability Score ใน Official Competition เพื่อป้องกันการทำ metric hacking

ในการคิดคะแนนหาผู้ชนะเราจะใช้ Gini Index โดยคำนวนได้จาก AUC Score ใน Kaggle นี้

𝐺𝑖𝑛𝑖 = 2 × 𝐴𝑈𝑅𝑂𝐶 − 1
Evaluation criteria:
• 20% Model performance (Gini)
• 30% Creativity
• 30% Pitching and communication
• 20% Live Demo (the last 4 mins)

Pircing: https://ai.google.dev/pricing
Model Benchmark: https://storage.googleapis.com/deepmind-media/gemini/gemini_v1_5_report.pdf
