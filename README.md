# Career Center Modeles MindMatch 🚀

## Overview

This repository contains the implementation of various data analysis models aimed at optimizing the Employability Pole platform. The models cover a range of functionalities, including data clustering, recommendation systems, reporting, prediction, chatbots, and rating systems. This README provides an overview of each model's purpose, methodology, and key outcomes.

## Models Description

### 1. **Data Clustering Model** 📊

- **Purpose:** This model aims to cluster job offers and resumes based on their content, enabling better organization and understanding of the dataset.
  
- **Methodology:**
  - Applied KMeans clustering on job offers and resumes datasets.
  - Transformed job descriptions using SentenceTransformer for embedding.
  - Visualized clustering results through scatter plots and histograms.

### 2. **Recommendation Systems** 🌐

#### a. **Content-Based Recommendation**

- **Purpose:** Provide personalized recommendations for job seekers based on their profiles and preferences.

- **Methodology:**
  - Utilized content-based recommendation approaches.
  - Developed a Siamese network architecture for matching embeddings of job offers and profiles.
  - Trained the model to identify the best matches for personalized recommendations.

#### b. **Hybrid Recommendation System**

- **Purpose:** Combine content-based and collaborative filtering techniques for enhanced job recommendations.

- **Methodology:**
  - Calculated TF-IDF vectors for job seekers' skills.
  - Computed cosine similarity to find similar job seekers for each job offer.
  - Recommended top matching job seekers for each job offer.

### 3. **Reporting and Prediction Model** 📈

- **Purpose:** Analyze data, provide insights, and make predictions to support decision-making for both job seekers and employers.

- **Methodology:**
  - Conducted skills and qualifications analysis.
  - Predicted future job market trends.
  - Utilized techniques like LDA, Logistic Regression, and Random Forest for skill gap analysis.

### 4. **Chatbot Implementation** 🤖

- **Purpose:** Develop a chatbot to facilitate interaction and provide information to users.

- **Methodology:**
  - Installed necessary libraries for chatbot functionality.
  - Utilized LlamaIndex and LangChain frameworks for interfacing with the OpenAI language model.
  - Constructed an index of documents for the chatbot to generate responses.

### 5. **Rating Systems** ⭐

#### a. **Job Opportunities Rating System**

- **Purpose:** Allow users to evaluate and compare different job opportunities based on objective criteria.

- **Methodology:**
  - Installed OpenAI Python module for job rating.
  - Developed a Python function, "rate_job," to generate job ratings based on user input.

#### b. **Resumes Rating System**

- **Purpose:** Evaluate and analyze resumes in relation to specific job requirements, assigning scores based on alignment.

- **Methodology:**
  - Utilized AI and NLP techniques for resume rating.
  - Developed the "rate_resume" function to generate resume ratings using the GPT-3 API.

### 6. **Job Interviews Chatbot** 🎙️

- **Purpose:** Facilitate job interviews by generating responses to common interview questions.

- **Methodology:**
  - Employed OpenAI GPT-3 API to generate responses.
  - Prompted users for their name and asked a series of common interview questions.

### 7. **Resume Generator** 📄

- **Purpose:** Generate resumes based on user input.

- **Methodology:**
  - Utilized the OpenAI API to generate resumes.
  - Constructed a prompt string with input parameters for resume generation.

## Conclusion

These models collectively contribute to the optimization of the Employability Pole platform by enhancing user experience, providing personalized recommendations, and facilitating data-driven decision-making for both job seekers and employers. Each model serves a specific purpose within the overarching goal of fostering better connections in the job market.
