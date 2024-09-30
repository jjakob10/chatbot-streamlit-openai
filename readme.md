# Chatbot com Streamlit e OpenAI

Este projeto implementa um chatbot simples usando a API da OpenAI e a interface de usuário do Streamlit. Ele permite que os usuários insiram uma chave de API da OpenAI para interagir com o modelo GPT-4o-mini.

## Funcionalidades

- **Integração com OpenAI**: O chatbot utiliza a API da OpenAI para gerar respostas com base em entradas fornecidas pelo usuário.
- **Interface do Streamlit**: A interface do Streamlit facilita a interação com o chatbot por meio de um layout simples e amigável.
- **Mensagens Persistentes**: As mensagens trocadas com o chatbot são mantidas durante a sessão e exibidas na interface.

## Requisitos

- Python 3.8+
- Conta na OpenAI com uma chave de API

## Instalação

1. Clone este repositório:

   ```bash
   git clone https://github.com/jjakob10/chatbot-streamlit-openai.git
   cd chatbot-streamlit-openai
   ```

2. Crie um ambiente virtual e ative-o:

   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   ```

3. Instale as dependências:

   ```bash
   pip install -r requirements.txt
   ```

## Como Executar

1. Execute o aplicativo com o Streamlit:

   ```bash
   streamlit run app.py
   ```

2. Abra o navegador no endereço fornecido, geralmente `http://localhost:8501`, e adicione sua chave de API no campo fornecido na barra lateral.

3. Comece a interagir com o chatbot!

## Personalização

- **Modelo OpenAI**: O modelo utilizado por padrão é o `gpt-4o-mini`. Isso pode ser alterado ajustando o valor da chave `"openai_model"` no estado da sessão (`st.session_state`).
- **Exibição de Mensagens**: As mensagens de entrada e saída são exibidas no formato de chat, permitindo uma visualização fácil do histórico de conversas.

## Dependências

- **OpenAI**: Para acessar a API da OpenAI.
- **Streamlit**: Para criar a interface web.

## Licença

Este projeto está licenciado sob a MIT License
