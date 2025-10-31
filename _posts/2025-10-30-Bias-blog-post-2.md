---
title: 'Bias and Fairness blog 2: Understanding Potential Sources of Harm throughout the Machine Learning Life Cycle'
date: 2025-10-30
permalink: /posts/2025/10/Bias and Fairness-blog-post-2/
tags:
  - Bias
  - Harm reduction
  - Machine Learning 
---
**Article:**  
[Understanding Potential Sources of Harm throughout the Machine Learning Life Cycle](https://mit-serc.pubpub.org/pub/potential-sources-of-harm-throughout-the-machine-learning-life-cycle/release/2)

Brief Summary:
This article breaks down the harm in Machone learning models theough different scenarios. It also proved historical biases that have been imminent in AI. 

Draft a checklist that people starting new projects could use to try to anticipate or prevent different types of bias.
 A checklist that people could use could fall into different sections:

Data collection:
 
 Who benefits from this system and who may be harmed?
 
 Are there diverse stakeholders so that marginalized groups are included in data collection?
 
 Data preparation:
 
 Who is coming up with the data preparation steps, what's their demographic?
 
 Are there fair guidelines for preparation that includes all demographics and are they reviewed before they're put out.

Model Development:
 
 Are features inclusive or are they tailored toward a certain group of people(white men)?
 Are multiple models tested for overfit/biased data and if so are those models discouraged?

Model evaluation:

 Are the data sets balanced and realistic?
 
 Do the models catch false positives/negatives and are the results of accuracy, precision, and recall accurate?

Model postprocessing:
 
 Is the data representation understandable to the audience?

 Do the thresholds align with the desired output of the data(categorical answer)?

Model deployment:
 
 Who is the one outputting the data? Are they inclusive of all groups? Is their recall if the finished data set has bias?
 
 Are there feedback implementations that flag bias right away?

Can you come up with additional ways to detect and/or mitigate each source of harm?

Data collection:
 
 Collect data from diverse groups and inclusive populations that reflect the targeted users.

 Allow community input for data collection.

Data Preparation:
 Allow experts to review data, especially for specific data/sensitive features
 
 Create a training program for data analysts so they know what to look for and how to act on biases.

Model development:
 
 Remove variables that exclude marginalized groups.
 
 Review all features for discrimination risks.

Model Evaluation:
 
 Include human evaluation methods rather than ML evaluation only.
 
 Include specific metrics like fairness and harm reduction.

Model postprocessing:
 
 Document when outputs are modified so that decisions remain interpretable.
 
 Test outputs across multiple demographics to ensure fairness holds.

Model Deployment:
 
 Ensure whoever is outputting data exemplifies fairness and inclusivity.
 
 Update and continuously monitor data outputs if populations increase or decrease.
 
Can you think of other sources of harm that aren’t captured in this case study?

We recently talked about environmental concerns. The article doesn't mention the excessive use of water that keeps machines running. Additionally, hardware is melted and destroyed which then exposes the environment to the burning fossil fuels leading to climate change and issues. Usually these procedures are done in underdeveloped communities that already face environmental inequality.

Who shoukld be held reliable when there is harm in AI systems? Model developers, Analysts, Managers, outputters? Is the accountability directed towards one group or spread throughout each branch?

I chose this question so that readers can identify who they think is responsible for bias and exclusive data. I think this question gives readers the chance to hold the people in charge accountable and possibly research why outputted data is biased. Are these higher ups a specific gender, race, or in a higher economic class than the normal person or specific groups.

Reflection:

This case study allowed me to learn more about harm reduction through the discussion questions and ways to mitigate biased ML data sets. Additionally I was able to think of new ways to reduce harm in ML and apply those methods to the case study. Reading through the case study provided a layout of how I could conduct my case study for our project in class and ways that I could go about presenting it. 