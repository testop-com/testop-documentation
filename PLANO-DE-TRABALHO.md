# Plano de Trabalho do Projeto de Avaliação do Sistema TES-TOP

## Análise e Documentação Interna do Sistema - Um Mês

---

**Título do Projeto:** Avaliação e Documentação do Sistema Interno TES-TOP  
**Duração:** 1 Mês (4 Semanas)  
**Data de Início:** 13 de Outubro de 2025  
**Data de Término:** 13 de Novembro de 2025  
**Preparado por:** [Seu Nome]  
**Data de Preparação:** 12 de Outubro de 2025

---

## Sumário Executivo

Este plano de trabalho delineia o compromisso abrangente de um mês para avaliar, analisar, compreender e avaliar o sistema interno TES-TOP. O projeto entregará quatro entregas principais fornecendo aos stakeholders insights acionáveis e recomendações para melhoria do sistema.

**⚠️ Nota Importante:** Este projeto será realizado em circunstâncias desafiantes, nomeadamente a **ausência de documentação técnica existente** e a **indisponibilidade da equipa de desenvolvimento original** para colaboração. A abordagem de avaliação foi adaptada para ser independente, utilizando engenharia reversa, análise de código-fonte e pesquisa intensiva com utilizadores para reconstruir o conhecimento do sistema.

---

## Contexto e Restrições do Projeto

### Situação Atual

**Restrições Identificadas:**

1. **Ausência de Documentação Técnica**

   - O sistema TES-TOP não possui documentação técnica formal
   - Não existem diagramas de arquitetura, manuais técnicos ou guias de desenvolvimento
   - A documentação de código-fonte é limitada ou inexistente
   - Não há histórico documentado de decisões de design ou arquitetura

2. **Indisponibilidade da Equipa de Desenvolvimento Original**

   - A equipa de desenvolvimento que criou o sistema não está disponível para colaboração
   - Existem conflitos entre a equipa de desenvolvimento e a empresa TES-TOP
   - Não será possível obter esclarecimentos diretos sobre decisões técnicas ou funcionamento interno
   - O conhecimento tácito sobre o sistema não está acessível

3. **Conhecimento Institucional Limitado**
   - O conhecimento sobre o sistema reside principalmente nos utilizadores finais
   - Pode haver funcionalidades não documentadas ou comportamentos não óbvios
   - Histórico de problemas e soluções pode estar disperso ou perdido

### Impacto nas Entregas

Estas restrições impactam significativamente a abordagem do projeto:

- **Maior tempo dedicado à engenharia reversa** do código e sistema
- **Dependência crítica de ferramentas de análise automática** de código
- **Ênfase aumentada na pesquisa com utilizadores** como fonte primária de conhecimento
- **Necessidade de reconstruir a documentação desde o zero** através de análise direta
- **Possíveis lacunas no conhecimento técnico** que precisarão ser documentadas como áreas de risco

### Abordagem Adaptada

Para mitigar estas restrições, o projeto adotará:

1. **Análise Forense de Código**

   - Uso extensivo de ferramentas de análise estática de código
   - Mapeamento sistemático de dependências e fluxos de dados
   - Identificação de padrões arquiteturais através do código

2. **Engenharia Reversa Estruturada**

   - Reconstrução de diagramas de arquitetura através da análise do código
   - Documentação de APIs através de inspeção de rotas e controllers
   - Mapeamento de esquema de base de dados através de migrations e models

3. **Pesquisa Intensiva com Utilizadores**

   - Maior número de entrevistas para compensar falta de documentação técnica
   - Foco em capturar conhecimento tácito e casos de uso não documentados
   - Mapeamento de fluxos de trabalho através da experiência do utilizador

4. **Análise de Histórico de Sistema**
   - Revisão de logs de sistema e histórico de tickets de suporte
   - Análise de histórico de commits no repositório de código
   - Identificação de padrões de uso através de dados de analytics (se disponíveis)

---

## Objetivos do Projeto

1. **Avaliação Abrangente do Sistema:** Conduzir uma análise técnica completa da arquitetura atual do sistema, código-fonte e infraestrutura
2. **Análise das Necessidades dos Utilizadores:** Compreender os pontos críticos dos utilizadores, requisitos e solicitações de funcionalidades em todos os departamentos
3. **Recomendações Estratégicas:** Fornecer recomendações acionáveis para melhorias e aprimoramentos do sistema
4. **Documentação Completa:** Entregar documentação profissional adequada para equipas técnicas, gestão e stakeholders

---

## Entregas Principais

### 1. Relatório Final de Avaliação

**Descrição:** Relatório abrangente do projeto consolidando todas as descobertas, análises e recomendações  
**Formato:** Documento de relatório profissional  
**Público-Alvo:** Liderança executiva, gestão e todos os stakeholders  
**Conteúdo Principal:**

- Resumo executivo com descobertas-chave
- Resultados detalhados da avaliação do sistema
- Resumo das necessidades dos utilizadores
- Recomendações priorizadas
- Roteiro de implementação
- Estimativas de orçamento e projeções de ROI

