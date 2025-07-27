# 🤖 Automação de Testes Unitários com LangChain e Azure ChatGPT

Projeto prático do desafio DIO para automação da criação de **testes unitários** utilizando **modelos de linguagem (LLMs)** com **LangChain** e **Azure OpenAI ChatGPT**.

---

## 🧠 Conceitos Aplicados

- LangChain para orquestração de prompts
- Azure OpenAI (ChatGPT) para geração de código
- Testes com Pytest
- Engenharia de prompts
- Automação com Python
- Boas práticas de documentação e uso do GitHub

---

## 🛠️ Tecnologias

- Python 3.10+
- LangChain
- Azure OpenAI (ChatGPT)
- Pytest
- dotenv
- Git & GitHub

---

## 📁 Estrutura do Projeto
langchain-test-generator/
├── src/
│ ├── main.py
│ ├── prompts.py
│ ├── generator.py
│ └── utils.py
├── tests/
│ └── exemplo_func.py
├── .env.example
├── requirements.txt
├── README.md
└── images/
└── print-execucao.png
________________________________________________________________________________________________________________


---

## ⚙️ Como Executar

1. Clone o repositório

2. Crie e ative um ambiente virtual

python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

3. Instale as dependências
pip install -r requirements.txt

4. Configure o .env com base no .env.example
AZURE_OPENAI_KEY=your-key-here
AZURE_OPENAI_ENDPOINT=https://your-instance.openai.azure.com/
AZURE_DEPLOYMENT_NAME=your-deployment-name

5. Execute o gerador de testes
   python src/main.py



  Observações
  
O projeto é extensível para múltiplas funções e diretórios.
Geração 100% automática com base no código fornecido.
Ideal para integrar em pipelines CI/CD para reforçar a cobertura de testes.


 Referências
 
LangChain
Azure OpenAI
Pytest
GitHub Markdown
   
