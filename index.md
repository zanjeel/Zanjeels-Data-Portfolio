---
layout: default
---

<style>
/* Base styles for consistent sizing */
html, body {
    max-width: 100vw;
    overflow-x: hidden !important;
    position: relative;
    margin: 0;
    padding: 0;
}

body {
    padding: 80px 30px 0;
    font-size: 1rem;
    line-height: 1.6;
}

* {
    max-width: 100vw;
    box-sizing: border-box;
}

.wrapper {
    width: 100%;
    max-width: 100vw;
    overflow-x: hidden !important;
    margin: 0 auto;
    padding: 0 15px;
}

/* Project image sizing */
.project-image, .project-image2 {
    width: 100%;
    max-width: 500px;
    height: auto;
    margin: 20px auto;
    display: block;
    object-fit: cover;
}

/* Table styles */
table {
    width: 100%;
    max-width: 100%;
    display: block;
    overflow-x: auto;
    white-space: nowrap;
    -webkit-overflow-scrolling: touch;
    margin: 0 auto;
}

/* Media Queries */
@media screen and (max-width: 1024px) {
    html, body {
        overflow-x: hidden !important;
        max-width: 100vw;
    }
    
    .project-image, .project-image2 {
        max-width: 450px;
    }
}

@media screen and (max-width: 768px) {
    .project-image, .project-image2 {
        max-width: 400px;
    }
}

@media screen and (max-width: 480px) {
    html {
        font-size: 11px;
        -webkit-text-size-adjust: none;
        text-size-adjust: none;
    }
    
    .project-image, .project-image2 {
        max-width: 350px;
    }
    
    .wrapper {
        padding: 0 10px;
    }
}

/* Content sizing */
.wrapper {
    max-width: 1400px;
    margin: 0 auto;
    padding: 0 30px;
    overflow-x: hidden;  /* Prevent wrapper overflow */
}

section {
    font-size: 1.1rem;
    line-height: 1.6;
    max-width: 100%;  /* Ensure sections don't overflow */
}

h1 {
    font-size: 3em;
    margin-bottom: 0.7em;
}

h2 {
    font-size: 2.5em;
    margin-bottom: 0.7em;
}

h3 {
    font-size: 2em;
    margin-bottom: 0.7em;
}

p, li {
    font-size: 1.1rem;
    margin-bottom: 1em;
}

/* GitHub Profile Link Style */
.view a {
    display: inline-block;
    padding: 10px 20px;
    background-color: #2ea44f;
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-weight: 600;
    transition: background-color 0.3s ease;
}

.view a:hover {
    background-color: #2c974b;
}

/* Project Button Style */
.project-button {
    display: inline-block;
    padding: 8px 16px;
    background-color: #0366d6;
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-weight: 500;
    margin-top: 10px;
    margin-right: 10px;
    transition: background-color 0.3s ease;
}

.project-button:hover {
    background-color: #0245a3;
}

/* GitHub Button Style */
.github-button {
    display: inline-block;
    padding: 8px 16px;
    background-color: #24292e;
    color: white;
    text-decoration: none;
    border-radius: 6px;
    font-weight: 500;
    margin-top: 10px;
    transition: background-color 0.3s ease;
}

.github-button:hover {
    background-color: #2f363d;
}

/* Education container styles */
.education-container {
    margin: 20px 0;
}

.education-item {
    background-color: #f8f9fa;
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 15px;
    box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    transition: transform 0.2s ease;
}

.education-item:hover {
    transform: translateY(-2px);
}

.education-item h3 {
    color: #0366d6;
    margin: 0 0 10px 0;
    font-size: 1.2em;
}

.education-details {
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: #586069;
}

.education-details .institution {
    font-weight: 500;
    margin: 0;
}

.education-details .year {
    margin: 0;
    font-style: italic;
}

/* Desktop Styles */
@media screen and (min-width: 1250px) {
  body {
    overflow-x: hidden;
    zoom: 1.1;
    -moz-transform: scale(1.1);
    -moz-transform-origin: 0 0;
  }
  
  .container {
    max-width: 1200px;
    padding: 0 2rem;
  }
  
  h1 {
    font-size: 2.5rem;
  }
  
  h2 {
    font-size: 2rem;
  }
  
  h3 {
    font-size: 1.5rem;
  }
  
  p {
    font-size: 1rem;
  }
  
  .project-image {
    max-width: 90%;
    height: auto;
  }
  
  .skills-grid {
    grid-template-columns: repeat(4, 1fr);
    gap: 1.5rem;
  }
  
  .skill-item {
    padding: 1.2rem;
    font-size: 1.1rem;
  }
  
  .education-item {
    padding: 1.5rem;
  }
  
  .education-item h3 {
    font-size: 1.6rem;
  }
  
  .education-item p {
    font-size: 1.1rem;
  }
}

