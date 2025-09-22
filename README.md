# API REST - Notificação por E-mail

Este projeto implementa uma API REST para envio de notificações por e-mail, utilizando **Java com Spring Boot** e **JavaMailSender**. A estrutura de templates é gerenciada com **TemplateEngine**, 
permitindo personalização dinâmica das mensagens.

---

## 🚀 Tecnologias Utilizadas

- **Linguagem:** Java  
- **Frameworks:** Spring Boot  
- **Envio de E-mail:** JavaMailSender  
- **Templates de E-mail:** TemplateEngine  
- **DevOps:** Docker, Git/GitHub  
- **Qualidade de Código:** SonarLint/SonarQube  

---

## 📂 Funcionalidades

- Envio de notificações por e-mail com templates personalizados  
- Configuração de servidor SMTP para envio de e-mails  
- Suporte a variáveis dinâmicas nos templates de e-mail  
- Monitoramento de qualidade de código com **SonarLint/SonarQube**  
- Containerização da aplicação com **Docker**  

---

## 🛠️ Como Rodar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/Danniesantos/notificacao.git
   
2. Navegue até o diretório do projeto:
bash
Copiar código
cd notificacao

3. Construa e execute o projeto:
bash
Copiar código
mvn spring-boot:run

4. Acesse a documentação da API:
bash
Copiar código
http://localhost:8080/swagger-ui.html
