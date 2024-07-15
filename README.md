# Data Scientist
Someone who is deeply interested in Data Analytics, Machine Learning, and Generative AI. Always curious about the world, open to learn, detail-oriented, self-motivated, and determined. Has a unique interdisciplinary approach that integrates principles from both Industrial and Computer Engineering.

### Technical Skills: Python, Django, AWS, Microsoft Azure, Java, C, R, MongoDB, PostgreSQL, PL/SQL, Node.js, HTML, CSS, Android Studio, Microsoft Office Programs

## Education
- BSc, Computer Engineering | Yildiz Technical University (_August 2018 - June 2023_)
- BSc, Industrial Engineering | Yildiz Technical University (_August 2017 - June 2023_)

## Work Experience
**Jr. Data Scientist/Technology Consultant @ PwC (_February 2023 - Present_)**
- Created internal automation tools using Python and SQL,
- Designed cloud architectures using AWS services (Lambda, Elastic Beanstalk, RDS, etc.)
- Designed and implemented Generative AI solutions using LLM models (Llama, GPT) on Microsoft Azure and AWS.
- Created ETL and AI pipelines

**Undergraduate Research Fellow @ Yıldız Technical University (_October 2021 - October 2023_)**

I had the privilege of working as an undergraduate research fellow in a project funded by TUBİTAK (The Scientific and Technological Research Institution of Turkey) as part of the TUBİTAK 1001 program. This project, guided by Assoc. Prof. Dr. Mehmet Amaç Güvensan and Asst. Prof. Dr. İrem Türkmen, focused on analyzing the weights of various factors influencing Istanbul's traffic dynamics and implementing a predictive traffic flow model for durations between 2 and 48 hours across different city zones.
During this project, I accomplished the following tasks:
- Conducted error and data analysis targeting accident detection with delays ranging from 5 to 15 minutes. 
- Estimated long-term traffic speeds during holidays in Istanbul.
- Engaged extensively with deep learning architectures, including Convolutional Neural Networks (CNN), Long Short-Term Memory networks (LSTM), and Multi-Layer Perceptrons (MLP).
- Explored additional machine learning models such as Support Vector Regression (SVR) and Isolation Forest.
- Applied numerous data engineering techniques, including similarity-based approaches, k-Nearest Neighbors (k-NN), and time framing, to manage and analyze temporal factors in time-series traffic speed data.
- Published a [workshop paper](https://ieeexplore.ieee.org/document/10422052) and a [journal paper](https://ieeexplore.ieee.org/document/10247217) based on our findings

**Software Engineering Intern @ Amadeus IT Group (_July 2021 - September 2021_)**
- Worked on database performance measurement and optimisation on Oracle PL/SQL 
- Gained insight about the design and implementation of customer database systems.

**Software Engineering Intern @ Yapı Kredi Technology (_July 2020 - September 2020_)**
- Created an internal tool as a web application. Built on Java/Spring, Hibernate and an HTML front-end
- Worked on data and address cleaning, and data normalisation scripts on Oracle PL/SQL
- Gained insight about finance industry and financial instruments in general

## Projects
### AI-Enhanced Integrated Field Data Management System (_April 2024 - Present_)
Our team was engaged by a large catering and support services firm in Turkey to identify potential digital growth areas that could be enhanced with AI. An in-depth analysis of the client's IT system was conducted to detect critical points requiring immediate attention while a research was carried out on data analytics and third-party generative AI services to determine suitable solutions. Based on these observations, a strategic roadmap and the architecture for a comprehensive system were designed to streamline the collection, processing, and storage of field data from project managers and field workers. The system aims to provide a more holistic solution by gathering data from a single source, making it easier and more manageable for users to access.

As the implementation phase of the system, a WhatsApp bot integrated with the OpenAI API is being developed to automate data management processes. Although the project is still ongoing, the analysis, technology research, and system design phases have been completed.

### Implementation of Generative AI Models for Pricing Data Extraction (_December 2023 - February 2024_)
As part of a collaborative team, I played a key role in the development of a cloud-based data extraction tool that leveraged OpenAI's GPT-3.5 models, hosted on **Microsoft Azure**. This tool was designed to extract entities, product prices, and associated discounts from CRM customer interview data stored in database. My responsibilities included designing and implementing data pipelines to ensure compatibility with **large language models**, configuring the LLMs, and conducting extensive **prompt engineering** experiments to enhance stability and accuracy of the models. Additionally, we created a statistical ruleset for effective error and outlier detection, further refining our tool's performance. Our project extensively utilized **Azure OpenAI** for AI functionalities and **Azure Functions** for network services, significantly advancing our cloud computing capabilities and knowledge on Generative AI models.

### Implementation of Generative AI Models for Proposal Generation (_November 2023 - January 2024_)
In a recent project, our team developed a content generation tool utilizing OpenAI GPT 3.5 models, designed to automate the creation of client emails for price offers on specified items. The tool integrates seamlessly with Microsoft Outlook to generate product price quotes directly to customers. My contributions included developing algorithms to classify incoming emails, extracting bill of materials from these emails, and matching extracted data with existing material data in our database to derive accurate pricing information. The resulting tool automatically generates tailored price proposal emails. Throughout this project, we employed **Microsoft Azure** for hosting AI and network services through Azure Functions and utilized **OpenAI** services for the deployment of **large language models** (LLMs).

### Traffic Characteristics of Short and Long Public Holidays: A Hybrid Holiday-Oriented Speed Prediction Approach via Feature Engineering (_October 2021 - October 2023_)
[Publication](https://ieeexplore.ieee.org/document/10247217)
The study investigated the idea that public holidays contribute significantly to the overall traffic speed estimation problem and therefore should be handled separately. Contrary to other studies in the literature, in order to achieve successful results in all long and short lasting holidays, a hybrid holiday-oriented approach that combines the **support vector regression (SVR)** algorithm and **historical average (HA)** method is proposed. We additionally fed the proposed model with three novel feature engineering strategies in order to make the system learn similar holidays’ characteristics. To ensure the system’s effectiveness across a broad geographic scope, training and testing were conducted on 441 road segments located in Istanbul, Turkey.

The results demonstrated that the proposed method could achieve up to 29% improvement in terms of mean absolute percentage error (MAPE) values for holiday times over 441 different locations. Moreover, with the help of our novel approach, long-term speed estimation models exceed their limits and we could end up with an average minimization of 2% in terms of mean absolute error (MAE) and MAPE traffic speed prediction error over the year.

### Towards Accurate Traffic Accident Detection: Developing Deep Learning Strategies with Distant Past, Recent Past, and Adjacency Features (_October 2021 - October 2023_)
[Publication](https://ieeexplore.ieee.org/document/10422052)
The aim of this study was to minimize the negative effects of traffic accidents on human life, environmental health and economy on the long run. The study introduces a novel input set derived from distant and near past to detect traffic accidents with a delay of 5–30 minutes while informing authorities and citizens. Furthermore, the study presents statistical methods and windowing techniques to pre-process and transform the traffic speed data into various features, which are then fed into the most preferred deep learning architectures for multivariate time-series data such as **Multi-Layer Perceptron (MLP)**, **Convolutional Neural Networks (CNN)**, and **Long Short-Term Memory (LSTM)** to detect accidents in traffic. 

﻿In order to verify our strategy, we ran our tests on the traffic accident dataset obtained from the 100 main road segments in Istanbul during 2018. With a 15-minute detection delay, CNN-based accident detection model outperformed all other candidate models, while generating an F-Score of 0.75 and an AUC of 0.87. The results indicates that, although there is still a gap for an improvement, pre-eliminary results are promising for determining anomaly in traffic, i.e traffic accidents, exploiting only traffic speed info.

### CFA Institute Research Challenge (_October 2022 - January 2023_)
I participated in the CFA Institute Research Challenge, an annual global competition that demands intensive research in financial analysis and ESG. Representing Yildiz Technical University, our team analyzed Şişecam, Turkey’s largest glass manufacturer and a global industry leader. Under the guidance of Assoc. Prof. Özlem Kutlu Furtuna, we prepared and presented a detailed financial report on the company.

My role in the competition involved conducting a thorough analysis of the company and its industry sectors. I developed **regression models** to estimate the company’s financial multipliers, which were crucial in forecasting the firm’s share price for 2023. This experience enhanced my analytical skills and deepened my understanding of financial modeling and equity research.

### Outfit Recommendation Application for Smartphones (_June 2021 - July 2022_)
I led the development of an application that employs recommendation systems, deep learning, and computer vision to recommend fashion outfits based on the sartorial preferences of a selected cohort. The project, which is funded by TUBITAK, aimed to explore and visualize fashion compatibility.

The process began with the construction of a data scraper using BeautifulSoup and Selenium in **Python** to collect images from fashion retail websites within specific categories. This formed the basis for our recommendation engine, which focused on matching tops with bottoms. I initiated the project by selecting a preliminary set of pairs as seeds for training.

To facilitate data collection for training, I developed a small web application that allowed users to rate random outfit pairs on a scale of 1 to 10. Six users were selected for scoring, providing the data needed to train the recommendation system. Utilizing TensorFlow, I designed the system and implemented a custom layer using transfer learning techniques on top of the pre-trained VGG16 model architecture.

The final model was integrated into a mobile application developed in **Java**, utilizing **Android Studio** with **Retrofit** for network operations, supported by a backend built with **Node.js** and **MongoDB**.

## Publications
1. I. Atilgan, H. I. Turkmen and M. A. Guvensan, "Traffic Characteristics of Short and Long Public Holidays: A Hybrid Holiday-Oriented Speed Prediction Approach via Feature Engineering," in IEEE Sensors Journal, vol. 23, no. 20, pp. 25016-25025, 15 Oct.15, 2023, doi: 10.1109/JSEN.2023.3312189.
2. I. Atilgan, H. I. Turkmen and M. A. Guvensan, "Towards Accurate Traffic Accident Detection: Developing Deep Learning Strategies with Distant Past, Recent Past, and Adjacency Features," 2023 IEEE 26th International Conference on Intelligent Transportation Systems (ITSC), Bilbao, Spain, 2023, pp. 6120-6125, doi: 10.1109/ITSC57777.2023.10422052.


