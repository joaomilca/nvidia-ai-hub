# NVIDIA AI Developer Hub — Protótipo & Web App

Este repositório contém a documentação, configurações de IA e o código-fonte da aplicação **NVIDIA AI Developer Hub**, desenvolvida no âmbito do Entregável Individual 1 da disciplina de Desenvolvimento Ágil de Software (ISCTE).

---

## 📌 Visão Geral do Projeto
O **NVIDIA AI Developer Hub** é uma plataforma web interativa concebida para engenheiros de IA, arquitetos de sistemas e desenvolvedores explorarem a infraestrutura de computação acelerada da NVIDIA. A aplicação integra um catálogo de microserviços NIM, um playground de teste de inferência em tempo real, uma calculadora de dimensionamento de GPUs (Hopper e Blackwell) e um assistente virtual inteligente com agendamento integrado.

### 🛠️ Stack Tecnológica & Ferramentas
- **Frontend & UI:** React, TypeScript, Tailwind CSS, Lucide Icons (Dark Mode nativo)
- **Backend & Servidor:** Node.js / Express (`server.ts`)
- **Modelo de IA:** Gemini 1.5 Flash (via Google AI Studio API)
- **Agendamento:** Cal.com (incorporado via Modal e sincronizado com o Google Calendar)

---

## 🤖 Configuração do Assistente Virtual (System Instructions)

```text
# PAPEL E OBJETIVO
Atuas como o Assistente Virtual Oficial da NVIDIA. O teu objetivo principal é ajudar os visitantes da landing page a compreender o ecossistema de produtos da NVIDIA (Placas Gráficas GeForce RTX, Soluções de AI/Data Center, NVIDIA Omniverse e Plataformas para Desenvolvedores), esclarecer dúvidas técnicas e guiá-los para agendar uma reunião ou demonstração com a equipa de especialistas.

# CONTEXTO E INFORMAÇÕES SOBRE A NVIDIA
- Nome da Empresa: NVIDIA Corporation
- Descrição Breve: Líder mundial em computação com GPU, IA (Inteligência Artificial), aceleração gráfica, computação de alto desempenho (HPC) e plataformas para o Metaverso Industrial (Omniverse).
- Público-Alvo: Gamers e Criadores de Conteúdo, Desenvolvedores e Cientistas de Dados, Empresas e TI.
- Principais Linhas de Produto: Placas GeForce RTX, GPUs Data Center (H100, H200, B200), CUDA, TensorRT, NVIDIA NIMs, Omniverse.

# REGRAS DE COMPORTAMENTO E TOM DE VOZ
1. Tom de Voz: Inovador, técnico, amigável, profissional e focado em soluções. Responde em português.
2. Concisão: Mantém as respostas curtas (2 a 4 frases por mensagem).
3. Chamada para Ação (CTA): Recomenda o agendamento de reuniões através do link do Cal.com sempre que relevante.
4. Suporte a Dúvidas: Esclarece questões sobre compatibilidade, VRAM, licenças e requisitos de hardware.