**Data de Entrega:** Semana 4, Dia 8 (13 de Novembro de 2025)

---

### 2. Documentação Técnica do Sistema

**Descrição:** Documentação técnica completa da arquitetura do sistema TES-TOP, código-fonte e infraestrutura  
**Formato:** Documentação técnica com diagramas e referências de código  
**Público-Alvo:** Equipa de desenvolvimento, equipa de TI, stakeholders técnicos  
**Conteúdo Principal:**

- Visão geral da arquitetura do sistema
- Análise da pilha tecnológica
- Documentação do esquema da base de dados
- Documentação de API
- Estrutura de código e módulos principais
- Avaliação de segurança
- Análise de desempenho
- Avaliação da dívida técnica

**Data de Entrega:** Semana 3, Dia 5 (6 de Novembro de 2025)

---

### 3. Documento de Especificação de Necessidades dos Utilizadores

**Descrição:** Análise detalhada dos requisitos dos utilizadores, pontos críticos e solicitações de funcionalidades  
**Formato:** Relatório de pesquisa do utilizador com recomendações  
**Público-Alvo:** Gestores de produto, analistas de negócios, equipa de desenvolvimento  
**Conteúdo Principal:**

- Demografia e perfis dos utilizadores
- Padrões de uso atuais
- Pontos críticos e problemas (priorizados)
- Solicitações de funcionalidades e melhorias
- Mapas de jornada do utilizador
- Descobertas de usabilidade
- Recomendações priorizadas

**Data de Entrega:** Semana 3, Dia 3 (4 de Novembro de 2025)

---

### 4. Termos de Referência (ToR)

**Descrição:** Carta de projeto e estrutura de iniciativa de melhoria  
**Formato:** Documento de planeamento estratégico  
**Público-Alvo:** Patrocinadores do projeto, comité de direção, gestores de projeto  
**Conteúdo Principal:**

- Âmbito e objetivos do projeto
- Análise de stakeholders
- Papéis e responsabilidades
- Critérios de sucesso e KPIs
- Avaliação de riscos
- Estrutura de governança
- Requisitos de recursos
- Fases de implementação

**Data de Entrega:** Semana 4, Dia 3 (11 de Novembro de 2025)

---

## Stakeholders do Projeto

### Stakeholders Principais

#### 1. Patrocinador Executivo

- **Papel:** Aprovação geral do projeto e direção estratégica
- **Envolvimento:** Atualizações de status semanais, apresentação final
- **Revisão de Entregas:** Relatório Final de Avaliação, Termos de Referência

#### 2. Diretor de TI/CTO

- **Papel:** Supervisão técnica e coordenação de recursos
- **Envolvimento:** Check-ins quinzenais, revisões técnicas
- **Revisão de Entregas:** Documentação Técnica do Sistema, Relatório Final de Avaliação

#### 3. Líderes de Unidades de Negócio

- **Papel:** Requisitos de negócio e entrada de necessidades dos utilizadores
- **Envolvimento:** Entrevistas da Semana 2, sessões de feedback
- **Revisão de Entregas:** Especificação de Necessidades dos Utilizadores, Relatório Final de Avaliação

#### 4. Utilizadores do Sistema (Todos os Departamentos)

- **Papel:** Fornecer feedback sobre o uso atual do sistema e necessidades
- **Envolvimento:** Entrevistas e inquéritos da Semana 2
- **Revisão de Entregas:** Resumo da Especificação de Necessidades dos Utilizadores

#### 5. Administrador de Sistemas / Equipa de TI Interna

- **Papel:** Fornecimento de acesso técnico ao sistema e infraestrutura
- **Envolvimento:** Configuração de acessos na Semana 1, suporte técnico conforme necessário
- **Revisão de Entregas:** Documentação Técnica do Sistema (validação de infraestrutura)

**⚠️ Nota:** A equipa de desenvolvimento original não está disponível para colaboração devido a conflitos existentes. O projeto prosseguirá de forma independente utilizando engenharia reversa e análise direta do código-fonte.

---

### Ponto Focal / Coordenador do Projeto

**Contacto Principal:** [Nome]  
**Título:** [Título]  
**Departamento:** [Departamento]  
**Responsabilidades:**

- Coordenar reuniões de stakeholders e entrevistas
- Fornecer acesso ao sistema e credenciais
- Facilitar comunicação com membros da equipa
- Rever rascunhos das entregas
- Coordenar apresentação final

**Informações de Contacto:**

- Email: [email@example.com]
- Telefone: [Número de Telefone]
- Escritório: [Localização]

---

## Stakeholders a Serem Contactados

### Semana 1: Contactos Iniciais

- [ ] Diretor de TI/CTO - Acesso ao sistema e briefing técnico
- [ ] Coordenador do Projeto - Logística e agendamento
- [ ] Administrador de Sistemas - Acesso ao sistema, base de dados e infraestrutura
- [ ] Equipa de TI Interna - Configuração de acessos e ambientes
- [ ] Responsável por Suporte Técnico - Histórico de problemas e tickets

