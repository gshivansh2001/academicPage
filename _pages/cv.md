---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Download [Academic CV (last updated May'25)](/files/Shivansh_Professional_Resume_2025.pdf) or [Professional CV (last updated May'25)](/files/Shivansh_Professional_Resume_2025.pdf)

<script>
    function pressBtn(p) {

      var id_btn=["exp-btn", "pub-btn"], class_btn=["fas fa-plus-square", "fas fa-minus-square"];
      var id_div=["exp-div", "pub-div"], style_div=["height: 300px; overflow: auto;", "height: 400px; overflow: auto;"];

      var btn = document.getElementById(id_btn[p]);
      if(btn.className == class_btn[0]) {
        btn.className = class_btn[1];
        document.getElementById(id_div[p]).style = "";
      }
      else {
        btn.className = class_btn[0];
        document.getElementById(id_div[p]).style = style_div[p];
      }
    }

    function img_hover(e, f) {
      e.setAttribute("src", f);
    }
    function img_unhover(e, f) {
      e.setAttribute("src", f);
    }
</script>



Education
======   
* B.Tech in Petroleum Engineering, Indian Institute of Technology (Indian School of Mines), Dhanbad, India, 2019 - 2023
  + <span style="font-size: 0.75em">GPA: 7.83/10, (MCM Scholarship Recipient)</span>
  + <span style="font-size: 0.75em">Related courses: Engineering Economics & Finance, Object Oriented Programming, Data mining, Financial Econometrics, Operations Research, Development Economics, Fundamentals of Machine Learning, Data Analytics, International Macroeconomics and Monetary Policy, Reservoir Modelling and Simulation</span>

<!-- adding td
td {
  padding: 0px 20px 0px 20px;
  vertical-align: middle;
}
td.all {
  width: 100%;
}
td.exp-avatar {
  width: 15%;
}
td.exp-description {
  width: 80%;
}
td.pub-avatar {
  width: 30%;
}
td.pub-description {
  width: 65%;
}--> 


