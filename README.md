# Sistema de Resolução de Chamados com IA



<details> <summary><strong>## Descrição do Desafio</strong></summary>

Muitas empresas enfrentam atrasos e baixa eficiência no atendimento dos chamados técnicos, o que gera insatisfação dos clientes e retrabalho para a equipe de suporte. Nosso sistema visa resolver esses problemas usando Inteligência Artificial para automatizar a triagem e resolução dos chamados, reduzindo tempo e esforço humano.
</details>


<details> <summary><strong>## Backlog de Produto</strong></summary>

| ID | História de Usuário                                  | Prioridade | Status    |
|-----|----------------------------------------------------|------------|-----------|
| 1   | Como usuário, quero abrir um chamado para relatar um problema. | Alta       | Em andamento |
| 2   | Como sistema, quero classificar automaticamente os chamados usando IA. | Alta       | Pendente  |
| 3   | Como usuário, quero receber notificações do status do meu chamado. | Média      | Pendente  |
| 4   | Como suporte, quero visualizar chamados que não foram resolvidos automaticamente. | Média      | Pendente  |
| 5   | Como administrador, quero gerar relatórios de chamados e desempenho da IA. | Baixa      | Pendente  |
</details>


<details> <summary><strong>## Cronograma de Evolução do Projeto (Visual)</strong></summary>

| Sprint | Período       | Link Documentação do Sprint | Link Vídeo do Incremento  |
|--------|---------------|-----------------------------|--------------------------|
| Sprint 1 | 01/11/2025 - 14/11/2025 | [Doc Sprint 1](https://github.com/seu-usuario/projeto-chamados-ia/docs/sprint1.md) | [YouTube Sprint 1](https://youtu.be/exemplo1) |
| Sprint 2 | 15/11/2025 - 28/11/2025 | [Doc Sprint 2](https://github.com/seu-usuario/projeto-chamados-ia/docs/sprint2.md) | [YouTube Sprint 2](https://youtu.be/exemplo2) |
| Sprint 3 | 29/11/2025 - 12/12/2025 | [Doc Sprint 3](https://github.com/seu-usuario/projeto-chamados-ia/docs/sprint3.md) | [YouTube Sprint 3](https://youtu.be/exemplo3) |
</details>


<details> <summary><strong>## Tecnologias Utilizadas</strong></summary>

- Python (para a IA)
- Node.js e Express (backend)
- React (frontend)
- MongoDB (banco de dados)
- Docker (containerização)
- Kubernetes (orquestração)
- GitHub Actions (CI/CD)
</details>


<details> <summary><strong>## Estrutura do Projeto</strong></summary>


/docs/ # Documentação do projeto, sprints, manuais e checklist
/backend/ # Código backend (Node.js e Express)
/frontend/ # Código frontend (React)
/ia/ # Algoritmos e modelos de IA (Python)
/scripts/ # Scripts auxiliares para deploy, migração, etc.
/.env.example # Exemplo de variáveis de ambiente
README.md # Documentação principal do projeto
</details>


<details> <summary><strong>## Como Executar, Usar e Testar o Projeto</strong></summary>

### Pré-requisitos

- Node.js instalado
- Python 3.8+ instalado
- MongoDB rodando localmente ou remotamente
- Docker instalado (opcional)

### Passos para execução local

<details> <summary><strong>1. Clone o repositório  </strong></summary>
   ```bash
   git clone https://github.com/seu-usuario/projeto-chamados-ia.git
   cd projeto-chamados-ia
  </details>
<details> <summary><strong>2. Configure as variáveis de ambiente</strong></summary>
   Copie o arquivo .env.example para .env e edite conforme necessário
</details>
<details> <summary><strong>3. Instale as dependências backend e frontend</strong></summary>
   cd backend
npm install
cd ../frontend
npm install
</details>
<details> <summary><strong>4. Execute o backend</strong></summary>
cd ../backend
npm start
</details>
<details> <summary><strong>5. Execute o frontend</strong></summary>
cd ../frontend
npm start
</details>
<details> <summary><strong>6. Execute a IA</strong></summary>
Na pasta /ia, execute o script principal para processar os chamados.

<details> <summary><strong>7. Executar Testes:</strong></summary>
cd backend
npm test

cd ../frontend
npm test
</details>
</details>
</details>
<details> <summary><strong>## Link para Pasta de Documentação</strong></summary>

Toda a documentação detalhada está na pasta /docs
, incluindo:

Documentação das sprints

Manual do usuário
</details>

<details>
<summary><strong>## Equipe</strong></summary>

| Nome Completo     | Papel                     | GitHub                                     | LinkedIn                                          |
| ----------------- | ------------------------- | ------------------------------------------ | ------------------------------------------------- |
| Gabriel Arantes   | Banco de Dados /Scrum Master / Product Owner  | [GitHub](https://github.com/gabrielarantes) | [LinkedIn](https://linkedin.com/in/gabrielarantes) |
| Wesley Martins    | Desenvolvedor Frontend    | [GitHub](https://github.com/wesleymartins)   | [LinkedIn](https://linkedin.com/in/wesleymartins)    |
| Gabriel Freitas   | Desenvolvedor Backend  | [GitHub](https://github.com/gabrielfreitas)  | [LinkedIn](https://linkedin.com/in/gabrielfreitas)   |

</details>


<details> <summary><strong>## Checklist de Definition of Ready (DoR) e Definition of Done (DoD)</strong></summary>

| Item                             | DoR (Pronto para iniciar) | DoD (Pronto para entregar) |
| -------------------------------- | ------------------------- | -------------------------- |
| Requisitos claros                | ✅                         | ✅                          |
| Critérios de aceitação definidos | ✅                         | ✅                          |
| Código revisado                  |                           | ✅                          |
| Testes automatizados             |                           | ✅                          |
| Documentação atualizada          |                           | ✅                          |
</details>
<details> <summary><strong>##Manual do Usuário</strong></summary>

Disponível no arquivo /docs/manual-usuario.md
, contendo:

Guia para abertura de chamados

Como acompanhar o status do chamado

Como interagir com a IA

Informações para contato com suporte humano

Desenvolvedor: Gabriel Arantes da Silva Soares
Email: gabrielarantes207@gmail.com
</details>
