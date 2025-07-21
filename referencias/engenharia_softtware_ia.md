# Fundamentos de IA Generativa

Introdução à IA Generativa

Conceitos e evolução histórica dos modelos generativos
Diferenças entre IA tradicional, estatística e generativa
Principais impactos no desenvolvimento de software e produtos
Icone

Modelos de Linguagem (LLMs)

O que são LLMs e como aprendem a gerar conteúdo
Diferença entre modelos generalistas, especializados e multimodais
Modelos open source: LLaMA, DeepSeek, Hugging Face
Execução local: Ollama, LM Studio e alternativas
Icone

Geração de Respostas

Tokens e tokenização
Processo de inferência e fluxo de geração
Temperatura, top-k, top-p e controle de saída
Janela de contexto e truncamento
Icone

Arquiteturas e Tipos de Modelos

Encoder-only, decoder-only e encoder-decoder
Modelos de texto, código, embeddings e multimodais
Comparação entre estilos e seus usos ideais
Icone

Embeddings e Representações Vetoriais

Representações numéricas e proximidade semântica
Embeddings vs geração
Casos de uso em busca, recomendação e organização de conteúdo
Icone

Estratégias de Uso

Prompt Engineering
RAG (Retrieval-Augmented Generation)
Fine-tuning

# Prompt Engineering
Fundamentos

Icone
A importância do Prompt Engineering no mundo do desenvolvimento

Icone
Zero-shot, few-shot, Chain of Thought (CoT), Self-consistency, Tree of Thought

Icone
Skeleton of Thought, ReAct e estratégias para raciocínio estruturado

Icone
Modularização de prompts para funções específicas

Icone
Prompt templates dinâmicos (com variáveis de entrada)

Icone
Sanitização e prevenção contra prompt injection

Icone
Validação de resposta com LLM secundário (auto-eval)

Icone
Versionamento de prompts e fallback

Icone

Template de prompts

Novas aplicações
Aplicações legadas
Documentação
Testes
Code Review e PRs
Mesa Redondas com Especialistas e Brainstorming

# Fundamentos Arquitetura e Software com IA
Arquitetura de Software e Solução na era da IA

O mundo da Arquitetura antes e depois da IA
O novo perfil de desenvolvedor
O novo papel do arquiteto
A nova geração de aplicações orientadas à IA
Icone

Agentes de IA e Protocolos de Comunicação

Software, Microservices vs Agentes de IA
Arquiteturas de Agentes de IA
Orquestração de Agentes
MCP (Model Context Protocol) e Meios de Transporte
A2A (Agent to Agent)
Iniciativas de novos protocolos
Evaluation
Icone

Design Patterns com IA

Design Patterns para desenvolvimento de sistemas e agentes
Design Patterns para segurança
12 Factors Agents
Icone

Caching

Conceitos básicos de caching
Formas de invalidação (TTL, Cache-aside, Write-through, etc)
Eviction Policies: LRU, LFU, FIFO, MRU, Random Replacement
Caching de Tokens em LLMs (OpenAI, Gemini, Claude)
Caching de contexto e embeddings em aplicações com RAG
Cache-aware prompts e uso de fingerprints para controle de resposta
Icone

Segurança

Jailbreaking
Prompt Injection
Guardrails
Proteção de dados sensíveis
OWASP Top 10 LLM e Gen AI
Icone

Context Engineering e Prompt Engineering

Prompt Engineering
Context Engineering para desenvolvimento de aplicações de grande porte
Versionamento de prompts e histórico de iterações
Icone

System Design e Sistemas distribuídos com IA

Princípios de System Design com IA
Escala: performance, custo e qualidade
Pipelines, mensageria e streaming
Banco de dados vetoriais (ex: Pinecone)
Compatibilidade entre versões de embeddings
Arquitetura RAG (Retrieval-Augmented Generation)
Cloud Providers e serviços-chave
Observabilidade
Icone

Testes e Qualidade em Sistemas com IA

Testes de prompts e contextos (Prompt Testing)
Avaliação de agentes com datasets reais e sintéticos
Snapshot testing para validação de respostas
Testes determinísticos e estratégias para LLMs não-determinísticos
Principais ferramentas (ex: LangSmith)
Icone

Controle de Custos em Arquiteturas com IA

Entendendo input tokens, output tokens e limites por modelo
Estratégias de caching para reduzir chamadas repetidas
Calculadoras e ferramentas de estimativa de custo
Logging e monitoramento do uso de IA (por usuário, prompt ou agente)
Otimização de prompts e truncamento inteligente
Escolha de modelos com base em custo x qualidade x latência