**Nota:** Equipa de desenvolvimento original não disponível - análise será baseada em código-fonte e engenharia reversa.

### Semana 2: Entrevistas com Utilizadores (Sessões Agendadas)

- [ ] Chefe de Departamento - Administração
- [ ] Chefe de Departamento - Finanças
- [ ] Chefe de Departamento - Operações
- [ ] Chefe de Departamento - RH
- [ ] Utilizadores Avançados (3-5 por departamento)
- [ ] Utilizadores Finais (2-3 por departamento)
- [ ] Equipa de Suporte/Help Desk

### Semana 3: Contactos de Validação

- [ ] Diretor de TI - Revisão da documentação técnica
- [ ] Líderes de Unidades de Negócio - Validação das necessidades dos utilizadores
- [ ] Patrocinador do Projeto - Atualização de progresso

### Semana 4: Revisão Final

- [ ] Todos os Stakeholders Principais - Apresentação final
- [ ] Patrocinador Executivo - Aprovação do relatório final

---

## Requisitos de Recursos

### Acesso e Permissões

#### Acesso ao Sistema

- [ ] **Acesso ao Ambiente de Produção** (Somente leitura)

  - Propósito: Exploração e teste do sistema
  - Necessário até: Semana 1, Dia 1

- [ ] **Acesso ao Ambiente de Desenvolvimento** (Acesso completo)

  - Propósito: Revisão de código e análise técnica
  - Necessário até: Semana 1, Dia 1

- [ ] **Acesso à Base de Dados** (Somente leitura)

  - Propósito: Análise de esquema e revisão de estrutura de dados
  - Necessário até: Semana 1, Dia 2

- [ ] **Acesso ao Repositório de Controlo de Versão** (Somente leitura)

  - Propósito: Revisão de código e análise do histórico de commits
  - Necessário até: Semana 1, Dia 1

- [ ] **Repositório de Documentação**
  - Propósito: Revisão da documentação existente
  - Necessário até: Semana 1, Dia 1

#### Ferramentas e Software

- [ ] Acesso a ferramentas de monitorização/análise do sistema
- [ ] Acesso ao sistema de rastreamento de bugs
- [ ] Acesso a ferramentas de gestão de projetos
- [ ] Ferramentas de teste de API (Postman, Insomnia, etc.)
- [ ] Ferramentas de gestão de base de dados
- [ ] Ferramentas de perfilamento de desempenho

---

### Recursos Humanos

#### Da Equipa TES-TOP

- **Administrador de Sistemas / TI:** 8-12 horas total

  - Semana 1: Configuração de acessos e visão geral da infraestrutura (4-6 horas)
  - Semana 2-3: Suporte técnico e esclarecimentos conforme necessário (4-6 horas)

- **Responsável por Suporte Técnico:** 3-5 horas

  - Semana 1: Partilha de histórico de tickets e problemas comuns (2-3 horas)
  - Semana 2: Acompanhamento e esclarecimentos (1-2 horas)

- **Coordenador do Projeto:** 25-35 horas total

  - Contínuo: Coordenação de reuniões, ligação com stakeholders, facilitação de acessos

- **Utilizadores do Sistema:** 40-50 horas total (entre todos os utilizadores)
  - Semana 2: Entrevistas com utilizadores (30-40 horas) - **aumentado devido à falta de documentação**
  - Semana 3: Sessões de acompanhamento e validação (10 horas)

**⚠️ Nota Importante:** O tempo de utilizadores é maior do que o normal devido à ausência de documentação técnica e indisponibilidade da equipa de desenvolvimento. Os utilizadores serão a fonte primária de conhecimento sobre funcionalidades e comportamentos do sistema.

#### Recursos de Consultoria (Sua Equipa)

- **Consultor/Analista Principal:** Tempo integral (160 horas)
  - Avaliação do sistema
  - Criação de documentação
  - Envolvimento de stakeholders
  - Redação de relatórios

---

### Documentação e Materiais

#### A Ser Fornecido pela TES-TOP

**⚠️ Documentação Inexistente:** O sistema não possui documentação técnica formal. Os itens abaixo representam informações que, se existirem, serão úteis:

- [ ] ❌ Documentação técnica do sistema (**NÃO EXISTE**)
- [ ] ❌ Diagramas de arquitetura (**NÃO EXISTE**)
- [ ] ❌ Documentação do esquema da base de dados (**NÃO EXISTE**)
- [ ] ❌ Manuais técnicos ou guias de desenvolvimento (**NÃO EXISTE**)
- [ ] Manuais do utilizador ou materiais de formação (se existirem)
- [ ] Histórico de tickets de suporte (últimos 6-12 meses) - **CRÍTICO**
- [ ] Logs de sistema e registos de erros - **CRÍTICO**
- [ ] Métricas de desempenho do sistema (se disponíveis)
- [ ] Informações de licenças de software utilizadas
- [ ] Histórico de commits do repositório de código - **CRÍTICO**
- [ ] Credenciais e acessos aos ambientes (produção, staging, desenvolvimento)
- [ ] Informações sobre integrações externas (se existirem)
- [ ] Backups da base de dados para análise