Work experience
======
<!--- <div style="height: 600px; overflow: auto;" id="exp-div"> --->
<div style="overflow: auto;" id="exp-div">  
  <table>
    <thead>
      <tr>
        <th style="padding: 10px 20px; text-align: left; width: 15%;">Organisation</th>
        <th style="padding: 10px 20px; text-align: left; width: 25%;">Title</th>
        <th style="padding: 10px 20px; text-align: left; width: 55%;">Experience</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="padding: 0px 20px; vertical-align: middle; width: 15%; text-align: center;">
          <img src="https://gshivansh2001.github.io/academicPage/images/ISB_Logo.png" alt="ISB Logo" width="80" /><br>
          <a href="https://www.isb.edu" target="_blank">Indian School of Business</a><br>
        </td>
        <td style="padding: 0px 20px; vertical-align: middle; width: 25%;">
          <b>Research Associate</b><br>
          <br><b>Department:</b> Information Systems<br>
          <br><b>Advisor:</b> <a href="https://www.isb.edu/faculty-and-research/faculty-directory/vasundhara-sharma">Dr. Vasundhara Sharma</a>
        </td>
        <td style="padding: 0px 20px; vertical-align: middle; width: 55%;">
          <span style="float: right;">Dec'24 - Ongoing</span>
          <ul style="margin: 8px 0; padding-left: 20px;">
            <li>Research Focus: Passionate about applying machine learning (ML) and data science to macroeconomic measures and public policy, aiming to evaluate and enhance their impact on society</li>
            <li>Conducting a research project on the impact of social movements in the digital world and another project simulating a virtual environment to curb the spread of misinformation in social networks, while supporting professors in academic research and data-driven analyses.</li>
            <li>Currently working with web scraping tools like Selenium, applying natural language processing (NLP) techniques, and leveraging large language models (LLMs) for text data analysis and generating actionable insights.</li>
            <li>Methodologies: Econometric Analysis, Structural Modeling & Survery</li>
          </ul>
        </td>
      </tr>
      <br>
      <tr>
        <td style="padding: 0px 20px; vertical-align: middle; width: 15%; text-align: center;">
          <img src="https://gshivansh2001.github.io/academicPage/images/HCLTech_logo.png" alt="HCLTech & Chevron Logo" width="80" /><br>
          <a href="https://www.hcltech.com/" target="_blank">HCLTech</a><br><b>Client:</b> Chevron<br>
        </td>
        <td style="padding: 0px 20px; vertical-align: middle; width: 25%;">
          <b>Data Scientist</b><br>
          <br><b>Team:</b> Oil & Gas Consulting<br>
          <br><b>Manager:</b> <a href="https://www.linkedin.com/in/jaspreet-singh-86bb2319/">Jaspreet Singh</a>
          <br><b>Product Owner:</b> <a href="https://www.linkedin.com/in/lshapirosf/">Leonid Shapiro</a>
        </td>
        <td style="padding: 0px 20px; vertical-align: middle; width: 55%;">
          <span style="float: right;">Jul'23 - Nov'24</span>
          <ul style="margin: 8px 0; padding-left: 20px;">
            <li>Working with the AIOps team to develop a supervised machine learning model which analyses Azure Virtual Desktop log data to predict issues to automate and streamline L1 support.</li>
            <li>Developed a Generative AI application for analysing O&G daily drilling reports (DDRs) to convert them into OSDU-compliant JSON data for direct ingestion in the OSDU environment. Used Azure ML Studio with OpenAI GPT-3.5 Turbo API and LangChain in Python for developing the application and Gradio for developing the interface.</li>
            <li>Created and managed data pipelines and dashboards for asset management across 800 O&G wells using Azure Databricks, Power BI and internal asset management tools. </li>
            <li>Developed an application for registering new and reimaged remote desktop data, creating an SQL database for asset management with Azure Function and Power Apps in Python.</li>
            <li>Contributed to OSDU production and logging practices with DataVedik.</li>
          </ul>
        </td>
      </tr>
      <br>
      <tr>
        <td style="padding: 0px 20px; vertical-align: middle; width: 15%; text-align: center;">
          <img src="https://gshivansh2001.github.io/academicPage/images/HCLTech-thumbnail.png" alt="HCLTech Logo" width="80" /><br>
          <a href="https://www.hcltech.com/" target="_blank">HCLTech</a><br>
        </td>
        <td style="padding: 0px 20px; vertical-align: middle; width: 25%;">
          <b>Machine Learning Intern</b><br>
          <br><b>Team:</b> Oil & Gas Consulting<br>
          <br><b>Manager:</b> <a href="https://www.linkedin.com/in/deepak-bhardwaj-08a0278/">Deepak Bhardwaj</a>
        </td>
        <td style="padding: 0px 20px; vertical-align: middle; width: 55%;">
          <span style="float: right;">May'22 - Aug'22</span>
          <ul style="margin: 8px 0; padding-left: 20px;">
            <li>Developed adaptive ML-based alarm system using Random Forest in Python for early detection of kicks and blowouts in O&G wells, using Equinor’s Volve dataset.</li>
            <li>Addressed imbalance in the dataset with SMOTE. Trained supervised ML models using Sklearn & TensorFlow for optimal prediction results.</li>
            <li>Conducted extensive data preprocessing & EDA using seaborn & pandas. Implemented a method to label kicks in the dataset using DDRs & lithological parameters.</li>
            <li>A patent was filed (in progress) for the data labelling mechanism used in the model. Received pre-placement offer upon completion</li>
          </ul>
        </td>
      </tr>
      <br>
      <tr>
        <td style="padding: 0px 20px; vertical-align: middle; width: 15%; text-align: center;">
          <img src="https://gshivansh2001.github.io/academicPage/images/dgms_logo.png" alt="DGMS Logo" width="80" /><br>
          <a href="https://www.hcltech.com/" target="_blank">Directorate General of Mine Safety (DGMS)</a><br>
        </td>
        <td style="padding: 0px 20px; vertical-align: middle; width: 25%;">
          <b>Project Intern</b><br>
          <br><b>Team:</b> <a href="https://sites.google.com/view/dail-lab/home?authuser=0" target="_blank">Mine Digitalization and Artificial Intelligence Lab</a><br> <br>
          <br><b>Advisor:</b> <a href="https://www.linkedin.com/in/siddharth-agarwal-86179613/">Prof. Siddharth Agarwal</a>
        </td>
        <td style="padding: 0px 20px; vertical-align: middle; width: 55%;">
          <span style="float: right;">Aug'22 - Feb'23</span>
          <ul style="margin: 8px 0; padding-left: 20px;">
            <li>Conducted an independent research project analysing the root causes of fatalities in Indian coal and non-coal mines using historical DGMS fatality reports.</li>
            <li>Developed a customised text mining pipeline using Python's re and nltk libraries to extract structured data from unstructured PDF reports spanning multiple years.</li>
            <li>Designed and implemented a relational MySQL database to systematically organise fatality records by mine type, location, cause, and year, facilitating longitudinal analysis.</li>
            <li>Utilized pandas, matplotlib, and plotly to generate analytical visualisations revealing temporal patterns and critical risk factors contributing to mine accidents.</li>
            <li>The project provided actionable insights into systemic safety failures and informed recommendations for targeted regulatory interventions.</li>
          </ul>
        </td>
      </tr>
      <br>
      <tr>
        <td style="padding: 0px 20px; vertical-align: middle; width: 15%; text-align: center;">
          <img src="https://gshivansh2001.github.io/academicPage/images/IIMU_Logo.png" alt="IIM Udaipur Logo" width="80" /><br>
          <a href="https://www.hcltech.com/" target="_blank">Indian Institute of Management (IIM) Udaipur</a><br>
        </td>
        <td style="padding: 0px 20px; vertical-align: middle; width: 25%;">
          <b>Research Intern</b><br>
          <br><b>Advisor:</b> <a href="https://www.ashishgalande.com/home">Prof. Ashish Galande</a>
        </td>
        <td style="padding: 0px 20px; vertical-align: middle; width: 55%;">
          <span style="float: right;">Aug'22 - Feb'23</span>
          <ul style="margin: 8px 0; padding-left: 20px;">
            <li>Created a structured dataset of Fortune 500 companies’ tweets through web scraping using Twint and Scrapy in Python to analyse CSR activities and study principles of conscious capitalism.</li>
            <li> Utilised text analysis and NLP techniques to compute lexical diversity and sentiment scores using NLTK and VADER libraries.</li>
            <li>Preprocessed and vectorised text, and leveraged sentiment scores to develop a sentiment analysis model using RNN in TensorFlow.</li>
          </ul>
        </td>
      </tr>
  </tbody></table>
