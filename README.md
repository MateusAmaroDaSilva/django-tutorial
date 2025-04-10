# 📘 Django Tutorial Project

Este projeto foi desenvolvido seguindo o [tutorial oficial do Django](https://docs.djangoproject.com/pt-br/4.2/intro/tutorial01/) até a **Parte 5**, como forma de aprendizado prático dos conceitos fundamentais do framework.

---

## 🚀 Sobre o Projeto

A aplicação é uma **enquete simples** que permite visualizar perguntas, votar em alternativas e ver os resultados.

Durante o processo, foram abordados os principais componentes do Django, incluindo:

- Criação e configuração de um projeto Django
- Definição de modelos (`models.py`)
- Registro de modelos no Django Admin
- Criação de views e uso de URLs
- Templates com HTML dinâmico
- Interação entre frontend e backend
- Uso do shell do Django para testes

---

## 🧰 Tecnologias Utilizadas

- Python 3.x
- Django 4.x
- SQLite (banco de dados padrão)
- HTML/CSS (básico para templates)

---

## 📦 Como Executar o Projeto

### 1. Clone o repositório

```bash
git clone <https://github.com/seu-usuario/nome-do-repositorio.git>

```

### 2. Acesse a pasta do projeto

```bash
cd nome-do-repositorio

```

### 3. Crie um ambiente virtual

```bash
python3 -m venv venv

```

### 4. Ative o ambiente virtual

```bash
source venv/bin/activate  # Linux/macOS

```

### 5. Instale as dependências

```bash
pip install -r requirements.txt

```

### Se não tiver um requirements.txt, instale o Django manualmente:

```bash
pip install django

```

### 6. Aplique as migrações do banco de dados

```bash
python manage.py migrate

```

### 7. Inicie o servidor de desenvolvimento

```bash
python manage.py runserver

```

### Acesse em: [http://localhost:8000](http://localhost:8000/)

## 

### 📂 Estrutura do Projeto

```bash
mysite/
├── manage.py
├── mysite/
│   └── settings.py
├── polls/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   └── admin.py

```

---

### ✅ O que foi implementado até a Parte 5

### 🛠️ Criação do projeto e da aplicação polls

### 🗃️ Definição dos modelos Question e Choice

### 🧑‍💼 Cadastro e gerenciamento no Django Admin

### 🌐 Views baseadas em função e genéricas

### 🧩 Templates com HTML dinâmico e estrutura de diretórios

### 🔗 Mapeamento de URLs com [urls.py](http://urls.py/)

---

### 📚 Referência

### Documentação oficial do Django (pt-br)
