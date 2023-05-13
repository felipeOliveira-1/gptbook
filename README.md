# GPTBook
GPT Book é uma aplicação desenvolvida em Python que utiliza o modelo de linguagem GPT-4 para ler e processar livros em PDF, permitindo ao usuário interagir e buscar informações relevantes dentro do conteúdo.

![Descrição da Imagem 1](https://github.com/felipeOliveira-1/gptbook/blob/main/gptbook1.jpg?raw=true)
![Descrição da Imagem 2](https://github.com/felipeOliveira-1/gptbook/blob/main/gptbook2.jpg?raw=true)


## Requisitos
* Python 3.8+
*Bibliotecas:
  * streamlit
  * langchain
  * PyPDFLoader
  * Chroma
## Instalação e configuração
1. Instale as bibliotecas necessárias:

``
pip install streamlit langchain PyPDFLoader Chroma
``

2. Clone o repositório e acesse a pasta do projeto

``
git clone [URL_DO_REPOSITORIO]
``

``
cd gpt_book
``

3. Adicione a chave da API da OpenAI ao arquivo gpt_book.py

``
os.environ['OPENAI_API_KEY'] = 'sua_chave_da_api'
``

4. Execute o aplicativo:

``
streamlit run gpt_book.py
``

## Uso
1. Faça o upload do livro em PDF que deseja processar.
2. Aguarde a mensagem de sucesso ao concluir o processamento.
3. Digite um prompt na caixa de texto e pressione Enter para obter a resposta do GPT-4.
4. Veja os resultados relevantes das páginas do livro processado.

Com o GPT Book, você pode obter respostas rápidas e relevantes de um livro.
