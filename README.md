# Q&A com IA - Processamento de Linguagem Natural usando LangChain

## 🌟 Visão Geral
Este projeto é um aplicativo interativo desenvolvido com **Streamlit** que permite fazer **Perguntas e Respostas (Q&A)** em diversos tipos de arquivos, usando **LangChain** e **OpenAI GPT-4**. Ele aceita arquivos de texto, PDFs, imagens e até documentos do Word, extrai o conteúdo e responde às perguntas com base nas informações fornecidas.

## 🚀 Funcionalidades Principais
- **Uploads de arquivos:** Suporta PDFs, TXT, CSV, DOCX, JPEG e PNG.
- **Processamento de texto com OCR:** Extrai texto de imagens.
- **Integração com OpenAI (GPT-4):** Responde a perguntas baseadas no conteúdo dos arquivos.
- **Suporte a diferentes métodos de encadeamento:** `stuff`, `map_reduce`, `refine`, `map_rerank`.
- **Controle do número de chunks relevantes:** Personalize a busca por partes mais importantes do documento.

## 🔧 Tecnologias Utilizadas
- **Python**
- **Streamlit** (interface web interativa)
- **Pandas** (para CSV)
- **Pillow (PIL)** (para imagens)
- **PyTesseract** (OCR para extração de texto de imagens)
- **LangChain** (estrutura para perguntas e respostas)
- **OpenAI GPT-4** (modelo de linguagem)
- **Chroma** (vetorização e armazenamento)

## 📥 Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seuusuario/nome-do-repositorio.git
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Configure sua chave da OpenAI:
```bash
export OPENAI_API_KEY='sua-chave-aqui'
```

4. Execute o aplicativo:
```bash
streamlit run app.py
```

## 🎯 Como Usar

1. **Faça o upload de um arquivo (PDF, TXT, CSV, DOCX, JPEG ou PNG).**
2. **Insira sua chave da OpenAI.**
3. **Escreva a pergunta baseada no conteúdo do arquivo.**
4. **Escolha o tipo de encadeamento e o número de chunks relevantes.**
5. **Clique em 'Run!' e aguarde a resposta.**

## ⚠️ Tratamento de Erros
O app lida com diferentes tipos de erros, como:
- **Erros de leitura de PDF.**
- **Chave de API inválida.**
- **Pedidos mal formatados para a API da OpenAI.**
- **Arquivos não suportados.**

## 🔥 Melhorias Futuras
- 🔧 **Suporte a mais formatos de arquivo (JSON, XLSX)**
- 💡 **Melhor detecção de erros e feedback mais descritivo para o usuário**
- 🚀 **Cache de respostas para perguntas repetidas**

## 📄 Licença
Este projeto está licenciado sob a licença MIT.

---

🎉 **Divirta-se explorando o poder da IA aplicada em seus documentos!**