/* Medium-large screens */
@media screen and (min-width: 1024px) and (max-width: 1249px) {
  body {
    overflow-x: hidden;
    zoom: 0.9;
    -moz-transform: scale(0.9);
    -moz-transform-origin: 0 0;
  }
  
  .container {
    max-width: 1100px;
    padding: 0 2rem;
  }
  
  h1 {
    font-size: 2.3rem;
  }
  
  h2 {
    font-size: 1.8rem;
  }
  
  h3 {
    font-size: 1.4rem;
  }
  
  p {
    font-size: 1rem;
  }
  
  .project-image {
    max-width: 85%;
    height: auto;
  }
}

/* Add to the style section */
.project-separator {
    border: 0;
    height: 1px;
    background-color: #e1e4e8;
    margin: 30px 0;
    width: 100%;
}

/* Add to the style section */
table th {
    text-align: center;
}
</style>

# Data Scientist & Analyst

📍 London, United Kingdom

Hey, I'm Zanjeel. I'm a data lover and I thrive on using data for building the most innovative and latest, modern technologies. 
Here you'll find a collection of my projects in data analysis, machine learning, and artificial intelligence.

## Education

* **MSc., Data Science & Analytics** - Brunel University London *(Dec 2024)*
* **BSc., Computer Science** - FAST University *(Sep 2023)*

## Skills

* **Programming Languages**: Python, R, SQL, JavaScript, CSS, HTML
* **Data Analysis**: Pandas, PySpark, NumPy, Matplotlib, Sikit 
* **Machine Learning**: Scikit-learn, TensorFlow, Deep Learning
* **Data Visualization**: Tableau, Power BI, Matplotlib
* **AI/ML**: RAG, LLMs, Speech Recognition, APIs
* **Tools**: Git, GitHub, Google Cloud Platform

---

## Featured Projects

### 1. Voice-to-Voice LLM Assistant
<img src="./assets/img/Voice-LLM.jpeg" class="project-image" alt="Voice Assistant">
* **Description**: A conversational AI assistant that uses speech-to-text and text-to-speech capabilities, powered by Google's Gemini AI. Features real-time voice recording, processing, and witty responses in real time.

* **Skills**: Python, Flask, React, Google Gemini AI, Speech Recognition, gTTS (Google Text to Speech)

* **Key Features**: Real-time voice processing, natural dialogue, witty responses

