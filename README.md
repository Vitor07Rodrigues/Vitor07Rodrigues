# Olá, eu sou o Vitor Sousa Rodrigues! 👋

Sou desenvolvedor com 1 ano de experiência na área de tecnologia, atualmente atuando no desenvolvimento e engenharia na **linhauni**. Sou apaixonado pelo ecossistema **Backend**, focado em arquitetura de sistemas escaláveis e banco de dados, mas também possuo conhecimentos em Frontend para garantir a entrega ponta a ponta nas aplicações.

Atualmente estou trabalhando no meu tcc, que atualmente segue pricado, porem com o fim do projeto disponibilizarei o mesmo aqui.

### 💻 Minhas Habilidades e Ferramentas

**Backend & Linguagens**  
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)

**Banco de Dados & Infraestrutura**  
![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![Firebase](https://img.shields.io/badge/firebase-%23039BE5.svg?style=for-the-badge&logo=firebase)

**Frontend Básico**  
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

---

## 📋 Projeto em Destaque: Vitaly

No momento, meu principal foco e paixão é o desenvolvimento do **Vitaly**, uma plataforma de **prontuário digital pessoal (PHR)** que centraliza informações de saúde em um único ambiente. O objetivo é permitir que o usuário seja **dono dos próprios dados**, gerenciando sua saúde (e a de sua família) de forma acessível, segura e prática.

### 🧩 Funcionalidades Principais

| Módulo | O que faz |
| :--- | :--- |
| **Prontuário Pessoal** | Armazena exames, vacinas, documentos médicos, alergias e resultados de laboratório. |
| **Gestão de Tratamentos** | Controla medicamentos, horários, notificações, estoque e interações. |
| **Emergência** | Gera QR Code com perfil crítico (tipo sanguíneo, alergias) e botão com localização. |
| **Cuidado Compartilhado** | Permite que cuidadores gerenciem a saúde de dependentes com permissões. |
| **Relatórios** | Exportação de PDFs com histórico de tratamentos para levar em consultas. |

### 🛠️ Tecnologias e Arquitetura

O sistema utiliza uma arquitetura baseada em **Microsserviços**, separando o Core (Django) do motor de IA/OCR (FastAPI), utilizando comunicação via REST e mensageria.

| Camada | Stack Tecnológica |
| :--- | :--- |
| **Backend Core** | Python (3.11), Django (4.2), Django REST Framework |
| **IA & OCR** | FastAPI, Google Cloud Vision, Uvicorn |
| **Banco de Dados & Cache** | PostgreSQL (15), Redis (7) |
| **Filas & Mensageria** | Celery, Celery Beat, Redis (Broker) |
| **Storage & Arquivos** | MinIO (S3-compatible), boto3, Pillow |
| **Notificações & Cloud** | **Firebase** (Cloud Messaging / Push Notifications) |
| **Testes & Qualidade** | pytest, pytest-django, flake8, black, isort |
| **DevOps & Infra** | Docker, Docker Compose, GitHub Actions |
| **Frontend** | React, React Native, TypeScript |

### 🚀 Status do Projeto e Próximos Passos

O Vitaly está em desenvolvimento ativo. No momento, o foco tem sido consolidar a infraestrutura e o backend:

- [x] Estrutura do backend criada via microsserviços.
- [x] Models principais definidos (usuários, prontuários, emergência).
- [x] Pipeline de CI/CD configurada para testes automatizados.
- [x] Ambiente de orquestração local pronto com Docker Compose (PostgreSQL, Redis, MinIO, Django, FastAPI, Celery).
- [ ] Implementar endpoints (autenticação e CRUDs).
- [ ] Integrar OCR com FastAPI para extração autônoma de dados de receitas.
- [ ] Configurar notificações push integrando **Celery + Firebase (FCM)**.
- [ ] Implementação de QR Code de emergência e deploy final em produção.

---

### 📇 Como me encontrar
* **LinkedIn:** [Linkedin](www.linkedin.com/in/vitor-sousa-rodrigues-a09963379)
* **E-mail:** [E-mail para contato](vituxt0995@gmail.com)