# Design Docs com IA
Fundamentos de Design Docs

Icone
Estruturação

Icone
Objetivos e Escopo

Icone
Ferramentas

Icone
Design Docs na era da IA

Icone
Documentação como Contexto

Icone

Formatos de documentação

Requisitos e Produto (PRD, TRD, FRD, User Stores e Epics)
Decisões técnicas (RFCs e Architecture Decision Record)
Engineering Guidelines (Workflow, Coding Standars, Code Review, PRs e Testing)
Design e Arquitetura (System Design, Low Level Design e C4 Model)
Operações (Runbook, Playbook, Postmortem)
Icone
Geração automatizada de documentações e criação de assistentes de IA

Icone
Referenciação e desabilitação de documentos

Icone
Manutenção e atualização de documentações com IA

# Desenvolvimento de Software com IA
Fundamentos do desenvolvimento IA Driven

Icone
Novas Aplicações vs Aplicações Existentes

Icone
Comparativo entre ferramentas: Cursor, Windsurf e Github Copilot

Icone
Biblioteca de prompts para desenvolvimento

Icone
Estruturação de documentação para Contexto

Icone
Geração de Rules e Memories

Icone
Testes automatizados e detecção de Edge Cases

Icone
Servidores MCPs para Desenvolvimento e Docker Catalog

Icone
Processos de debugging otimizados

Icone
Boas práticas de Refactoring

Icone
Análise automatizada de logs e debugging

Icone
Verificação de vulnerabilidades

# Desenvolvimento em modo Agente
Fundamentos do Desenvolvimento Agentico

Icone
Princípios, precauções e diferenças de Vibe Coding

Icone
Ferramentas, IDEs e o papel do Codex (OpenAI) e Claude Code

Icone
Principais modelos e seus casos de uso

Icone
Workflow: Desenvolvimento de novas aplicações vs Aplicações existentes

Icone
Rules para desenvolvimento Agentico

Icone
Exploração e Contextualização

Icone
Planos de Ação

Icone
Task Breakdown

Icone
Gerenciamento de estado

Icone
Prompts para desenvolvimento autônomo sem devolução de controle ao usuário

Icone
Verificação, Análise e Correção de discrepâncias

Icone
Criação e execução automatizada de testes

# Desenvolvimento de aplicações com IA

Integração com APIs e Modelos

Uso prático com OpenAI SDK
Autenticação, envio de mensagens e parâmetros principais
Limites de uso, tokens, retry e controle de erros
Logging básico e boas práticas de chamada
Icone

Introdução ao LangChain

O que é LangChain e quando usar
Criação de pipelines com LLMChain e PromptTemplate
Uso de SequentialChain para compor múltiplas etapas
Parsing estruturado de respostas com Output Parsers
Composição de múltiplos fluxos com RouterChain
Uso de memória com ConversationBufferMemory e VectorStoreRetrieverMemory
Icone

RAG: Retrieval-Augmented Generation

Estrutura do RAG: recuperação de conteúdo antes da geração da resposta
Implementação com LangChain: retriever, injeção de contexto e geração
Estratégias para dividir e preparar o conteúdo (chunking e organização semântica)
Uso de fontes externas como PDFs, Web Scraper e banco de dados vetoriais
Reordenação de trechos com base em relevância
Icone

Aplicações Multifuncionais com IA

Estrutura de aplicações que combinam diferentes funcionalidades de IA
Roteamento por intenção e controle de fluxo
Composição com LangChain para organizar múltiplos caminhos
Casos práticos: resumo, tradução, reescrita, explicação
Icone

Extração, Classificação e Análise de Texto

Criação de prompts para classificação e análise de sentimento
Extração de informações relevantes de textos livres
Como tornar as saídas previsíveis e utilizáveis
Estratégias básicas de validação de respostas

# Desenvolvimento de Agentes

Fundamentos de agentes

O que são agentes e suas características
Diferenças entre aplicações com IA e agentes autônomos
Ciclo de vida: objetivo, plano, execução, adaptação
Tipos de agentes: baseados em ferramenta, com memória, reflexivos
Icone

Coordenação e Estratégias de Execução

Tipos de coordenação: sequencial, condicional, paralela e cíclica
Controle de fluxo com validação, repetição e fallback
Integração de ferramentas externas durante a execução de agentes
Modelagem de tarefas compostas e divisão por subtarefas
Icone

