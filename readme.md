## 1. Introduction
The “Custom Health Insurance ChatBot” is a conversational agent designed to respond to user
queries related to health insurance policies. It is trained using data from Policy Bazaar, a popular
insurance aggregator platform. The ChatBot utilizes the GPT-3.5 API from OpenAI to generate
answers based on its training data.

## 2. Running the Project
To run the project follow the below steps:
1. Download the project folder and open it in your code editor. 
2. Run the following commands:

    ```pip install -r requirements.txt```

    ```python app.py```

3. Visit http://127.0.0.1:7860/

## 3. Training 
You can train the model by adding files to the docs folder. 

## 4. Features & Limitations
The ChatBot was trained on a 35-page Policy Wording taken from PolicyBazaar. It was
able to answer questions based on it. Furthermore, the replies were factually correct and
generated responses that considered the context of the conversation.

As a second use case, the ChatBot was trained on two different Policy Documents. This time 
the responses tend to be focused on only one policy document. They improved as the questions
became specific. The limited word count of the responses was also an obstacle.

## 5. Data Source
The training data for the ChatBot was collected from Policy Bazaar's publicly available
information and includes general information about health insurance policies, coverage details,
and common user queries. The ChatBot cannot access real-time or personalized user data from
Policy Bazaar.

## 6. Further Improvements
In my assessment, there are several areas where the ChatBot could be enhanced:
1. Accuracy Verification: Although the ChatBot generally performs well, we should strive
to improve its response accuracy further. Validating and verifying the information it
provides will instill more user confidence during interactions.

2. Expanding Training Data: By expanding the ChatBot's training data with comprehensive
and up-to-date information, we can enhance its knowledge base and improve the quality
of responses.

3. Real-Time Updates: The ChatBot currently relies on static training data. We can also
consider the possibility of integrating real-time updates or the latest policy information
into the ChatBot's responses.

4. Multi-Document Training Optimization: When trained on multiple policy documents, the
ChatBot may need improvements to avoid fixating on one document and instead leverage
information from all sources to generate more comprehensive responses.

## 7. References
For building the ChatBot:

https://beebom.com/how-train-ai-chatbot-custom-knowledge-base-chatgpt-api/

For training the ChatBot:

https://www.policybazaar.com/
