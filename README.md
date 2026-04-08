# 🤖 Chatbot Interno de TI com Azure OpenAI

## 📌 Descrição
Este projeto foi desenvolvido com o objetivo de explorar as funcionalidades do Azure OpenAI e do Microsoft Copilot na criação de soluções baseadas em inteligência artificial generativa.

A aplicação consiste em um chatbot interno de TI, desenvolvido em Python com Streamlit, capaz de responder dúvidas técnicas simulando o comportamento de um analista de suporte. A solução utiliza um modelo implantado no Azure OpenAI, com respostas orientadas por prompt engineering.

---

## 🎯 Objetivos do Projeto

- Aplicar conceitos de IA generativa em um cenário prático  
- Utilizar Azure OpenAI para construção de aplicações inteligentes  
- Explorar o uso de prompts estruturados (prompt engineering)  
- Documentar processos técnicos de forma clara  
- Utilizar o GitHub como ferramenta de versionamento e compartilhamento  

---

## ⚙️ Tecnologias Utilizadas

- Python  
- Streamlit  
- Azure OpenAI  
- Microsoft Copilot  
- GitHub  

---

## 🧠 Funcionamento da Solução

O chatbot utiliza um modelo implantado no Azure OpenAI (`gpt-4o-mini`) e responde perguntas com base em um contexto definido por prompt.

A aplicação realiza:

1. Captura da pergunta do usuário via interface web  
2. Envio da requisição para o Azure OpenAI  
3. Processamento da resposta com base no prompt definido  
4. Exibição da resposta no formato de chat  

---

## 💬 Prompt Utilizado

```text
Você é um analista de suporte interno de TI nível 3.

Responda sempre com:
1. Diagnóstico direto
2. Possível causa raiz
3. Teste prático
4. Solução objetiva

Evite respostas genéricas.
Considere ambiente corporativo com Microsoft 365.
