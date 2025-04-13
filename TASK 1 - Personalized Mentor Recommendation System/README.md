# Mentor Recommendation System Using NLP & Cosine Similarity

## Overview
This project aims to match **aspirants** with the most suitable **mentors** based on their preferred subjects, target law colleges, and learning styles. By leveraging **Natural Language Processing (NLP)** techniques like **TF-IDF vectorization** and **cosine similarity**, the system efficiently identifies mentors who align best with aspirants’ preferences.

## Key Features
- Uses **TF-IDF vectorization** to analyze aspirant and mentor profiles based on subject expertise.
- Implements **cosine similarity** to compute compatibility scores between mentors and aspirants.
- Processes **structured mock data** consisting of 300 aspirants and mentor profiles.
- Incorporates a **feedback system** to dynamically refine recommendations over time.

---

## Repository Structure
```
mentor_recommendation/
 ├── aspirants_data.csv          # Sample dataset for aspirants
 ├── mentors_data.csv            # Sample dataset for mentors
 ├── mentor_recommendation.ipynb # Google Colab notebook with step-by-step implementation
 ├── README.md                   # Documentation outlining the project
```

---

## Installation & Setup

Before running the recommendation system, install the necessary dependencies:

```bash
pip install pandas scikit-learn numpy
```

Ensure that the files `aspirants_data.csv` and `mentors_data.csv` are available in your working directory.

---

## How It Works
1. **User profiles (aspirants and mentors)** are preprocessed using **TF-IDF vectorization** to extract meaningful text features.
2. **Cosine similarity** is computed between aspirant profiles and mentor profiles to determine the best match.
3. **Top mentor recommendations** are generated based on similarity scores.
4. **Feedback-based weight adjustments** improve the algorithm over time, ensuring better recommendations for future aspirants.

---

## Usage Instructions

Run the recommendation system in **Google Colab** or locally using:

```python
python mentor_recommendation.ipynb
```

Once executed, the system will provide the **top 3 mentors** for each aspirant.

To further experiment with the model, users can:
- Modify the dataset to include additional attributes such as experience level and specialization.
- Adjust feature weighting in the feedback system to enhance recommendation accuracy.
- Extend the model to incorporate **collaborative filtering techniques** for smarter predictions.

---

## Contribution Guidelines
Enhancements and contributions to the system are encouraged. Possible improvements include:
- Refining **NLP-based profile matching** for better accuracy.
- Expanding the dataset with real-world mentor and aspirant profiles.
- Enhancing the **feedback loop** with explicit user reviews and ranking systems.

If you'd like to contribute, submit a **Pull Request** or open an **Issue** on **GitHub**.

---

## License
This project is licensed under the **MIT License**, allowing open-source usage and modifications.

---


