# Clippy AI - Assistente de Voz para Análise de Dados de Vendas de Carros

Clippy AI é um assistente de voz interativo que utiliza Inteligência Artificial para responder perguntas sobre um dataset de vendas de carros. Ele combina reconhecimento de voz, processamento de linguagem natural e síntese de fala para oferecer uma experiência fluida e intuitiva.

## Recursos
- **Interação por voz:** Utilize um atalho de teclado para falar com a IA.
- **Análise de dados com Pandas:** O agente analisa o dataset de vendas de carros e responde suas perguntas.
- **Transcrição de áudio:** O modelo Whisper converte suas perguntas faladas em texto.
- **Respostas em voz:** O modelo de síntese de fala do OpenAI transforma as respostas em áudio.

## Tecnologias Utilizadas
- **Python**
- **OpenAI GPT-4o-mini**
- **Whisper (modelo de reconhecimento de fala)**
- **Pandas (para análise de dados)**
- **LangChain (para criação do agente de IA)**
- **SoundDevice (para gravação e reprodução de áudio)**
- **pynput (para controle via teclado)**

## Instalação
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/clippy-ai.git
   cd clippy-ai
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Configure sua chave de API OpenAI:
   - Crie um arquivo `.env` na raiz do projeto e adicione sua API Key:
     ```
     API_KEY=your_openai_api_key
     ```
4. Adicione o dataset de vendas de carros na raiz do projeto:
   - Nome do arquivo: `car_price_dataset.csv`

## Como Usar
1. Execute o script principal:
   ```bash
   python main.py
   ```
2. Pressione **Ctrl** para iniciar ou parar a gravação.
3. Fale sua pergunta e aguarde a resposta em voz.

## Exemplo de Perguntas
- "Qual é o carro mais caro no dataset?"
- "Quantos carros foram vendidos em 2023?"
- "Qual é a média de preço dos carros?"

## Contribuição
Fique à vontade para contribuir com melhorias, correções ou novos recursos. Basta abrir um pull request ou relatar problemas na aba de issues.

## Licença
Este projeto está licenciado sob a [MIT License](LICENSE).

