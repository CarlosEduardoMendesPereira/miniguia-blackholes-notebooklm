# miniguia-blackholes-notebooklm
Miniguia de estudo interativo sobre a vida e morte dos buracos negros, compilado no NotebookLM a partir de 31 fontes com resumos, guia de estudos e áudio.

# Shadows of Creation: The life and Death of Black Holes

Este repositório reúne um estudo interativo sobre buracos negros desenvolvido utilizando a ferramenta **NotebookLM**.

## 📌 Conteúdo e Fontes
O projeto compila 31 fontes de artigos científicos, enciclopédias e notícias especializadas (como NASA, Wikipédia, Nobel Prize, entre outras), abordando:
- Estrutura e anatomia dos buracos negros (Horizonte de eventos, Singularidade, Disco de acreção).
- Tipos de buracos negros (Estelares, Supermassivos e Primordiais).
- Radiação de Hawking, evaporação e descobertas históricas (como a primeira foto do M87* e Sagitário A*).

## 🛠️ Recursos Gerados no NotebookLM
- **Guia de Estudo Completo** (*Comprehensive Study Guide*)
- **Resumo em Áudio** (*Biografia do Buraco Negro*)
- **Apresentação e Anatomia dos Buracos Negros**
- **Mapa Mental Interativo**

## 🎯 Contexto e Objetivos

O estudo de **Buracos Negros** é um dos campos mais fascinantes e complexos da astrofísica moderna, envolvendo conceitos de Relatividade Geral, Mecânica Quântica e evolução estelar. 

### Objetivos do Projeto:
* **Consolidar um Miniguia de Estudos:** Centralizar informações complexas de dezenas de fontes em um material didático e acessível.
* **Explorar o NotebookLM:** Avaliar o uso da IA generativa baseada em fontes confiáveis para síntese de conhecimento, geração de resumos em áudio, apresentações e mapas mentais.
* **Praticar Engenharia de Prompts:** Testar perguntas estratégicas para extrair respostas precisas, documentando o processo e os desafios de refinar os resultados.

## 📚 Curadoria de Fontes

Para alimentar o caderno no NotebookLM, foram selecionadas **31 fontes abertas** sobre o tema. Abaixo destacam-se 5 das principais fontes utilizadas:

1. 🌌 **NASA Science – Black Holes:** Visão geral da agência espacial sobre a anatomia e classificação dos buracos negros.
2. 🏆 **Nobel Prize in Physics (2020):** Documentação oficial da premiação concedida às descobertas sobre a formação de buracos negros e o objeto compacto supermassivo no centro da nossa galáxia.
3. ⚛️ **Hawking Radiation (JILA / Wikipedia):** Artigos sobre os efeitos quânticos e o processo de evaporação teórica dos buracos negros proposto por Stephen Hawking.
4. 📐 **Karl Schwarzschild – Wikipédia:** Registro histórico e matemático do cálculo da solução exata das equações de Einstein que deu origem ao conceito do Raio de Schwarzschild.
5. 🌠 **Direct Collapse Black Hole – Wikipedia:** Artigos sobre as teorias de formação de buracos negros supermassivos no universo primordial.

## 🧪 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta seção estão documentados os testes de prompts aplicados no NotebookLM, os resultados obtidos e os ajustes necessários durante o processo de extração do conhecimento.

### 1. Testes de Prompts e Resultados
* **Prompt Inicial (Genérico):** *"Me fale sobre buracos negros."*
  * **Resultado:** A IA gerou um texto longo e superficial com conceitos muito básicos.
* **Prompt Refinado (Estratégico):** *"Faça uma breve descrição sobre os buracos negros abordando sua definição, anatomia (horizonte de eventos, singularidade, disco de acreção), categorias por massa e as principais descobertas recentes (imagens diretas e radiação de Hawking)."*
  * **Resultado:** Resposta estruturada, citando diretamente os trechos das fontes importadas e cobrindo exatamente os pontos-chave de interesse.

### 2. "Cicatrizes" e Lições Aprendidas (Troubleshooting)
* **Desafio:** Evitar que a IA misturasse conceitos puramente teóricos (como buracos negros primordiais) com fatos comprovados observacionalmente (como o Sagitário A*).
* **Solução:** Adicionar restrições explícitas no prompt pedindo para diferenciar claramente **teoria/hipótese** de **observações empíricas/comprovadas**.
* **Alinhamento de Fontes:** Fontes em inglês e português geraram termos duplicados no glossário. Foi necessário solicitar à IA que mantivesse a terminologia padronizada em português.