**Prioridades:** Dado que não existe documentação, o foco será em obter acesso ao código-fonte, base de dados, logs de sistema e histórico de tickets de suporte.

#### A Ser Criado pelo Consultor

- [ ] Modelos de avaliação técnica
- [ ] Guias de entrevista
- [ ] Formulários de inquérito
- [ ] Estruturas de análise
- [ ] Todas as quatro entregas principais

---

### Requisitos de Infraestrutura

- [ ] **Espaço de Trabalho:** Espaço de trabalho dedicado ou mesa partilhada no escritório TES-TOP (se presencial)
- [ ] **Acesso à Rede:** Acesso à rede corporativa com VPN (se remoto)
- [ ] **Ferramentas de Comunicação:** Acesso a plataformas de comunicação interna (Teams, Slack, etc.)
- [ ] **Salas de Reunião:** Salas de conferência para entrevistas (Semana 2)
- [ ] **Hardware:** Computador com especificações necessárias para executar ambiente de desenvolvimento
- [ ] **Credenciais:** Conta de email para comunicação interna (opcional)

---

## Divisão Semanal

### **Semana 1: Descoberta e Familiarização com o Sistema**

**Datas:** 13-19 de Outubro de 2025  
**Tema:** Compreender o Estado Atual

#### Objetivos

- Estabelecer fundação do projeto e acesso
- Compreender arquitetura do sistema e pilha tecnológica
- Iniciar revisão inicial de código e infraestrutura
- Configurar estrutura de documentação

#### Atividades Diárias

**Dia 1 (Segunda-feira) - Início do Projeto e Configuração de Acessos**

- 9:00: Reunião de início com Patrocinador do Projeto e Diretor de TI
- 10:00: Reunião com Administrador de Sistemas - obtenção de acessos técnicos
- 11:00: Configuração de ambientes (desenvolvimento, staging, acesso à produção)
- 13:00: Clone do repositório de código-fonte e configuração local
- 15:00: Exploração inicial do sistema como utilizador
- 16:00: Revisão de histórico de tickets de suporte disponíveis
- **Entrega:** Notas do início do projeto, checklist de acesso concluída
- **Desafio:** Sem documentação ou briefing técnico disponível - início por engenharia reversa

**Dia 2 (Terça-feira) - Análise Forense do Código**

- 9:00: Análise da estrutura de diretórios e organização do código
- 10:00: Identificação da pilha tecnológica através de ficheiros de configuração
- 11:00: Inspeção direta do esquema da base de dados
- 13:00: Exploração do repositório de código e histórico de commits
- 15:00: Documentação inicial da pilha tecnológica identificada
- 16:00: Identificação de dependências e bibliotecas utilizadas
- **Entrega:** Documentação inicial da pilha tecnológica (reconstruída através de análise)

**Dia 3 (Quarta-feira) - Engenharia Reversa da Arquitetura**

- 9:00: Mapeamento de fluxos de dados através do código
- 11:00: Documentação de rotas e endpoints de API (através de inspeção de código)
- 13:00: Reconstrução do esquema da base de dados e relacionamentos
- 15:00: Identificação de padrões arquiteturais utilizados
- 16:00: Avaliação da infraestrutura através de configurações
- **Entrega:** Rascunho de visão geral da arquitetura (reconstruída)

**Dia 4 (Quinta-feira) - Análise Profunda do Código**

- 9:00: Revisão detalhada de módulos principais e controllers
- 10:30: Análise de models e lógica de negócio
- 11:30: Identificação de áreas de dívida técnica através de code smells
- 13:00: Análise de segurança (configurações, autenticação, autorização)
- 15:00: Configuração de ferramentas de análise estática de código
- 16:00: Execução de análise automática de código
- **Entrega:** Checklist de revisão de código, relatório de análise estática

**Dia 5 (Sexta-feira) - Consolidação e Planeamento**

- 9:00: Análise de resultados de ferramentas automáticas
- 10:30: Compilação de descobertas técnicas da Semana 1
- 11:30: Identificação de lacunas de conhecimento para pesquisa com utilizadores
- 13:00: Preparação de guia de entrevista adaptado (foco em funcionalidades não documentadas)
- 14:00: Agendamento detalhado de entrevistas para Semana 2
- 15:00: Atualização de status semanal com Ponto Focal
- **Entregas:** Relatório resumido da Semana 1, guia de entrevista, lista de lacunas identificadas

#### Marcos da Semana 1

- ✅ Acesso ao sistema estabelecido
- ✅ Ambiente de desenvolvimento configurado
- ✅ Avaliação técnica inicial concluída (30%)
- ✅ Agendamento de entrevistas confirmado para Semana 2
- ✅ Estrutura de documentação estabelecida

#### Envolvimento de Stakeholders

