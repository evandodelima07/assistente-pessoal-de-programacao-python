# DSA AI Coder — Assistente de Programação Python

> Desenvolvido para auxiliar em suas dúvidas de programação com Python.  
> ⚠️ A IA pode cometer erros. Sempre verifique as respostas.

---

## 📋 Sobre o Projeto

Assistente inteligente de programação Python, construído com Streamlit e integrado à API da Groq. Ideal para tirar dúvidas de sintaxe, lógica e uso de bibliotecas.

**Stack principal:** Streamlit · Groq API · Pandas · NumPy

---

## ✅ Pré-requisitos

- [Miniconda ou Anaconda](https://www.anaconda.com/download) instalado
- Chave de API da [Groq](https://console.groq.com) (gratuita)

---

## ⚙️ Configuração do Ambiente

### 1. Criar o ambiente virtual

```bash
conda create --name dsaec1 python=3.13
```

### 2. Ativar o ambiente

```bash
conda activate dsaec1
# ou, em sistemas Unix:
source dsaec1/bin/activate
```

### 3. Instalar as dependências

```bash
conda install pip
pip install -r requirements.txt
```

### 4. Configurar a chave de API

Crie um arquivo `.env` na raiz do projeto com o seguinte conteúdo:

```env
GROQ_API_KEY=sua_chave_aqui
```

> Obtenha sua chave gratuita em [console.groq.com](https://console.groq.com)

### 5. Executar a aplicação

```bash
streamlit run dsa_assistente.py
```

---

## 💬 Exemplos de Uso

Perguntas que você pode fazer ao assistente:

- `Como crio um hello world em Python?`
- `Qual a sintaxe de um loop em Python?`
- `Como eu uso a função map em Python? Me dê um exemplo com lambda.`

---

## 🧹 Desativar e Remover o Ambiente (opcional)

```bash
conda deactivate
conda remove --name dsaec1 --all
```