# 🗺️ LegacyLens - Documentação Automática de Código Legado com IA

> Transformando "código dinossauro" em conhecimento acionável em segundos.

---

## 📌 Sobre o Projeto

O **LegacyLens** é uma ferramenta baseada em Inteligência Artificial projetada para resolver um dos maiores gargalos no desenvolvimento de software: **entender e dar manutenção em sistemas antigos (código legado) sem documentação.**

Enquanto as ferramentas de mercado atuais apenas geram comentários simples em linhas de código (`JSDoc`, `Javadoc`), o LegacyLens atua na **arquitetura e no impacto**. Ele analisa arquivos ou repositórios inteiros e gera um **"Guia de Sobrevivência" em Markdown**, detalhando regras de negócio implícitas, pontos críticos de atenção e mapeamento de dependências.

---

## 🧠 O Problema Real & O Gap de Mercado

* **O Problema:** Desenvolvedores perdem dias (ou semanas) decifrando sistemas antigos antes de implementar novas *features* ou corrigir *bugs*, gerando custos altos e atrasos nas entregas.
* **O Gap:** As ferramentas de IA generativas comuns ajudam a escrever código, mas falham em contextualizar a arquitetura global e o impacto cascata de alterar uma função legada.
* **A Solução:** Uma aplicação que realiza engenharia reversa automatizada, entregando documentação técnica de alto nível estruturada em Markdown.

---

## 🚀 Como Funciona (Fluxo do MVP)

1. **Upload:** O desenvolvedor faz o upload de um arquivo ou conecta o repositório legado.
2. **Análise de Contexto:** O sistema lê a estrutura do código e extrai o fluxo de execução.
3. **Engenharia Reversa (Prompt Engineering):** O código é enviado para modelos de linguagem avançados (GPT-4o ou Claude 3.5 Sonnet) através de um *System Prompt* altamente especializado em arquitetura de software.
4. **Guia de Sobrevivência:** A IA gera e exporta um arquivo `.md` estruturado.

---

## 🛠️ Tecnologias Utilizadas

* **Front-end:** [Inserir aqui: ex: React / Next.js ou HTML/Tailwind para interface web]
* **Back-end:** [Inserir aqui: ex: Node.js / Python Fast-API / Go]
* **Engine de IA:** API do OpenAI (GPT-4o) / Anthropic (Claude 3.5 Sonnet)
* **Técnica Principal:** Engenharia de Prompt Estruturada (System Prompt) para Engenharia Reversa.

---

## 📄 Estrutura do "Guia de Sobrevivência" Gerado

O Markdown final gerado pela aplicação entrega a seguinte estrutura:

* **Visão Geral da Arquitetura:** O que este componente faz e qual o seu papel no sistema.
* **Regras de Negócio Identificadas:** Tradução do código técnico para regras lógicas do negócio.
* **Pontos Críticos de Atenção:** Funções complexas, *gargalos* de performance ou áreas com alto risco de efeito colateral.
* **Mapeamento de Dependências:** O que quebra se esta função for alterada?

---

## 🛠️ Configuração e Instalação (Local)

Se você quiser rodar este projeto localmente para testes, siga os passos abaixo:

### Pré-requisitos
* [Node.js](https://nodejs.org/) ou [Python](https://www.python.org/) instalado.
* Uma chave de API da OpenAI (`OPENAI_API_KEY`) ou Anthropic.

### Passo a Passo

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/DonRatinho/nome-do-repositorio.git](https://github.com/DonRatinho/nome-do-repositorio.git)
   cd nome-do-repositorio
