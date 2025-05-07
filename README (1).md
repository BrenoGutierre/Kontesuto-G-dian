
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
