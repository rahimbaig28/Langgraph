# **AI-Powered Supplier Quality Engineering Using Langchain & Groq**

## **Project Overview**
This project leverages **LangChain**, **LangGraph**, and **Groq** to develop an AI-powered solution for **Supplier Quality Engineering**. The implementation focuses on **document verification, risk assessment, collaboration, and predictive analytics** using advanced AI tools. It integrates **Wikipedia and ArXiv search tools** for quick information retrieval, along with **LLM (Large Language Model) capabilities** via **Groq**.

---

## **Features**
- **Document Review and Compliance**: Uses AI tools such as **Kofax Power PDF** and **DocuSign Insight** to verify packaging change control requests.
- **Risk Assessment & Predictive Analytics**: Implements **IBM Watson Studio** and **SAP Predictive Analytics** to assess potential risks in supplier quality.
- **Collaboration & Communication**: Integrates **Slack** and **Microsoft Teams** to enhance communication with AI bots.
- **Testing Protocols & Analysis**: Utilizes **Minitab** and **TensorFlow** for data analysis in testing new packaging materials.
- **Project Timelines & Compliance Tracking**: Implements **Monday.com** and **Smartsheet** to manage project tasks and deadlines.
- **Continuous Learning**: Uses **Clarifai** and **Feedly** to stay updated on the latest regulations and packaging material innovations.

---

## **Technology Stack**
- **Programming Language**: Python
- **AI Frameworks**: LangChain, LangGraph, LangChain Community
- **Large Language Model (LLM)**: Groq (Gemma2-9B-IT)
- **Data Sources**: Wikipedia, ArXiv
- **APIs & Libraries**:
  - `ArxivAPIWrapper`, `WikipediaAPIWrapper` for data retrieval
  - `ChatGroq` for LLM-based query processing

---

## **Installation & Setup**
1. **Clone the Repository**
   ```sh
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. **Install Dependencies**
   ```sh
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables**
   - Create a `.env` file in the root directory and add your **Groq API Key**:
     ```sh
     GROQ_API_KEY=your_api_key_here
     ```

4. **Run the Application**
   ```sh
   python main.py
   ```

---

## **Code Structure**
```
├── main.py               # Entry point for the application
├── config.py             # Configuration settings
├── utils/
│   ├── ai_tools.py       # AI tool integrations
│   ├── data_processing.py # Data handling functions
├── notebooks/
│   ├── langchain_demo.ipynb  # Jupyter Notebook for testing
├── requirements.txt      # Dependencies
├── .env                  # API keys and environment variables
└── README.md             # Project Documentation
```

---

## **Usage**
- **Retrieve Research Papers**:  
  ```python
  arxiv_tool.invoke("Attention is all you need")
  ```
- **Query Wikipedia**:  
  ```python
  wiki_tool.invoke("Who is Rahim Baig?")
  ```
- **Initialize LLM Model**:  
  ```python
  from langchain_groq import ChatGroq
  llm = ChatGroq(groq_api_key="your_api_key", model_name="gemma2-9b-it")
  ```

---

## **Future Enhancements**
- **Expand AI tool integration for supplier risk assessment**
- **Enhance automation in packaging compliance verification**
- **Integrate more LLM models for industry-specific analysis**

---

## **Contributing**
Contributions are welcome! Feel free to open an issue or submit a pull request.

---

## **License**
This project is licensed under the MIT License.

---

## **Contact**
For any inquiries or collaborations, feel free to reach out at [rahimbaig00332211@Gmail.com](mailto:rahimbaig00332211@Gmail.com).

