# DSA AI Coder — Assistente de Programação Python

> Desenvolvido para auxiliar em suas dúvidas de programação com Python.  
> ⚠️ A IA pode cometer erros. Sempre verifique as respostas.

---

## 📋 Sobre o Projeto

Assistente inteligente de programação Python, construído com Streamlit e integrado a modelos de linguagem. Ideal para tirar dúvidas de sintaxe, lógica e uso de bibliotecas.

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
source activate dsaec1
```

### 3. Instalar as dependências

```bash
conda install pip
pip install -r requirements.txt
```

### 4. Executar a aplicação

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