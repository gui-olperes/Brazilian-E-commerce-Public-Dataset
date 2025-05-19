# Análise de Dados da Olist

Este projeto contém um notebook de análise exploratória, modelagem e visualização dos dados do e-commerce brasileiro Olist. O objetivo é extrair insights de negócio, criar dashboards e propor soluções baseadas nos dados.

## 📁 Estrutura do Projeto

- `olist_analise.ipynb` — Notebook principal com todo o fluxo de análise.
- `requirements.txt` — Lista de dependências necessárias.
- `datasets/` — Pasta onde devem estar os arquivos CSV do dataset Olist.
- `olist.db` — Banco SQLite gerado automaticamente pelo notebook.

## 🚀 Como executar o notebook

### 1. Clone o repositório e acesse a pasta

```sh
git clone <url-do-repositorio>
cd Brazilian-E-commerce-Public-Dataset
```

### 2. Crie um ambiente virtual (opcional, mas recomendado)

No Windows:
```sh
python -m venv .venv
.venv\Scripts\activate
```
No Linux/Mac:
```sh
python3 -m venv .venv
source .venv/bin/activate
```

### 3. Instale as dependências

```sh
pip install -r requirements.txt
```

### 4. Execute o notebook

Você pode abrir o notebook de duas formas:

#### a) Usando o Jupyter Notebook

```sh
jupyter notebook
```
Depois, abra o arquivo `olist_analise_final_completo_reestruturado.ipynb` pelo navegador.

#### b) Usando o VS Code

- Abra a pasta do projeto no VS Code.
- Instale a extensão "Jupyter" se solicitado.
- Abra o notebook e execute as células.

### 6. Rode todas as células

Execute as células do notebook em ordem.  
A primeira execução pode demorar um pouco, pois o banco de dados será criado a partir dos CSVs.

---

## ⚠️ Dicas para evitar erros

- **Caminhos relativos:** Certifique-se de que a pasta `datasets/` está no mesmo nível do notebook.
- **Banco de dados:** O arquivo `olist.db` será criado automaticamente. Se já existir, pode ser sobrescrito.
- **Dependências:** Use sempre o `requirements.txt` para instalar as bibliotecas.
- **Ambiente limpo:** Se possível, use um ambiente virtual para evitar conflitos de versões.
- **Permissões:** Se der erro de permissão ao criar arquivos, execute o terminal como administrador.

---
