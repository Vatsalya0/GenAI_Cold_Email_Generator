# GenAI_Cold_Email_Generator
 Cold email generator using Llama3.3 LLM, Langchain, Chromadb and Streamlit.

 # 📧 Cold Mail Generator
Cold email generator for services company using groq, langchain and streamlit. It allows users to input the URL of a company's careers page. The tool then extracts job listings from that page and generates personalized cold emails. These emails include relevant portfolio links sourced from a vector database, based on the specific job descriptions. 

**Imagine a scenario:**

- OptimSpace needs a AI ML Intern and is spending time and resources in the hiring process, on boarding, training etc
- PixelMind is Software Development company can provide a dedicated AI ML development engineer to OptimSpace. So, the business development executive (Rahul) from PixelMind is going to reach out to OptimSpace via a cold email.

![img.png](img/img.jpeg)

## Architecture Diagram
![img.png](img/architecture.png)

## Set-up
1. To get started we first need to get an API_KEY from here: https://console.groq.com/keys. Inside `app/.env` update the value of `GROQ_API_KEY` with the API_KEY you created. 


2. To get started, first install the dependencies using:
    ```commandline
     pip install -r requirements.txt
    ```
   
3. Run the streamlit app:
   ```commandline
   streamlit run app/main.py
   ```
   

Copyright (C) Codebasics Inc. All rights reserved.

**Additional Terms:**
This software is licensed under the MIT License. However, commercial use of this software is strictly prohibited without prior written permission from the author. Attribution must be given in all copies or substantial portions of the software.
