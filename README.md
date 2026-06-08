## Inteligência Artificial e Engenharia de Prompts

Este repositório foi criado como parte do desafio prático da [DIO](https://www.dio.me/), integrando os conhecimentos adquiridos no **Bootcamp Bradesco - GenAI, Dados & Cyber**. O objetivo é utilizar o Google NotebookLM para organizar, refinar e documentar técnicas avançadas de interação com Inteligências Artificiais.

---

## 1. Contexto e Objetivos

### Assunto de Interesse
O tema central deste caderno é a **Engenharia de Prompts e Fundamentos de IA Moderna**. Com a evolução dos Modelos de Linguagem de Grande Escala (LLMs), saber como estruturar instruções claras tornou-se uma habilidade técnica indispensável. 

### Objetivos de Estudo
*   Consolidar os fundamentos de Machine Learning, LLMs e Agentes Inteligentes.
*   Documentar técnicas práticas de Engenharia de Prompts (Zero-shot, Few-shot, etc.).
*   Criar um repositório de prompts reutilizáveis para geração de textos e refinamento de imagens realistas.

### Certificações Conquistadas (Base de Conhecimento)
Este material foi construído a partir dos aprendizados nos seguintes módulos do bootcamp:
1. Boas vindas ao Bootcamp Bradesco - GenAI, Dados & Cyber
2. Fundamentos da IA Moderna: Machine Learning, LLMs, IA Generativa e Agentes
3. Fundamentos de Modelos de Linguagem de Grande Escala
4. Introdução à Engenharia de Prompts
5. Técnicas de Engenharia de Prompt
6. Desafios de Projetos: Crie Um Portfólio Vencedor

---

## 2. Curadoria de Fontes

Para alimentar o NotebookLM e criar este guia sem risco de alucinações da IA, utilizei como base:
1. **Material do Bootcamp:** Transcrições e resumos das aulas teóricas da DIO sobre LLMs e IA Generativa.
2. **Documentação Oficial:** Guias de boas práticas de prompting da OpenAI/Anthropic (PDF).
3. **Artigo de Referência:** *Técnicas de Otimização de Prompts para Redução de Viés e Alucinação*.
*(Os materiais foram enviados para o ambiente do NotebookLM para embasar as respostas).*

---

## 3. Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta seção, documento os testes realizados no NotebookLM para extrair o melhor conhecimento, simulando a criação de uma diretriz para gerar imagens corporativas.

### Teste 1: O Prompt Genérico (Resultado Ruim)
*   **Prompt:** `"Resume como criar um bom prompt para foto de perfil corporativa."`
*   **Resposta da IA:** A IA deu dicas superficiais, resultando em sugestões que frequentemente geram imagens com aspecto muito artificial e fundos poluídos.
*   **A "Cicatriz":** Percebi que precisava ser mais incisivo sobre os parâmetros negativos e o estilo exato desejado para a saída.

### Teste 2: O Prompt Estruturado (Resultado Excelente)
*   **Prompt:** 
    > "Aja como um Especialista em Engenharia de Prompt. Com base nos nossos documentos, crie uma estrutura de prompt otimizada para uma IA geradora de imagens. O objetivo é criar uma foto para uso profissional. É fundamental exigir alto realismo e impor estritamente o uso de um fundo branco liso. Inclua comandos para evitar qualquer aspecto artificial, de pintura ou ilustração."
*   **Resultado Obtido:** O NotebookLM retornou uma estrutura de prompt perfeita, separando [Sujeito], [Iluminação], [Lente da Câmera] e um bloco pesado de [Prompts Negativos] (ex: *cartoon, renderização 3D, artificial, fundo texturizado*), garantindo o realismo exigido.

---

## 4. Miniguia de Estudo (Entrega Final)

### Resumos Estruturados

*   **Machine Learning (ML) vs. IA Generativa:** Enquanto o ML tradicional foca em analisar dados para prever resultados a IA Generativa utiliza redes neurais profundas para criar *novos* conteúdos (textos, imagens, código) a partir de padrões aprendidos.
*   **LLMs (Large Language Models):** São modelos treinados em vastas quantidades de texto. Eles não "pensam", mas calculam a probabilidade da próxima palavra com base no contexto (Prompt) fornecido.
*   **O Ciclo do Prompt Eficaz:** Um bom prompt deve conter: **Um Contexto** (Quem a IA deve ser), **A Instrução** (O que ela deve fazer), **Dados de Entrada** (Informações base) e **Formato de Saída** (Como a resposta deve ser apresentada).

---

### Glossário de Conceitos-Chave

*   **Zero-Shot Prompting:** Pedir à IA para realizar uma tarefa sem fornecer nenhum exemplo prévio.
*   **Few-Shot Prompting:** Fornecer alguns exemplos de entradas e saídas esperadas dentro do prompt para guiar o comportamento da IA.
*   **Alucinação:** Quando a IA gera informações falsas ou sem sentido, mas as apresenta de forma muito confiante.
*   **Tokens:** Pedaços de palavras que a IA usa para processar a linguagem. Uma palavra pode ser um token único ou ser dividida em vários tokens menores.

---

### Prompts Reutilizáveis para Revisão e Trabalho

**1. Refinamento de Código ou Texto:**
> "Atue como um revisor sênior. Avalie o texto/código abaixo e aponte 3 melhorias com base em clareza, eficiência e boas práticas. Forneça a versão corrigida ao final."

**2. Explicação de Conceitos Complexos (Técnica de Feynman):**
> "Explique o conceito de Bubble Sort como se eu tivesse 10 anos de idade. Use analogias do dia a dia e evite jargões técnicos excessivos."

---
*Desenvolvido durante o Bootcamp Bradesco na DIO.*
