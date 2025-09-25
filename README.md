# 🤖 Assistente de IA - Programação Python

Um assistente de inteligência artificial especializado em programação Python, desenvolvido com Streamlit e integrado à API da Groq para fornecer respostas precisas e didáticas sobre desenvolvimento, principalmente sobre a linguagem python.

## Sobre o Projeto

Este projeto é um assistente de IA focado em auxiliar desenvolvedores iniciantes com dúvidas de programação Python. O assistente fornece:

- **Explicações claras** de conceitos de programação
- **Exemplos de código** bem comentados
- **Detalhamento técnico** das implementações
- **Links de referência** para documentação oficial

## Funcionalidades

- ✅ Interface web interativa desenvolvida com Streamlit
- ✅ Integração com a API da Groq para processamento de linguagem natural
- ✅ Respostas estruturadas e didáticas
- ✅ Foco exclusivo em programação Python
- ✅ Histórico de conversas durante a sessão
- ✅ Interface responsiva e intuitiva

## Tecnologias Utilizadas

- **Python 3.x** - Linguagem de programação principal
- **Streamlit** - Framework para criação da interface web
- **Groq API** - Serviço de IA para processamento de linguagem natural
- **Git** - Controle de versão

## Pré-requisitos

Antes de executar o projeto, certifique-se de ter:

- Python 3.7 ou superior instalado
- Uma conta na [Groq](https://console.groq.com/) para obter a API Key
- Git instalado (opcional)

## Como Instalar e Executar

### 1. Clone o repositório
```bash
git clone https://github.com/ramoneirao/assistente-ia.git
cd assistente-ia
```

### 2. Crie um ambiente virtual (recomendado)
```bash
python -m venv venv

# No Linux/Mac:
source venv/bin/activate

# No Windows:
venv\Scripts\activate
```

### 3. Instale as dependências
```bash
pip install -r requirements.txt
```

### 4. Obtenha sua API Key da Groq
1. Acesse [https://console.groq.com/keys](https://console.groq.com/keys)
2. Faça login ou crie uma conta
3. Gere uma nova API Key
4. Guarde a chave com segurança

### 5. Execute o projeto
```bash
streamlit run assistente_ia.py
```

### 6. Acesse a aplicação
- O Streamlit abrirá automaticamente seu navegador
- Se não abrir, acesse: `http://localhost:8501`
- Insira sua API Key da Groq na barra lateral
- Comece a fazer suas perguntas sobre Python!

## Como Usar

1. **Insira sua API Key**: Na barra lateral, cole sua chave da API da Groq
2. **Faça sua pergunta**: Digite sua dúvida sobre programação Python no campo de chat
3. **Receba a resposta**: O assistente fornecerá uma explicação estruturada com:
   - Conceito teórico
   - Exemplo de código comentado
   - Explicação detalhada
   - Links para documentação oficial

## Aprendizados do Projeto

Durante o desenvolvimento deste assistente, foram aplicados diversos conceitos importantes:

### **Integração com APIs Externas**
- Configuração e autenticação com a API da Groq
- Tratamento de erros e exceções em requisições HTTP
- Gerenciamento de chaves de API de forma segura

### **Desenvolvimento de Interface Web**
- Uso do Streamlit para criar interfaces interativas
- Gerenciamento de estado da sessão
- Criação de componentes de UI responsivos
- Implementação de chat em tempo real

### **Engenharia de Prompt**
- Desenvolvimento de prompts de sistema estruturados
- Definição de regras e comportamentos específicos
- Formatação de respostas para melhor didática

### **Gerenciamento de Projeto**
- Uso de requirements.txt para dependências
- Estruturação de repositório Git
- Documentação de projeto (README.md)

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para:

- Reportar bugs
- Sugerir melhorias
- Enviar pull requests
- Compartilhar feedback

---

## 📚 Créditos

Este projeto foi desenvolvido como parte do curso **"Fundamentos de Linguagem Python - Do Básico a Aplicações de IA"** da [Data Science Academy](https://www.datascienceacademy.com.br/).

O curso aborda conceitos fundamentais da linguagem Python e suas aplicações em inteligência artificial, proporcionando uma base sólida para desenvolvimento de projetos práticos como este assistente de IA.