Visão Geral de Frameworks

Estilos de agentes: stateful, conversacional, por papéis e com planejamento
Comparativo conceitual entre LangChain, LangGraph, CrewIA e ADK
Demonstrações práticas de cada ferramenta
Abordagens de escolha de cada framework baseado em casos de uso
Icone

Desenvolvimento com ADK (Agent Development Kit da Google)

Estrutura modular e organização por subagentes
Criação visual de fluxos com ações e decisões
Controle de execução com repetição e validação
Integração de ferramentas externas
Observabilidade integrada com painel do ADK
Visualização de execução em tempo real
Rastreamento de ações, decisões e uso de ferramentas
Registro de histórico e refinamento do comportamento

# Protocolos de comunicação
Protocolos de comunicação vs Tool Calling

Icone

MCP (Model Context Protocol)

Protocolos de comunicação vs Tool Calling
Fundamentos do MCP (Tools, Resources e Prompts)
Servidores MCPs e Docker MCP Tool Kit
MCPs na prática, incluindo Resources e Prompts
Desenvolvimento de Servidores MCPs
Deploy e distribuição utilizando Docker
Icone

Google A2A (Agent to Agent)

Fundamentos do A2A
Tasks, Messages, Parts, Agent Cards e Artifacts
Arquitetura e fluxo de comunicação A2A
Estrutura de uma Task e estados possíveis
Tipos de mensagens e partes (text, file, json, etc.)
Descoberta de agentes (agent.json)
Composição de agentes desenvolvidos com diferentes frameworks

# DevOps e SRE com IA

Fundamentos de DevOps e SRE

Princípios e práticas do DevOps moderno
O papel do SRE e a cultura de confiabilidade
Diferenças e complementaridades entre DevOps e SRE
Onde a GenAI atua em cada um dos papéis
Icone

Automação de pipelines e deploys com IA

Geração assistida de pipelines e arquivos de configuração
Otimização de etapas com base em histórico de builds e deploys
Sugestões automáticas de ajustes e paralelizações
Geração de changelogs e notas de release com copilotos
Icone

Segurança em pipelines com IA

Introdução ao conceito de DevSecOps
Geração assistida de regras de SAST (análise estática) e DAST (análise dinâmica)
Automatização da detecção de vulnerabilidades via LLM
Validação de dependências e análise de pacotes com copilotos
Geração automatizada de alertas de segurança em pipelines
Icone

Monitoramento e observabilidade assistidos por IA

Detecção de anomalias com explicação em linguagem natural
Consultas conversacionais a métricas e logs
Insights e correlações automáticas com múltiplas fontes
Geração automatizada de resumos e dashboards
Icone

Resposta a incidentes com suporte de IA

Geração automática de resumos de incidentes
Sugestões de mitigação com base em runbooks e histórico
Interações via ChatOps com copilotos operacionais
Rascunhos automáticos de postmortem com base em dados reais
Icone

Agentes operacionais e copilotos no ciclo de confiabilidade

Diferença entre copilotos e agentes autônomos
Exemplos de agentes atuando em diagnóstico e ações corretivas
Estratégias de adoção gradual com supervisão humana
Casos práticos em ambientes com alta exigência de confiabilidade

# Marketing Pessoal, Trabalho em Equipe e Empreendedorismo
Marketing Pessoal: Posicionamento e Percepção

As sete chaves para o sucesso com Roberto Justus
Quem é você vs. Quem pensam que você é?
O valor de se conhecer para se comunicar com clareza
Reputação: como você é percebido (e por que isso importa)
Ser visto: criação de conteúdo e visibilidade estratégica
Ser lembrado: networking com propósito
Ser entendido: comunicação como diferencial profissional
Icone

Trabalho em Equipe e Liderança

Pipeline de liderança: como liderar a si mesmo primeiro
Autoconhecimento como base para boas relações
Habilidades de convivência e colaboração em equipe
Liderança de pessoas: boas práticas e construção de confiança
Liderança de líderes: visão sistêmica e multiplicação de talentos
Icone

Empreendedorismo e Protagonismo Profissional

Introdução ao empreendedorismo dentro e fora de empresas
Perfil do empreendedor: coragem, resiliência e visão
Fundamentos de marketing e growth para iniciativas modernas
Protagonismo e coragem com Clovis de Barros Filho
Lições práticas com Cris Arcangelli: inovação e startups
Considerações finais: como aplicar o que aprendeu em sua jornada
