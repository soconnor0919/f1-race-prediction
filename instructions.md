# CSCI 349 — Introduction to Data Mining

**Fall 2024**

---

## Final Project

**Points:** 100  
**Team-based?** YES (Preferably TWO students per team, request permission to work alone)

**Due Dates:**

- **Final Report PDF:** Tuesday, December 10
- **Video:** Friday, December 13 (URL updated on your `README.md`)

A portion of your final grade in CSCI 349 consists of the final project. This project will be a relatively large effort (compared to your work to date) to apply what you have learned in this course to the mining of a real-world, large-scale data set. The overall constraints and goals for each project will be identical, and graded using the same rubric.

---

## Deliverables

The final project deliverables will amount to:

- Python Notebook files pushed to your Git repository representing different phases of the project.
- One notebook file, `Final_Report.pdf`, submitted to Gradescope.
- A short pre-recorded video presentation.

---

## 1. Project Ideas

You are to select a challenging dataset of significance and relevance. (Common datasets in the machine learning community, such as iris, titanic, wine, MNIST, etc. are **NOT acceptable**.) Data size should be within the resources that can be handled by your computer, or you must be willing to remotely use the computers in ACET 116 or use cloud-based resources (e.g., Google Colab).

### Suggested Datasets and Sources

- **Kaggle competition**: Choose any significant dataset and compete for money, knowledge, or kudos.
- **KDD cup**: Go to [https://www.kdd.org/kdd-cup](https://www.kdd.org/kdd-cup). These are significant datasets that have been used for ACM KDD competitions.
- **UCI data repository**: [http://archive.ics.uci.edu/ml/](http://archive.ics.uci.edu/ml/) has one of the oldest repositories for machine learning research available today. It's still updated regularly.
- **Google Dataset Search**: [https://toolbox.google.com/datasetsearch](https://toolbox.google.com/datasetsearch).

---

## Example Projects

### Interpretable and Explanatory Machine Learning

A golden opportunity to shine for the interview is for you to be able to:

1. Explain why “black-box” machine learning models are bad.
2. Demonstrate a variety of techniques coming out that help explain what is being learned by machine-learned models.

This is particularly under investigation with deep learning because the complexity of the model makes it incredibly difficult to open up for interpretation. Lots of good work is being done here, and it represents an important area of research for those considering graduate studies. A resource to get you going is: [https://christophm.github.io/interpretable-ml-book/](https://christophm.github.io/interpretable-ml-book/).

---

### Social Media

Social media platforms have fundamentally transformed how we communicate, consume information, and form opinions. While these platforms have enabled unprecedented global connectivity, they've also been linked to concerning trends in mental health (particularly depression and anxiety), the spread of misinformation and outright lies to manipulate populations, political polarization, concerning drops in educational outcomes, and so much more.

As data scientists, we have both the tools and ethical responsibility to understand these effects. Classification models can help us identify patterns in social media content and user behavior that may be contributing to these issues, potentially informing better platform design and policy decisions.

Can you find datasets that are being used by the research community that could be used to investigate these problems? For instance, you would not need to search hard to find some datasets containing posts labeled as "fake news," or hate posts, or posts from bots, or fear-mongering lies and conspiracies. An interesting problem is to develop a model that can predict the sentiment of a post (Happy? Sad? Hateful? Angry? Depressing? Sarcastic? Fear-mongering?).

Can you detect inflammatory content vs. a constructive discussion in dialogue? Identify mental health risks in posting patterns?

---

### Large Language Models (LLMs)

Large Language Models (LLMs) have emerged as one of the most transformative and disruptive technologies of our time. While these models demonstrate remarkable capabilities in generating human-like text, code, and creative content, they also raise critical questions about information authenticity, bias, and the future of human-AI interaction.

As data scientists, we have some golden opportunities to protect how humans interact with AI and mitigate potential negative impacts!

- Could you develop classifiers to distinguish between human-written and AI-generated content (academia needs this!)

**NOTE:** This is a challenging area to study as it will require a commitment on the team to be willing to explore a rapidly evolving area, delve deep into natural language processing techniques, and understand how transformer models work. Do **NOT** choose this if you know you do not have the time for a good outcome!

---

### Detection of Fake Images

The rise of AI image generation has fundamentally disrupted our ability to trust visual information. Tools like DALL-E, Midjourney, and Stable Diffusion can create hyper-realistic images indistinguishable to the untrained eye.

While these technologies enable unprecedented creativity, they also present serious societal challenges—from deepfake disinformation in elections, to fake evidence in legal proceedings, to manipulated images in journalism.

The ability to reliably detect AI-generated images has become crucial for maintaining information integrity in our digital world. For example, you could just focus on a specific type of image, such as detection of fake faces in photos.

---

### Climate Change

Climate change represents one of the most complex and urgent challenges facing humanity. There is no lack of data!!! The vast amount of climate data being collected—from satellite observations, ground sensors, air columns, and ocean buoys—provides an unprecedented opportunity to apply data mining techniques for understanding and addressing this crisis.

While the general trends of global warming are clear, the intricate interactions between Earth's systems, human activity, and climate outcomes require sophisticated analysis to understand fully.

## As data scientists, we can contribute to climate solutions by uncovering patterns in climate data, improving predictions, and identifying effective interventions. Your challenge in this limited time will be dealing with time series data, which makes sense! To draw conclusions about a changing climate, you need to capture change over time.

### Voting and Polling Outcomes

Polling is a popular job in many domains, especially politics near election times. But polls are used for so many other purposes. Could you gather recent poll data and understand how to model and analyze the data in a way that would let you identify important variables that are likely to lead to the choices voters make?

---

### Public Health

Public health represents a perfect intersection of big data, societal impact, and urgent real-world challenges. From predicting disease outbreaks to understanding healthcare disparities among different populations in the U.S. or between countries, to optimizing resource allocation, data mining is a highly sought-after skillset due to the complex nature of the data required to model the problems and make improvements.

For instance, the COVID-19 pandemic demonstrated both the power and limitations of our current health surveillance systems. Meanwhile, the rise of wearable devices, electronic health records, and environmental sensors has created unprecedented opportunities to understand population health patterns. There is no lack of data! Think about any human health-related problem and see what you can find!

---

### Astronomy

There are some fantastic (and HUGE) datasets that are being made public, such as imagery being used to identify exoplanets.

---

### Other Topics

Whatever you choose, you should expect to spend time on every important step in data mining, including preprocessing, exploratory data analysis (EDA), model evaluation/validation, and knowledge extraction. You should plan on including visualizations of your data to help understand the distributions of your data, but also for reporting modeling outcomes and final results.

Where you place your focus and emphasis is up to you. For instance, you might:

- Choose one classification model and explore the techniques we've learned about for improving performance results through careful exploration of model hyperparameters and ensemble methods.
- Choose a variety of classifiers and compare and contrast their performance.
- Select a deep learning model and explore methods for visualizing distinguishing features used to make predictions.

Regardless of your approach, expect to preprocess your data to get it in a form suitable for machine learning techniques. For most real-world datasets, expect preprocessing to take a significant amount of time. Keep track of everything you do. Use your Python Notebook files to tell your story and track your progress through the project.

---

## 2. Project Steps

### 2.1 GitLab Setup

Remember, I only pull from your `main` branch! If you do not have a `main` branch, you will receive no credit for the project.

1. Be sure to create the `README.md` file summarizing the project and keep it updated throughout your project. By the end, it should include:

   - A brief summary of your project.
   - A list of the packages you used.
   - A link to where you obtained your data.

2. Manage your data in a subdirectory called `data`.

   - If your dataset is small (i.e., <1MB in size), then you can commit your entire dataset into Git.
   - If it is extremely large, you should commit only a small subset of your data or write your script to pull the data directly from the original repository.

3. Include a URL to all data you are using in your `README.md` file.

---

### 2.2 `DataPrep_EDA.ipynb`

Create your first notebook file, `DataPrep_EDA.ipynb`. Use both markdown and code cells to convey the following:

1. **Problem Summary:** What problem are you working on? Summarize in a single cell.
2. **Dataset Description:**

   - What data are you using to understand the problem?
   - Describe the data in a general sense. Where did it come from?
   - Ensure you understand what every observation in the data represents and what each variable represents.

3. **Preprocessing Steps:**

   - Remember that the key to achieving good machine learning outcomes is understanding how each real-world entity in your data will be represented as a fixed-length vector of attributes in your dataset!
   - Preprocessing your data is critical. Spend quality time cleaning and prepping your data, as this will greatly impact your results.

4. **Exploratory Data Analysis (EDA):**

   - Generate good summary statistics and visualizations such as boxplots, bar charts, or density plots for key variables.
   - Use these to convey general information about your data.

5. **Modeling Plan:**

   - Clearly explain if this is a classification, regression, clustering, or association rule mining problem.
   - Justify your choice of methods and discuss any published papers relevant to the data you are using.

6. **Project Aim and Challenges:**
   - What are you hoping to learn, or what hypothesis are you testing?
   - What challenges do you foresee?
   - Provide a reasonable list of milestones to reach by the final deadline.

---

### 2.3 `Modeling.ipynb`

Copy over the important cells from the previous step that read in and cleaned your data to this new notebook file. You do not need to copy over all your EDA and plots describing your data, only the code that prepares your data for modeling.

This notebook is about exploring the development of predictive models. Some initial preliminary work on applying modeling techniques should be completed.

1. Be sure to commit and push all supporting code that you've completed in this file.
2. Include in this notebook a summary cell at the top detailing:

   - Your accomplishments so far.
   - Challenges faced.
   - What you expect to accomplish in your final steps.

3. Update your `README.md` in your repository to reflect progress.

---

### 2.4 `Final_Report.ipynb` → `Final_Report.pdf`

This is your final report! Consider the scenario of you giving a report to a client or your supervisor on your study. Include good reporting techniques, such as tables and visualizations.

Structure your notebook using proper headers for major sections. This notebook should be a complete standalone document that includes only the best outcomes from your previous notebooks.

Include the following sections:

1. **Introduction:** Copy over relevant cells from your first notebook, adding any new information learned.
2. **Data:** Introduce the original raw data. Explain where and how it was collected, the meaning of variables, and key target variables. Show only a few rows of data for context.
3. **Data Preparation:** Explain preprocessing steps with justifications. Show cleaned data samples.
4. **EDA:** Use visualizations to convey key statistics and distributions. Discuss correlations and patterns.
5. **Modeling:**
   - What modeling methods were tried?
   - Which methods were determined to be the best?
   - How were hyperparameters selected?
6. **Performance Results:** Provide metrics like ROC curves, confusion matrices, and precision/recall tables.
7. **Discussion:** Reflect on challenges, surprises, and lessons learned. Discuss feature importance.
8. **Conclusions:** Summarize the project and its outcomes.

Generate the final report as a PDF and submit it to Gradescope.

---

### 2.5 Video Presentation

You must record a final presentation video summarizing your project, generally following the structure of your final report.

- Record the video using any tools you prefer (Zoom works well).
- Upload the video to a platform (e.g., Mediaspace) and provide the URL in your `README.md`.
- Ensure your `README.md` is updated and pushed to your GitLab repository.

---

## Final Notes

There is no final exam. Use the time you would spend studying for the final to refine your report and video.
