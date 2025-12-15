# E‑commerce – SENAC

Este repositório contém um **exemplo de e‑commerce simples desenvolvido em aula no SENAC**, onde os alunos praticaram a construção de uma aplicação web com **Python (backend)** e interfaces HTML (frontend), além de interagir com banco de dados utilizando scripts SQL.

O material foi planejado com foco em **entender o fluxo de uma aplicação web completa**, servindo como referência prática para aprendizagem e revisão.

---

## 🎯 Objetivo Educacional

O projeto tem como objetivo auxiliar os alunos a:

- Compreender o fluxo de uma aplicação web com backend em Python
- Integrar rotas Python com templates HTML
- Trabalhar com scripts SQL para persistência de dados
- Construir lógica de cadastro e consulta de produtos
- Fixar conceitos de backend, frontend e banco de dados em uma solução real simples

---

## 📁 Estrutura do Projeto

Aulas_Ecommerce_Python_SENAC/
- ├── appdesktop/ # Código de aplicação desktop (se aplicável)
- ├── ecomerce.sql # Script SQL do banco de dados
- ├── SQLaula)!.sql # Script adicional de exemplo/estruturas SQL
- ├── templates/ # Templates HTML usados pelo backend
- │ └── *.html # Páginas HTML (visão do site)
- ├── Levantamentos.docx # Documento com levantamentos/análises
- ├── README.md # Este arquivo

yaml
Copiar código

---

## 🛠️ Como executar (local)

1. Clone o repositório:
   ```bash
   git clone https://github.com/GregoryKz/Aulas_Ecommerce_Python_SENAC.git
Entre na pasta do projeto:

bash
Copiar código
cd Aulas_Ecommerce_Python_SENAC
Instale Python (recomendado 3.8+).

Configure o banco de dados com o script ecomerce.sql (por exemplo no MySQL ou SQLite).

(Opcional) crie um ambiente virtual:

bash
Copiar código
python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows
Instale dependências (se houver):

bash
Copiar código
pip install flask
Execute a aplicação:

bash
Copiar código
python app.py
Abra o navegador:

cpp
Copiar código
http://127.0.0.1:5000
📚 Funcionalidades (exemplo)
Listagem de produtos cadastrados (HTML)

Interação entre Python e templates web

Banco de dados com produtos e informações básicas

Aplicação web simples para fins educacionais

🧪 Aplicação em Sala de Aula
O projeto foi utilizado de forma prática para demonstrar o passo a passo da integração entre backend, banco e frontend, permitindo que os alunos acompanhassem e testassem funcionalidades em tempo real.

🏫 Contexto Acadêmico
Material desenvolvido e aplicado em aulas presenciais do SENAC, com foco em reforçar o uso prático de Python, HTML e SQL em um projeto realista.

👨‍🏫 Docência
Conteúdo estruturado para clareza e aprendizagem gradual, ideal para quem está iniciando no desenvolvimento web com Python.

📌 Repositório de uso educacional.
