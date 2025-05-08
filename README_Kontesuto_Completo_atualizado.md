# 📚 Projeto Gear 5: Contest Guardian

## 🛡️ Visão Geral
O **Contest Guardian** é um site revolucionário para o meio militar, projetado para fornecer informações atualizadas sobre concursos militares e recomendar recursos de estudo personalizados com apoio de IA. A missão? Ajudar futuros guerreiros a vencer batalhas antes mesmo do campo de provas.

---

## 🏛️ Estrutura do Projeto

```
/src
  /backend
    /controllers
    /models
    /routes
    /services
  /frontend
    /components
    /pages
    /styles
  /ai
    /models
    /training
/database
  schema.sql
/tests
  /unit
  /integration
README.md
package.json
```

- `backend`: APIs e lógica do servidor (Spring ou .NET, você escolhe seu veneno).
- `frontend`: Onde a mágica visual acontece. Interface amigável e responsiva.
- `ai`: O cérebro do sistema — modelo de recomendação e personalização.
- `database`: Estrutura das tabelas e relações para armazenar concursos e perfis.
- `tests`: Porque confiamos, mas verificamos. Testes unitários e integração.

---

## 🎨 Decisões de Design

- **Frameworks escolhidos:**  
  - Backend com **Spring** (Java) ou **.NET** (C#) — robustez e segurança.
  - Frontend com tecnologias web modernas (React sugerido, para máxima responsividade).
  - IA com **TensorFlow** ou **PyTorch** — flexibilidade no treino de modelos.

- **Banco de dados:** Relacional, pela necessidade de integridade e relacionamentos claros (ex: PostgreSQL).

- **IA recomendadora:** Modelo treinado com perfis de usuários e dados de concursos para oferecer indicações certeiras e notificações personalizadas.

- **Responsividade:** Projeto feito para funcionar lisinho tanto em desktops quanto em celulares de combate (aka smartphones).

---

## 🚀 Como Executar Localmente

1. **Clone o repositório**
   ```bash
   git clone https://github.com/seuusuario/contest-guardian.git
   cd contest-guardian
   ```

2. **Configure o Banco de Dados**
   - Crie um banco PostgreSQL usando o arquivo `/database/schema.sql`.

3. **Backend**
   - Navegue até `/src/backend`
   - Instale dependências e execute:
     ```bash
     ./mvnw spring-boot:run
     ```

4. **Frontend**
   - Navegue até `/src/frontend`
   - Instale dependências:
     ```bash
     npm install
     ```
   - Rode a aplicação:
     ```bash
     npm run dev
     ```

5. **IA (Opcional para Devs ousados)**
   - Entre em `/src/ai`
   - Treine o modelo com:
     ```bash
     python train.py
     ```

---

## ✅ Critérios de Sucesso

- Funcionalidade 100% no ar.
- Resposta da API em menos de 2 segundos ⚡.
- Clientes com pelo menos 90% de aprovação.
- Entregue no prazo em até 6 meses. Sem choro!

---

## 📝 Relatório de Desenvolvimento

### 🌱 Processo

1. **Fase 1: Análise e Requisitos (4 semanas)**
   - Entrevistas com militares e candidatos.
   - Definição do escopo claro como água.
   
2. **Fase 2: Desenvolvimento (16 semanas)**
   - Construção do site e sistema de recomendação.
   - Integração com plataformas de estudo online.
   - Desenvolvimento da IA que recomenda e notifica.

3. **Fase 3: Testes e Validação (8 semanas)**
   - Testes unitários, integração e aprovação dos stakeholders.
   
---

### ⚔️ Desafios Enfrentados

- **Segurança de dados:** Autenticação forte e criptografia de ponta foram adotadas para proteger informações sensíveis.
- **Desempenho da IA:** Ajustar o modelo para entregar recomendações em tempo real foi como domar um dragão, mas conseguimos otimizando com TensorFlow Lite.
- **Usabilidade:** Tornar o site intuitivo para militares não tão tech-savvy exigiu testes com usuários reais e ajustes na UI.
- **Acessibilidade mobile:** Implementamos design responsivo para garantir acesso desde bases militares até celulares no metrô.

---

### 🏆 Como Superamos

- Adotamos **metodologias ágeis** para responder rapidamente aos feedbacks.
- Utilizamos frameworks modernos para garantir performance.
- Investimos tempo em testes automatizados e validações contínuas.
- Mantivemos comunicação direta com os stakeholders para alinhar expectativas.

---

### 🚩 Status Atual: 
Projeto estruturado, pronto para crescer e conquistar território! 💪🏼

# Kontesuto Gādian

Kontesuto Gādian é um site voltado para o meio militar que fornece informações sobre concursos militares e utiliza inteligência artificial para enviar mensagens personalizadas e recursos de estudo aos usuários.

## 🚀 Tecnologias Utilizadas

Este projeto foi desenvolvido com as seguintes tecnologias:

- Eclipse  
- Visual Studio  
- TensorFlow  
- PyTorch  
- Spring Framework  
- .NET  

## 💻 Como Usar

Você pode acessar o Kontesuto Gādian diretamente por meio do site oficial ou através dos aplicativos desenvolvidos para diferentes plataformas (web e mobile).

### Pré-requisitos

- Navegador moderno ou sistema com suporte a aplicativos .NET/Spring
- Acesso à internet

### Instalação (modo desenvolvedor)

Caso deseje rodar o projeto localmente para fins de desenvolvimento:

```bash
# Clone este repositório
git clone https://github.com/seu-usuario/kontesuto-gadian.git

# Acesse a pasta do projeto
cd kontesuto-gadian

# Siga as instruções específicas de cada módulo (Spring, .NET, AI)
```

## 🤖 Inteligência Artificial

O sistema de IA foi construído com TensorFlow e PyTorch para oferecer recursos personalizados de aprendizagem, como envio de mensagens motivacionais, sugestões de estudo e acompanhamento de desempenho.

## 🧑‍💻 Autor

Feito por **Breno Gutierre**.

## 📄 Licença

Este projeto ainda não possui uma licença definida.


---

## 📁 Estrutura dos Setores e Menus

Mesmo que as páginas ainda estejam em construção, todas já estão acessíveis a partir do menu principal. Abaixo, segue a documentação de cada setor.

---

### 🏠 Página Inicial

**Motivação:** Receber o usuário com uma mensagem motivacional e mostrar o propósito da plataforma.

**Tecnologias:** React, Tailwind CSS

**Alterações Implementadas:**
- Layout com imagem temática e botão CTA
- Design responsivo e acessível

**Justificativa:** Engajamento inicial e boa primeira impressão

**Status:** Pronta

---

### 🎓 Dashboard do Aluno

**Motivação:** Acompanhar progresso, simulados e desempenho do aluno.

**Tecnologias:** React, Tailwind CSS

**Alterações Implementadas:** (em breve)

**Justificativa:** Permitir que o aluno acompanhe seus estudos de forma clara

**Status:** Em desenvolvimento

---

### 🛠️ Dashboard do Administrador

**Motivação:** Gerenciar conteúdos, usuários e resultados da plataforma.

**Tecnologias:** React, Tailwind CSS

**Alterações Implementadas:** (em breve)

**Justificativa:** Controle completo do ambiente da plataforma

**Status:** Em desenvolvimento

---

### 📝 Área de Simulados

**Motivação:** Disponibilizar simulados prontos com correção automática.

**Tecnologias:** React, React Router

**Alterações Implementadas:** (em breve)

**Justificativa:** Oferecer prática realista para o aluno

**Status:** Em desenvolvimento

---

### 📚 Banco de Questões

**Motivação:** Acesso a todas as questões organizadas por assunto e dificuldade.

**Tecnologias:** React, Tailwind CSS

**Alterações Implementadas:** (em breve)

**Justificativa:** Base de dados ampla e reutilizável para montagem de simulados

**Status:** Em desenvolvimento

---

### 📈 Relatórios e Desempenho

**Motivação:** Visualização de estatísticas e progresso por parte do aluno e do administrador.

**Tecnologias:** React, chart.js ou Recharts (proposto)

**Alterações Implementadas:** (em breve)

**Justificativa:** Feedback visual e estatístico da performance

**Status:** Em desenvolvimento

---

### ⚙️ Configurações

**Motivação:** Ajustes de perfil, preferências de tema, notificações etc.

**Tecnologias:** React

**Alterações Implementadas:** (em breve)

**Justificativa:** Permitir personalização do ambiente

**Status:** Em desenvolvimento

---

### 💬 Suporte

**Motivação:** Canal de contato com a equipe de suporte técnico ou pedagógico.

**Tecnologias:** React + formulário ou integração com ferramenta externa

**Alterações Implementadas:** (em breve)

**Justificativa:** Garantir suporte contínuo ao usuário

**Status:** Em desenvolvimento

---

## 📬 Página de Contato

A página de contato permite que o usuário entre em comunicação com a equipe de suporte para dúvidas, solicitações ou reclamações.

### 🎯 Objetivo

Fornecer uma interface simples e acessível para contato direto com a equipe do Kontesuto Gādian.

### 🧩 Funcionalidades

- Formulário de envio de mensagens por email
- Botão para atendimento via WhatsApp

### ✉️ Opção 1: Formulário com envio por Email

- **Tecnologia utilizada:** [EmailJS](https://www.emailjs.com/)
- **Campos:** Nome, Email, Mensagem
- **Integração:** Sem necessidade de backend, usando o serviço de envio direto do EmailJS
- **Validações:** Campos obrigatórios e email válido

### 💬 Opção 2: Link direto para WhatsApp

- Abre uma nova aba com link `https://wa.me/55SEUNUMERO`
- Pré-preenche uma mensagem automática

### 🔗 Rota do Sistema

- Rota: `/contato`
- Menu: item "Contato" adicionado ao menu principal de navegação

### 📝 Status

- Página em desenvolvimento funcional, acessível via menu.
- HTML e integração com EmailJS/WhatsApp testadas com sucesso.