- Patrocinador do Projeto: Reunião de início
- Diretor de TI: Briefing sobre contexto e restrições do projeto
- Administrador de Sistemas: Configuração de acessos e suporte técnico
- Coordenador do Projeto: Coordenação diária e facilitação de acessos
- **Nota:** Equipa de desenvolvimento original não envolvida - trabalho independente

---

### **Semana 2: Análise Profunda e Pesquisa com Utilizadores**

**Datas:** 20-26 de Outubro de 2025  
**Tema:** Compreender Utilizadores e Detalhes Técnicos

#### Objetivos

- Completar avaliação técnica abrangente
- Conduzir entrevistas com utilizadores em todos os departamentos
- Identificar pontos críticos e necessidades dos utilizadores
- Analisar desempenho e segurança do sistema

#### Atividades Diárias

**Dia 1 (Segunda-feira) - Análise Técnica Profunda**

- 9:00: Completar revisão de código (autenticação e autorização)
- 11:00: Avaliação de segurança de API
- 13:00: Análise de otimização da base de dados
- 15:00: Benchmarking de desempenho
- **Entrega:** Descobertas de avaliação de segurança

**Dia 2 (Terça-feira) - Início das Entrevistas com Utilizadores**

- 9:00: Entrevista Chefe de Departamento - Administração
- 10:30: Entrevista Utilizadores Avançados - Administração (2 utilizadores)
- 13:00: Entrevista Chefe de Departamento - Finanças
- 14:30: Entrevista Utilizadores Avançados - Finanças (2 utilizadores)
- 16:00: Compilar notas de entrevistas
- **Entrega:** Notas de entrevistas, lista inicial de pontos críticos

**Dia 3 (Quarta-feira) - Continuação das Entrevistas com Utilizadores**

- 9:00: Entrevista Chefe de Departamento - Operações
- 10:30: Entrevista Utilizadores Avançados - Operações (2 utilizadores)
- 13:00: Entrevista Chefe de Departamento - RH
- 14:30: Entrevista Utilizadores Avançados - RH (2 utilizadores)
- 16:00: Compilar notas de entrevistas
- **Entrega:** Notas abrangentes de entrevistas

**Dia 4 (Quinta-feira) - Entrevistas Adicionais e Análise**

- 9:00: Entrevista Utilizadores Finais (múltiplos departamentos, 3-4 utilizadores)
- 11:00: Entrevista Equipa de Suporte/Help Desk
- 13:00: Documentação de dívida técnica
- 15:00: Iniciar estrutura de análise SWOT
- **Entrega:** Notas completas de entrevistas, registo de dívida técnica

**Dia 5 (Sexta-feira) - Síntese da Semana 2**

- 9:00: Analisar todos os dados de entrevistas
- 11:00: Categorizar necessidades dos utilizadores e pontos críticos
- 13:00: Resumo de avaliação técnica
- 15:00: Atualização de status semanal com Diretor de TI
- **Entregas:** Resumo da Semana 2, relatório preliminar de necessidades dos utilizadores, avaliação técnica 70% concluída

#### Marcos da Semana 2

- ✅ Entrevistas com utilizadores concluídas (15-20 utilizadores)
- ✅ Avaliação técnica concluída (80%)
- ✅ Pontos críticos identificados e categorizados
- ✅ Análise de segurança e desempenho concluída
- ✅ Análise preliminar de necessidades dos utilizadores concluída

#### Envolvimento de Stakeholders

- Todos os Chefes de Departamento: Entrevistas individuais
- Utilizadores Avançados em todos os departamentos: Entrevistas em grupo e individuais
- Utilizadores Finais: Entrevistas individuais
- Diretor de TI: Atualização de progresso
- Equipa de Suporte: Entrevista sobre problemas do sistema

---

### **Semana 3: Documentação e Análise Estratégica**

**Datas:** 27 de Outubro - 2 de Novembro de 2025  
**Tema:** Criar Entregas e Planeamento Estratégico

#### Objetivos

- Criar Documentação Técnica do Sistema
- Finalizar Especificação de Necessidades dos Utilizadores
- Conduzir análise SWOT
- Desenvolver recomendações iniciais
- Iniciar Termos de Referência

#### Atividades Diárias

**Dia 1 (Segunda-feira) - Documentação Técnica**

- 9:00: Iniciar redação da Documentação Técnica do Sistema
- 11:00: Criação de diagramas de arquitetura
- 13:00: Documentação do esquema da base de dados
- 15:00: Documentação de API
- **Entrega:** Documentação Técnica 40% concluída

**Dia 2 (Terça-feira) - Continuação da Documentação Técnica**

- 9:00: Documentação da estrutura de código
- 11:00: Documentação das descobertas de segurança
- 13:00: Documentação da análise de desempenho
- 15:00: Seção de recomendações técnicas
- **Entrega:** Documentação Técnica 80% concluída

**Dia 3 (Quarta-feira) - Especificação de Necessidades dos Utilizadores**

