# Clustering Traveler Preferences in East Asia Using Review Data

📌 Project Overview
With the growing interest in tourism, one common dilemma travelers face is choosing the right destination that matches their interests and lifestyle. This project aims to help solve that by analyzing user feedback and review ratings on various travel destinations across East Asia.
Using unsupervised machine learning, we cluster users based on similar travel preferences, helping future travelers or tourism platforms recommend personalized experiences.

🎯 Project Objective

To group travelers into meaningful clusters of similar interests based on their ratings and feedback on East Asian travel destinations, using unsupervised learning techniques.

🛠️ Methodology
Data Source: Travel reviews dataset containing user feedback and rating scores across multiple destinations in East Asia.

Preprocessing:

Cleaning missing and inconsistent data

Normalizing rating features

Dimensionality reduction (if necessary)

Algorithms Used:

K-Means Clustering
Segmenting travelers based on optimal cluster number (Elbow Method used for k selection)

Hierarchical Clustering
Providing visual insights through dendrograms and offering alternative grouping structures

📊 Tools & Technologies

| Tool                     | Purpose                          |
| ------------------------ | -------------------------------- |
| **Python**               | Core development                 |
| **Pandas / NumPy**       | Data processing and manipulation |
| **Scikit-learn**         | Clustering algorithms            |
| **Matplotlib / Seaborn** | Data visualization               |

📈 Key Outcomes

Travelers were segmented into clusters representing distinct travel interests (e.g., adventure seekers, cultural enthusiasts, nature lovers).
Visualizations and cluster profiling helped interpret preferences across the user base.
The model can serve as the foundation for personalized travel recommendation systems.
