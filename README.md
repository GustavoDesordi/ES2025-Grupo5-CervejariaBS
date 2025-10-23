# ES2025-Grupo5-CervejariaBS
Especificação de Sistema de Controle para a Cervejaria BeboSim - Projeto da Disciplina de Engenharia de Software.
# Alunos:
Gustavo Desordi;
Ariel Felipe Marques dos Santos.
# Cervejaria BeboSim – Sistema de Controle de Produção e Vendas

## 1. Introdução

### 1.1 Propósito  
Este documento apresenta a especificação do sistema de controle de produção e vendas da **Cervejaria BeboSim**.  
O sistema busca integrar os processos de produção, estoque, vendas e campanhas, substituindo controles manuais por uma solução web automatizada.

### 1.2 Escopo  
O sistema incluirá:  
- Cadastro de produtos, embalagens e unidades de produção  
- Gestão de equipes de vendas e vendedores  
- Registro de clientes corporativos e pedidos  
- Controle de campanhas promocionais  
- Geração de relatórios sobre desempenho e produtividade  

### 1.3 Termos e Siglas  

| Termo | Definição |
|--------|-----------|
| GCS | Gerenciamento de Configuração de Software |
| IEEE | Institute of Electrical and Electronics Engineers |
| PO | Product Owner |
| SM | Scrum Master |

---

## 2. Descrição Geral

### 2.1 Visão do Produto  
Aplicação web acessível por navegadores, voltada à administração centralizada de informações da empresa.  
Deve ser responsiva, segura e adaptável a diferentes perfis de usuário.

### 2.2 Funções Principais  
- Controle de produção e estoque  
- Emissão e acompanhamento de pedidos  
- Gestão de campanhas publicitárias  
- Relatórios de desempenho e indicadores  

### 2.3 Usuários  

| Perfil | Responsabilidade |
|---------|------------------|
| Administrador | Acesso total e relatórios gerais |
| Gerente de Produção | Controle de produtos e unidades |
| Gerente de Vendas | Supervisão de equipes e resultados |
| Vendedor | Registro de clientes e pedidos |

### 2.4 Restrições Técnicas  
- Sistema baseado em tecnologias web atuais  
- Controle de acesso por níveis de permissão  
- Armazenamento seguro e integridade dos dados  
- Compatibilidade com bancos de dados relacionais  

---

## 3. Requisitos  
Os requisitos serão descritos em formato de épicos e histórias de usuário.  

**Exemplo:**  
> Como gerente de vendas, desejo consultar relatórios semanais para acompanhar o desempenho da equipe.  
> Critério de aceite: o relatório deve exibir resultados por vendedor e total de vendas no período.

---

## 4. Arquitetura  
A arquitetura será documentada na Wiki do projeto.  

**Previsão de uso:**  
- Frontend: React ou Vue.js  
- Backend: Java Spring Boot ou Node.js  
- Banco de dados: MySQL ou PostgreSQL  
- Controle de versão: Git e GitHub  
- Integração contínua: GitHub Actions  

---

## 5. Gerenciamento de Configuração de Software  

- **Controle de Versão:** Git (repositório no GitHub)  
- **Branches:** main, develop, feature, release e hotfix  
- **Controle de Mudanças:** Commits vinculados a *issues* e revisões via *pull request*  
- **Integração Contínua:** Testes e builds automatizados a cada atualização  

---

## 6. Autores  

- Ariel Felipe Marques dos Santos – ariel1@unochapeco.edu.br 
- Gustavo Desordi - gustavo.desordi@unochapeco.edu.br


Professor responsável: **radames@unochapeco.edu.br**

---

## 7. Licença  
Este projeto está licenciado sob a **Licença MIT**.

---

## 8. Status  
Versão inicial em desenvolvimento.  
Próxima etapa: detalhamento dos requisitos e início da modelagem da aplicação.
