# LLM-Simulator-for-Situations
Master's thesis project of students from the Master's in Big Data, Data Science &amp; Business Analytics at UCM.

## Team members
- Alejandro Blanco Rey.
- Amy Ramírez Jurado.
- Bruno Dosaula Ces.
- Germán David Cortés Hernández.
- Nicolás Esteban Spector.

## Description:

### AI-Powered Chatbot for Pharmaceutical Negotiation Scenarios

This project focuses on developing an AI-driven chatbot specialized in pharmaceutical negotiation scenarios. It integrates advanced Natural Language Processing (NLP) techniques with a modular and structured architecture to effectively manage user-provided information.

Built upon the COM-B model and prompt engineering techniques, the chatbot embodies distinct identities, motivations, and negotiation strategies, making interactions more dynamic and realistic. Its capabilities are further enhanced by incorporating contextual data, enabling more informed and adaptive decision-making.

Additionally, the system includes AI-assisted agent customization, Retrieval-Augmented Generation (RAG), voice command capabilities, dual-agent interaction mode, and feedback analysis. These features are designed to optimize user experience and enhance the learning process, ensuring a more immersive and effective negotiation simulation.

## Instructions to Run the Code
1. We recommend creating a specific virtual environment using Anaconda Prompt. To do so, run:
   ```bash
   conda create --name tfm python=3.11
2. Activate the enviroment:
   ```bash
   conda activate tfm
4. Then, navigate to the main `app.py` folder.
5. Install the necessary libraries using the following command:
   ```bash
   pip install -r requirements.txt
6. Navigate to the `config/local` folder and edit the `credentials.yml` file with a valid API KEY:
   ```bash
   OPENAI_API_KEY: 'xxx'
7. Run the `app.py` file:
   ```bash
   streamlit run app.py