</div>

  
Skills
======
* **Programming languages**:  Python, C#, R, Cuda
* **Programming Tools and Libraries**:
  * **Reinforcement Learning and Deep Learning**: Transformers(Huggingface), Stable-Baselines3, ClearnRL, Pytorch, Tensorboard, Pettingzoo, Gymnasium(OpenAI Gym) 
  * **Machine learning and Data Science toolkit**:  NLTK, Scikit-learn, SciPy, NumPy, Pandas, Sparks, Pyarrow, fastparquet
  * **Visualization Toolkit**: Matplotlib, Seaborn, Plotly, Dash(Plotly), Tableau
  * **App design**: Dash(Plotly), Flask
  * Misc : Selenium
* **Solution Design Experience**: Credit Risk Modeling, Social listening analysis, Fraud detection(fuzzy logic), Sales Forecasting, Market Mix Modeling, Demand forecasting, Attribution Modeling, Analytics Pipeline Design.
* **Research Experience**: Literature review, Research Study and Experiment Design, Statistical Analysis, Meta-Analysis, IRB transcript and Project report writing.
* **Management**: Project and Task planning, Call and Client management, Team management.

Projects and Publications
======

Please refer [Projects and Publications](/publications/) page.

<!--- <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> 
--->

  
Social Responsibility
======
* NGO Volunteer - Environmental Synergies in Development (ENSYDE): Promoted e-waste awareness through booths at various conventions. (2017-present)
* NGO Volunteer - Youth for Seva (YFS): Volunteered with YFS teaching children at government schools. (2018-present)
* NGO Volunteer -  Youth For Parivarthan: Led community-driven initiatives to clean & revitalize public areas (2018-2022)

Academic Volunteering and Coordination
======
* WITS conference volunteer (ISB): Event coordination and assistance. [Tracks: 1. ML/AI, 2. DEI, 3. Recommender systems] (2023)
* WISE conference volunteer (ISB): Track coordinator [ 1. Platforms and Misinformation, 2. AI and governance] (2023)
* Nvidia Lab Coordinator (AIT): Coordinated Nvidia CUDA programming workshops for students along, and Collaborated with Industry professionals  (2015)

Military Experience
======
<div style=" overflow: auto;" id="exp-div">  
  <table><tbody>
    <tr>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 15%;">
      <img src="/images/NDA.jpeg" />
      </td>
      <td style="padding: 0px 20px 0px 20px;vertical-align: middle;width: 80%;">
      <span style="float: right;">Jul. 2013 - Jul 2014</span>
      <br>
     Academics and Military Training at the prestigious National Defence Academy (India)
      </td>
    </tr>
  </tbody>
  </table>
</div>


Honors, prizes, awards, and fellowships:
======
* Project selected for CreateX startup lab, Georgia Institute of Technology (2022)
* Star of the Quarter, Quantzig, Awarded by HOD for exceptional project delivery (2020)
* Super Star Award, Quantzig, Awarded by VP for exceptional yearly contribution (2020)
* Spot Award, Deloitte USI, Awarded by HOD (2019)
* Recommended for Officers Training Academy (Indian Army - Engg.) All-India-Rank: 13 (2018)
* AGIF Scholarship (Award for academic excellence), Army Institute of Technology, (2015)
* Recommended for National Defence Academy(Indian Army) All-India-Rank: 107 (of ~ 400,000 applicants) (2013)

Teaching:
======
* Designed a course and taught Machine Learning, Data Science, and Python programming to new joinees at MoneyView (2021-2023)
* Mentored second and third-year Bachelor of Engineering students on the practical implementation of industry-relevant projects (2014-2016)

Selected Certifications:
======
* Probability - The Science of Uncertainty and Data (2020) – MITx on Edx
* Fundamentals of Statistics (2020) – MITx on Edx
* Data Analysis in Social Science(2020) – MITx on Edx
* Machine Learning with Python-From Linear Models to Deep Learning (2020) – MITx on Edx (MIT 18.650)