[View Live Project](https://voice-to-voice-llm.vercel.app){: .project-button} [View on GitHub](https://github.com/zanjeel/Voice-to-Voice-LLM){: .github-button}

<hr class="project-separator">




### 2. Automobile Predictive Analysis
<img src="./assets/img/Data-Analysis-Using-Machine-Learning.jpeg" class="project-image" alt="Automobile Analysis">
* **Description**: Predictive analysis of automobile data using RStudio, focusing on price prediction and market trends.

* **Skills**: R, Predictive Modeling, Data Visualization

* **Key Features**: Real-time voice processing, natural dialogue, witty responses

[View Live Project](https://zanjeel.github.io/Automobile-Predictive-Data-Analysis-RStudio/Automobile-Price-Prediction.nb.html){: .project-button} [View on GitHub](https://github.com/zanjeel/Automobile-Predictive-Data-Analysis-RStudio){: .github-button}

<hr class="project-separator">




### 3. Weather Prediction for Hillingdon Council
<img src="./assets/img/Predictive-ML-Hillingdon-Council-UK.jpeg" class="project-image" alt="Weather Prediction">
* **Description**: Machine learning-based weather prediction system developed for Hillingdon Council, UK, using various ML algorithms.

* **Skills**: Python, Machine Learning, Time Series Analysis

* **Key Features**: Multiple ML models comparison, accurate weather forecasting, interactive visualizations

[View Live Project](https://zanjeel.github.io/Weather-Prediction-MachineLearningAlgorithms-HillingdonCouncilUK/MachineLearningModelsforWeatherPrediction.html){: .project-button} [View on GitHub](https://github.com/zanjeel/Weather-Prediction-MachineLearningAlgorithms-HillingdonCouncilUK){: .github-button}

<hr class="project-separator">




### 4. RAG-NasaAI SpaceLovers
<img src="./assets/img/NasaAI-proj-img.jpeg" class="project-image" alt="NASA AI">
* **Description**: A Retrieval-Augmented Generation (RAG) system for space-related queries, integrating NASA's data with AI capabilities.

* **Skills**: Python, RAG, AI/ML, API Integration

* **Key Features**: Real-time space data retrieval, accurate space information, interactive Q&A interface

[View on GitHub](https://github.com/zanjeel/RAG-NasaAI-SpaceLovers){: .github-button}

<hr class="project-separator">




### 5. DataAnalyserPro
<img src="./assets/img/Data-Analytics-Pro.jpeg" class="project-image" alt="Data Analysis">
* **Description**: A web-based data analysis tool that provides instant insights from Excel files without storing any data. Features rich visualizations and comprehensive statistics.

* **Skills**: Excel, React, TypeScript, Tailwind CSS

* **Key Features**: Privacy-first processing, rich visualizations, responsive design

[View Live Project](https://data-analyser-pro.netlify.app){: .project-button} [View on GitHub](https://github.com/zanjeel/DataAnalyserPro){: .github-button}

<hr class="project-separator">




### 6. Tableau Dashboards
<img src="./assets/img/Customers-Data-Insights-Dashboard.jpeg" class="project-image" alt="Customer Insights Data Analysis">
#### Customer Insight Analysis
* **Description**: Interactive dashboard analyzing customer behavior and insights with interactive filters to visualise data by sales, gender and more.

* **Skills**: Tableau, Data Visualization, Business Analytics

* **Key Features**: Interactive filters, customer segmentation, trend analysis

[View Dashboard](https://public.tableau.com/app/profile/zanjeel.tariq.sahi/viz/CustomerInsightDataAnalysis/Dashboard){: .project-button}

<hr class="project-separator">



#### Adidas Sales Analysis
<img src="./assets/img/tableau2.jpeg" class="project-image2" alt="Adidas Insights Data Analysis">
* **Description**: Data analysis and visualisation of Adidas sales in the US with interactive filters like Profit margin, product and year.

* **Skills**: Tableau, Sales Analytics, Interactive Visualization

* **Key Features**: Sales performance metrics, regional analysis, product category insights

[View Dashboard](https://public.tableau.com/app/profile/zanjeel.tariq.sahi/viz/AdidasSalesAnalaysisUSwithInteractiveFiltersforDeeperInsights/Dashboard){: .project-button}

<hr class="project-separator">


---

## Work Experience

* **Chair @ Data Science at Brunel London (Feb 2024 - Dec 2024)**  
  * Data Science Society at Brunel is a Leading Tech organisation increasing tech literacy amongst students.
  * Here I led weekly Programming sessions for 50+ students in a range of programming languages including C++, Python, R, SQL and more.


* **Developer Intern @ Risidio, London (Jan 2024 - Jun 2024)**  
  * Risido is a tech startup in London with a global client base.
  * Developed scalable software and web solutions, working with huge datasets to bring their own flagship 3D metaverse to life.
  * Built PowerPoint presentations to communicate findings to the CEO and 5+ dept., in non-technical, clear terms.


* **Software Engineer Intern @ Devsinc (Jul 2021 - Oct 2021)**  
  * Designed an ETL pipeline to process ~10GB+ datasets from multiple sources (.txt, Excel .CSV). This reduced manual search time by 70%.
  * Developed a data retrieval took using Ruby that searched for the data input by the user from a 20+ years of past records and returned the needed data. it also visualised the past data over a user entered time period.


---

## Transferable Experience

* **Founder and Chair | Brunel Data Science**  
  Mentored 300+ students, led 5+ hackathons  

* **Tech Speaker | Innovia UK Women in STEM**  
  Keynote Guest Speaker  

* **Theatrical Actor | NUCES University**  
  Selected from 500+ unis to perform for 1st lady of Pakistan  

* **VP Dramatics | NUCES University**  
  Led 5+ theatrical performances for 5,000+ attendees  

---

## Contact

* **GitHub**: [https://github.com/zanjeel](https://github.com/zanjeel)
* **LinkedIn**: [zanjeel-tariq-sahi](https://www.linkedin.com/in/zanjeel-tariq-sahi){:rel="noopener noreferrer"}
* **Email**: zanjeel123@gmail.com

---

_This portfolio is constantly updated with new projects and analyses. Check back regularly for updates!_
