# 📘 Assignment: REST APIs with FastAPI
## 🎯 Objective

Construir uma API REST simples usando o framework FastAPI em Python. O objetivo é entender rotas, métodos HTTP, validação de entrada e resposta JSON.

## 📝 Tasks

### 🛠️ Task 1: Criar endpoints básicos

#### Description
Implemente endpoints GET e POST para gerenciar uma coleção simples de recursos (por exemplo, notas ou tarefas).

#### Requirements
- Criar um endpoint `GET /items` que retorna uma lista de itens
- Criar um endpoint `POST /items` que aceita JSON e adiciona um novo item
- Usar modelos Pydantic para validação de entrada

### 🛠️ Task 2: Validação e documentação automática

#### Description
Adicione validação dos dados de entrada e confirme que a documentação automática (Swagger UI) está disponível.

#### Requirements
- Validar campos obrigatórios usando Pydantic
- Verificar que a documentação está acessível em `/docs`

---
**Dica:** Forneça um `requirements.txt` com `fastapi` e `uvicorn` se quiser que os estudantes rodem localmente.
```
