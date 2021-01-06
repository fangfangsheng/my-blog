---
layout: page
title: Projects
# permalink: /about/
---

<ins>Novartis EEG lab</ins>   **Automatic high throughput genotype classification pipeline with feature selection based on Rodents EEG Signals**

<img src="assets/medias/eeg-streamlit.gif" width="400" height="250" />

EEG(Electroencephalogram) analysis has been an important and widely use tool in neuroscience with applications. It can determine changes in brain activity that server as one useful decision-making tool in diagnosing brain disorders and monitoring the drug effect. Some efforts are already being done on using human clinical EEG data to differentiate groups. However, EEG signals in combination with machine learning (ML) approaches were not commonly used for the Rodent genotype prediction.

Current approach in EEG lab is using pre-defined frequency bins, determine which are contributing most to group differences by manually looking at Prism plots.
We needed approach can identify new phenotypes without pre-defined bins. Look across whole EEG spectral domain to identify more robust meta-phenotypes to enhance EEGs effectiveness as a translatable biomarker.

To accomplish this, I developed an end to end machine learning pipeline to increase the efficiency of hypothesis testing and validation during my CoOp at Novartis.



<div>
    <a target="_blank" href="assets/slides/EEG2020.pdf">Poster</a> 
</div>


<br>


<ins>MITHack-Medicine 2020</ins>   **COVIData Registry**

<img src="assets/medias/COVIData.gif" width="400" height="250" />

As the impact of COVID-19 on hospital systems and health care workforces continues, how can we best help hospitals quickly shift human resources, redeploy healthcare workers appropriately based on skills sets, and quickly train current/new healthcare workers to fill certain needs of the health system while protecting the physical and mental well-being of our healthcare workforce?

Within 72 hours, we proposed and finished the system Design of a *curated COVID-19 registry database* of patient-level data from US hospitals that can be accessed by researchers to answer
questions about the best treatment options for patients with specific characteristics (e.g., age, sex, pre-existing conditions).


<div>
    <a target="_blank" href="assets/slides/COVIData.pdf">Slides</a> |
    <a target="_blank" href="https://fangfangsheng.github.io/COVIData/"> Website </a> |  
    <a target="_blank" href="https://github.com/fangfangsheng/COVIData"> Github
    </a>  
</div>

<br>


<ins>Full Stack Machine Learning</ins>   **Streaming Twitter Filter in Python**

Build and deploy a streaming pipeline that downloads tweets, filters based on provided *keywords* and caculates sentiment scores at cloud. 


<img src="assets/images/streaming-tweets.png" width="600" height="350" />


* use Tweepy to interact with Twitter's API
* use Redis to setup a key-value store at cloud
* conduct state-of-the-art sentiment analysis
* display data from Redis via Flask and Jinga2(web application) at Heroku


<div>
    <!-- <a target="_blank" href="">Slides</a> | -->
    <a target="_blank" href="https://tweets-redis-flask.herokuapp.com/"> Website </a> |  
    <a target="_blank" href="https://github.com/fangfangsheng/Streaming_Sentiment"> Github</a>  
</div>

<br>


<ins>Full Stack Deep Learning</ins>   **Text recognizer App in Python**

The goal for this project is trainning machine learning models and deploying a text recognizer AI systems in the real world at free cloud platform. More specifically, I'm going to build a web page allow user upload a picture of their handwriting and the AI models will try it best to recognize it and return text.

<!-- <img src="assets/medias/eeg-streamlit.png" width="400" height="250" /> -->


<div>
    <a target="_blank" href=""> Website </a> |  
    <a target="_blank" href=""> Github</a>  
</div>

<br>


<ins>Full Stack MERN Project</ins>   **Learning Tracking App in MongoDB, Node.js, Express, React, Redux**

Milestone porject for 'The Complete 2020 Web Development Bootcamp' at Udemy where I learnt how to build a Full Stack MERN Project - from start to finish. <br>
The App is called "Learner Booth" and it is a simple MERN application that allows users to keep track of their learning process and review what they've learned regularly.
Utilized MongoDB backend database for data persistence, deployed with Heroku(API) and netlify(Front End). 

<img src="assets/images/LearnerBooth.png" width="400" height="250" />

<div>
    <a target="_blank" href="https://leanerbooth.netlify.app/"> Website </a> |  
    <a target="_blank" href=""> Github</a>
</div>

<br>