- 9:00: Finalizar seção de demografia dos utilizadores
- 10:30: Documentar padrões de uso
- 13:00: Priorizar pontos críticos
- 15:00: Análise de solicitações de funcionalidades
- 16:30: Completar Especificação de Necessidades dos Utilizadores
- **Entrega:** ✅ **Documento de Especificação de Necessidades dos Utilizadores (Entrega #3)**

**Dia 4 (Quinta-feira) - Análise SWOT**

- 9:00: Análise SWOT - Forças
- 10:30: Análise SWOT - Fraquezas
- 13:00: Análise SWOT - Oportunidades
- 14:30: Análise SWOT - Ameaças
- 16:00: Recomendações estratégicas SWOT
- **Entrega:** Documento completo de Análise SWOT

**Dia 5 (Sexta-feira) - Finalizar Documentação Técnica**

- 9:00: Revisão e polimento da Documentação Técnica
- 11:00: Sessão de validação com Líder da Equipa de Desenvolvimento
- 13:00: Incorporar feedback técnico
- 15:00: Finalizar Documentação Técnica
- 16:00: Atualização de status semanal
- **Entrega:** ✅ **Documentação Técnica do Sistema (Entrega #2)**

#### Marcos da Semana 3

- ✅ Documentação Técnica do Sistema concluída
- ✅ Especificação de Necessidades dos Utilizadores concluída
- ✅ Análise SWOT concluída
- ✅ Validação técnica concluída
- ✅ Estrutura de recomendações iniciais estabelecida

#### Envolvimento de Stakeholders

- Líder da Equipa de Desenvolvimento: Revisão da documentação técnica
- Diretor de TI: Atualização de progresso
- Líderes de Unidades de Negócio: Validação das necessidades dos utilizadores (reuniões breves)

---

### **Semana 4: Relatório Final, ToR e Encerramento do Projeto**

**Datas:** 3-13 de Novembro de 2025  
**Tema:** Síntese, Recomendações e Transição

#### Objetivos

- Completar Termos de Referência
- Criar Relatório Final de Avaliação abrangente
- Desenvolver roteiro de implementação
- Apresentar descobertas aos stakeholders
- Transição do projeto

#### Atividades Diárias

**Dia 1 (Segunda-feira) - Termos de Referência**

- 9:00: Documentação do âmbito do projeto
- 11:00: Análise de stakeholders
- 13:00: Definição de papéis e responsabilidades
- 15:00: Estrutura de governança
- **Entrega:** Termos de Referência 60% concluídos

**Dia 2 (Terça-feira) - Continuação do ToR**

- 9:00: Critérios de sucesso e KPIs
- 11:00: Avaliação de riscos
- 13:00: Requisitos de recursos
- 15:00: Esboço das fases de implementação
- **Entrega:** Termos de Referência 90% concluídos

**Dia 3 (Quarta-feira) - Finalizar ToR**

- 9:00: Revisão e polimento dos Termos de Referência
- 11:00: Estimativas de orçamento
- 13:00: Projeções de cronograma
- 15:00: Finalizar Termos de Referência
- **Entrega:** ✅ **Termos de Referência (Entrega #4)**

**Dia 4 (Quinta-feira) - Criação do Relatório Final**

- 9:00: Redação do Resumo Executivo
- 10:30: Consolidar todas as descobertas
- 13:00: Priorização de recomendações
- 15:00: Roteiro de implementação
- **Entrega:** Relatório Final 60% concluído

**Dia 5 (Sexta-feira) - Conclusão do Relatório Final**

- 9:00: Completar Relatório Final de Avaliação
- 11:00: Projeções de orçamento e ROI
- 13:00: Polir e formatar todos os documentos
- 15:00: Revisão do relatório final
- **Entrega:** Relatório Final 100% concluído

**Dia 6 (Segunda-feira) - Revisão de Qualidade**

- 9:00: Revisar todas as quatro entregas
- 11:00: Garantir consistência entre documentos
- 13:00: Preparar materiais de apresentação
- 15:00: Criar deck de resumo executivo
- **Entrega:** Materiais de apresentação, deck executivo

**Dia 7 (Terça-feira) - Apresentação aos Stakeholders**

- 9:00: Preparações finais
- 10:00: **Apresentação à Equipa Executiva**
  - Resumo Executivo
  - Descobertas Principais
  - Recomendações Críticas
  - Roteiro de Implementação
  - Orçamento e ROI
- 13:00: Perguntas e discussão
- 15:00: Incorporação de feedback
- **Entrega:** Apresentação concluída, registo de feedback

**Dia 8 (Quarta-feira) - Encerramento do Projeto**

- 9:00: Incorporar feedback final
- 11:00: Finalizar todas as entregas
- 13:00: **Reunião Formal de Transição**
  - Entregar todas as quatro entregas principais
  - Documentação de transição
  - Discussão de próximos passos
- 15:00: Documentação de encerramento do projeto
- **Entrega:** ✅ **Relatório Final de Avaliação (Entrega #1)**, Todas as entregas formalmente entregues

#### Marcos da Semana 4

- ✅ Termos de Referência concluídos
- ✅ Relatório Final de Avaliação concluído
- ✅ Apresentação aos stakeholders concluída
- ✅ Todas as quatro entregas entregues
- ✅ Projeto formalmente encerrado

#### Envolvimento de Stakeholders

- Patrocinador Executivo: Apresentação final
- Todos os Stakeholders Principais: Apresentação final
- Diretor de TI: Reunião de transição
- Coordenador do Projeto: Encerramento do projeto

---

## Plano de Comunicação

### Atualizações de Status

**Diário:**

- Breve atualização por email ao Coordenador do Projeto
- Registo de problemas mantido

**Semanal:**

- Relatório de status ao Diretor de TI e Coordenador do Projeto
- Atualização de progresso no site de documentação GitHub Pages
- Email resumido aos stakeholders

**Ad-hoc:**

- Notificação imediata de descobertas críticas
- Problemas urgentes escalados aos stakeholders apropriados

### Cronograma de Reuniões

**Semana 1:**

- Dia 1: Início do Projeto (2 horas)
- Dia 2: Apresentação Técnica (2 horas)
- Dia 5: Atualização de Status Semanal (1 hora)

**Semana 2:**

- Dia 2-4: Entrevistas com Utilizadores (sessões agendadas)
- Dia 5: Atualização de Status Semanal (1 hora)

**Semana 3:**

- Dia 3: Revisão da Documentação Técnica (1 hora)
- Dia 5: Atualização de Status Semanal (1 hora)

**Semana 4:**

- Dia 7: Apresentação Final (3 horas)
- Dia 8: Reunião de Transição (2 horas)

---

## Gestão de Riscos

### Riscos Identificados e Estratégias de Mitigação

#### Risco 1: Atraso no Acesso ao Sistema

- **Impacto:** Alto - Pode atrasar todo o projeto
- **Probabilidade:** Média
- **Mitigação:** Solicitar acesso antecipadamente (Semana 0), caminho de escalação estabelecido
- **Contingência:** Focar na revisão de documentação e preparação de entrevistas se atrasado

#### Risco 2: Disponibilidade Limitada dos Stakeholders

- **Impacto:** Alto - Afeta qualidade da pesquisa do utilizador
- **Probabilidade:** Média
- **Mitigação:** Agendar entrevistas antecipadamente, agendamento flexível, múltiplas faixas horárias
- **Contingência:** Estender atividades da Semana 2 para a Semana 3 se necessário

#### Risco 3: Documentação Existente Insuficiente

- **Impacto:** Médio - Requer mais tempo de descoberta
- **Probabilidade:** Alta
- **Mitigação:** Alocar tempo extra para exploração do sistema, trabalhar em estreita colaboração com equipa de desenvolvimento
- **Contingência:** Ajustar cronograma da Semana 1, estender análise técnica

#### Risco 4: Complexidade Técnica Maior do que Esperado

- **Impacto:** Médio - Pode atrasar documentação técnica
- **Probabilidade:** Média
- **Mitigação:** Monitorização diária de progresso, identificação precoce de áreas complexas
- **Contingência:** Priorizar componentes críticos, adiar detalhes técnicos não críticos

#### Risco 5: Alargamento do Âmbito

- **Impacto:** Alto - Pode impedir entrega atempada
- **Probabilidade:** Média
- **Mitigação:** Definição clara de âmbito, processo de solicitação de mudanças, alinhamento regular com stakeholders
- **Contingência:** Documentar itens fora do âmbito para fases futuras

#### Risco 6: Lacunas de Conhecimento Críticas

- **Impacto:** Alto - Ausência de documentação pode deixar áreas técnicas não compreendidas
- **Probabilidade:** Alta
- **Mitigação:** 
  - Uso extensivo de ferramentas de análise automática
  - Pesquisa intensiva com utilizadores para capturar conhecimento tácito
  - Documentação explícita de áreas com lacunas de conhecimento
- **Contingência:** Identificar e documentar áreas que requerem atenção futura ou investigação adicional

#### Risco 7: Código Legado Sem Comentários ou Padrões

- **Impacto:** Médio - Dificulta compreensão e análise
- **Probabilidade:** Alta (sem documentação, provavelmente sem boas práticas de código)
- **Mitigação:**
  - Ferramentas de análise de complexidade de código
  - Tempo adicional para engenharia reversa
  - Validação de compreensão através de testes práticos
- **Contingência:** Priorizar documentação de componentes críticos, aceitar nível de detalhe limitado em componentes secundários

#### Risco 8: Informações Críticas Apenas na Memória da Equipa de Desenvolvimento

- **Impacto:** Alto - Conhecimento de decisões de design e comportamentos específicos pode estar perdido
- **Probabilidade:** Alta
- **Mitigação:**
  - Análise detalhada de histórico de commits e mensagens
  - Pesquisa com utilizadores de longa data para capturar conhecimento histórico
  - Análise de tickets de suporte para identificar comportamentos históricos
- **Contingência:** Documentar limitações conhecidas e recomendações para futura investigação

---

## Critérios de Sucesso

### Métricas de Sucesso do Projeto

1. **Conclusão das Entregas**

   - ✅ Todas as quatro entregas principais concluídas dentro do prazo
   - ✅ Todas as entregas atendem aos padrões de qualidade
   - ✅ Aprovação dos stakeholders recebida

2. **Envolvimento dos Stakeholders**

   - ✅ Mínimo de 15 entrevistas com utilizadores concluídas
   - ✅ Todos os stakeholders-chave envolvidos
   - ✅ Apresentação final entregue à equipa executiva

3. **Qualidade da Documentação**

   - ✅ Documentação técnica validada pela equipa de desenvolvimento
   - ✅ Necessidades dos utilizadores validadas pelas unidades de negócio
   - ✅ Recomendações acionáveis e priorizadas

4. **Gestão de Projeto**

   - ✅ Projeto concluído dentro do cronograma de um mês
   - ✅ Dentro do orçamento (se aplicável)
   - ✅ Sem problemas críticos ou escalações

5. **Valor Entregue**
   - ✅ Recomendações claras e acionáveis fornecidas
   - ✅ Projeções de ROI para melhorias identificadas
   - ✅ Roteiro de implementação aceite pelos stakeholders

---

## Considerações Orçamentárias

### Investimento de Tempo do Consultor

- **Total de Horas:** 160 horas (1 mês tempo integral)
- **Divisão:**
  - Semana 1: 40 horas - Descoberta e análise técnica
  - Semana 2: 40 horas - Pesquisa com utilizadores e revisão técnica profunda
  - Semana 3: 40 horas - Criação de documentação
  - Semana 4: 40 horas - Entregas finais e apresentação

### Custos de Recursos (TES-TOP)

- **Tempo de Pessoal:** ~60-80 horas entre todos os stakeholders
- **Infraestrutura:** Acesso ao sistema, ambiente de desenvolvimento
- **Espaços de Reunião:** Salas de conferência para entrevistas da Semana 2
- **Suporte Administrativo:** Tempo de coordenação do projeto

### Ferramentas e Software

- Ferramentas de desenvolvimento (se ainda não disponíveis)
- Ferramentas de documentação
- Software de apresentação
- Plataformas de colaboração

---

## Tabela Resumida de Entregas

| #   | Entrega                                            | Data de Entrega          | Público Principal         | Status      |
| --- | -------------------------------------------------- | ------------------------ | ------------------------- | ----------- |
| 1   | **Relatório Final de Avaliação**                   | Semana 4, Dia 8 (13 Nov) | Todos os Stakeholders     | 📋 Agendado |
| 2   | **Documentação Técnica do Sistema**                | Semana 3, Dia 5 (6 Nov)  | Equipa Técnica            | 📋 Agendado |
| 3   | **Especificação de Necessidades dos Utilizadores** | Semana 3, Dia 3 (4 Nov)  | Equipa de Produto/Negócio | 📋 Agendado |
| 4   | **Termos de Referência**                           | Semana 4, Dia 3 (11 Nov) | Patrocinadores do Projeto | 📋 Agendado |

### Entregas de Suporte

- Relatórios de status semanais (4 relatórios)
- Notas e análise de entrevistas
- Documento de Análise SWOT
- Materiais de apresentação
- Deck de resumo executivo
- Site de documentação GitHub Pages

---

## Atividades Pós-Projeto

### Transferência de Conhecimento

- Reunião de transição com Diretor de TI
- Sessão de perguntas e respostas com equipa de desenvolvimento
- Apresentação da documentação com coordenador do projeto

### Suporte de Acompanhamento

- Janela de 2 semanas para questões de esclarecimento
- Revisão do planeamento de implementação (opcional)
- Verificação de progresso aos 3 meses (opcional)

### Arquivo do Projeto

- Todos os ficheiros do projeto organizados e arquivados
- Site GitHub Pages mantido como referência
- Documentos de origem fornecidos à TES-TOP

---

## Apêndices

### Apêndice A: Modelos de Questões de Entrevista

[A ser desenvolvido na Semana 1]

### Apêndice B: Checklist de Avaliação Técnica

[A ser desenvolvido na Semana 1]

### Apêndice C: Modelos de Documentos

- Modelo de Relatório de Status
- Modelo de Notas de Entrevista
- Modelo de Descobertas Técnicas

### Apêndice D: Lista de Contactos

[A ser preenchida com informações de contacto reais]

---

## Controlo de Documentos

**Versão:** 1.0  
**Última Atualização:** 12 de Outubro de 2025  
**Próxima Revisão:** 13 de Outubro de 2025 (Início do Projeto)  
**Proprietário do Documento:** [Seu Nome]  
**Aprovador:** [Nome do Patrocinador do Projeto]

**Histórico de Alterações:**

| Versão | Data              | Autor      | Alterações                       |
| ------ | ----------------- | ---------- | -------------------------------- |
| 1.0    | 12 de Out de 2025 | [Seu Nome] | Plano de trabalho inicial criado |

---

**Fim do Documento**
