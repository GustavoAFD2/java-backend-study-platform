# ☕ Plano de Estudos — Java Backend (Foco em Estágio)

![Java](https://img.shields.io/badge/Java-17%2B-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.x-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-SQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Basic-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

Plataforma web interativa para organizar, acompanhar e documentar uma trilha prática de **~16 semanas (4 meses)** focada na conquista da primeira vaga de **estágio em Desenvolvimento Backend Java**.

🔗 **Acesse a plataforma online:** `🔗 **Acesse a plataforma online:** https://gustavoafd2.github.io/java-backend-study-platform/` 

---

## 🎯 Sobre o Projeto

Esta aplicação transforma um cronograma estruturado de estudos em um **painel interativo e hub de portfólio**:

- **Progresso isolado por visitante:** Cada pessoa que acessa a plataforma tem seu progresso salvo individualmente no navegador (`localStorage`). Ao abrir pela primeira vez, é possível iniciar a trilha do zero (`0%`) ou ativar o **Modo Demo** (ideal para recrutadores visualizarem a interface preenchida).
- **Trilha completa em 7 Fases:**
  1. **Fase 1 (Semanas 1-3):** Fundamentos de Java (JDK, sintaxe, controle de fluxo, arrays, strings, exceções)
  2. **Fase 2 (Semanas 4-6):** Orientação a Objetos (encapsulamento, herança, polimorfismo, interfaces, enums, Clean Code)
  3. **Fase 3 (Semanas 7-8):** Collections, Generics e Java 17+ (Streams, Lambdas, Optional, Records)
  4. **Fase 4 (Semana 9):** SQL e Banco de Dados (Modelagem relacional, PostgreSQL/MySQL, JDBC)
  5. **Fase 5 (Semanas 10-13) — Coração do Plano:** Spring Boot (IoC/DI, REST Controllers, DTOs, `@Valid`, Spring Data JPA, `@ControllerAdvice`, Spring Security/JWT, JUnit 5 & Mockito)
  6. **Fase 6 (Semana 14):** Ferramentas e Boas Práticas (Git/GitHub, Maven/Gradle, Docker, Postman/Insomnia, Swagger/OpenAPI, SOLID)
  7. **Fase 7 (Semanas 15-16):** Portfólio, LinkedIn, LeetCode/HackerRank e Preparação para Entrevistas
- **Funcionalidades extras:**
  - 📊 Dashboard com cálculo automático de progresso e badges da stack desbloqueadas dinamicamente
  - ⏱️ Timer Pomodoro integrado (25m foco / 5m pausa) + registro manual de horas estudadas
  - 🚀 Central de Portfólio para vincular repositórios do GitHub e status de cada projeto prático
  - 📝 Caderno de anotações por fase e roteiro para o projeto "carro-chefe"
  - 💾 Exportação/Importação de progresso em `.json` e botão para reiniciar tudo a qualquer momento

---

## 🛠️ Tecnologias Utilizadas na Interface

- **HTML5 Semântico**
- **Tailwind CSS** (via CDN, com suporte a Dark/Light Mode)
- **JavaScript Vanilla (ES6+)** com persistência via `localStorage` e Web Audio API (alerta sonoro do Pomodoro)

---

## 🚀 Como Executar Localmente

Nenhuma instalação ou build complexo é necessário:

```bash
# 1. Clone o repositório
git clone https://github.com/SEU-USUARIO/java-backend-study-platform.git

# 2. Acesse a pasta do projeto
cd java-backend-study-platform

# 3. Abra o arquivo index.html no navegador
# Ou utilize a extensão Live Server no VS Code
```

---

## 🌐 Como Publicar Gratuitamente no GitHub Pages

1. Crie um repositório público no GitHub (ex.: `java-backend-study-platform`).
2. Envie os arquivos deste projeto (`index.html`, `README.md`, `LICENSE`, `.gitignore`).
3. No repositório do GitHub, acesse **Settings** → **Pages**.
4. Em **Build and deployment** → **Source**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/ (root)` e clique em **Save**.
6. Aguarde cerca de 1 minuto e o link oficial estará ativo!

---

## 🔮 Próximos Passos (Evolução Full-Stack)

Ao avançar pelas **Fases 4, 5 e 6** da trilha, este projeto pode ser evoluído para uma arquitetura Full-Stack completa substituindo o `localStorage` por uma API própria:

- **Backend:** Java 17+ com Spring Boot 3, Spring Web e Spring Data JPA
- **Banco de Dados:** PostgreSQL rodando em container Docker
- **Autenticação:** Spring Security + JWT para login de múltiplos usuários
- **Documentação:** Swagger / OpenAPI

---

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
