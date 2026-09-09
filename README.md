# Inteligência Artificial de Visão Computacional com Azure AI Foundry

Este projeto foi desenvolvido como parte do cursp da DIO com o objetivo de explorar as capacidades de IA e Machine Learning da Microsoft Azure aplicadas à visão computacional. Foram realizados testes práticos envolvendo **reconhecimento facial**, **extração de textos em imagens (OCR)** e **geração automática de descrições contextuais (legendas)**.

## 📁 Estrutura do Repositório

* **inputs/**: Contém as imagens originais utilizadas nos testes do laboratório.
* **output/**: Contém os resultados em texto (JSON/Txt) extraídos pela inteligência artificial.

## 🛠️ Passo a Passo do Processo

1. **Configuração no Azure**: Criação do recurso de inteligência artificial unificado no portal do Azure.
2. **Acesso ao Azure AI Foundry**: Utilização da nova plataforma da Microsoft para gerenciar os modelos de visão computacional.
3. **Execução dos Testes**: Upload das imagens contidas na pasta `inputs` para processamento simultâneo das seguintes ferramentas:
   * **Detecção Facial**: Mapeamento de rostos, pontos de referência faciais e estimativa de atributos.
   * **Extração de Texto (OCR)**: Identificação e digitalização de palavras e frases contidas nas imagens.
   * **Descrição da Imagem**: Geração de legendas automáticas baseadas no contexto e nos objetos identificados na cena.

## 📊 Principais Insights Obtidos

* **Análise Multimodal**: A IA da Microsoft consegue realizar três tarefas complexas e diferentes sobre a mesma imagem em questão de milissegundos, mostrando alto poder de processamento.
* **Leitura de Textos Complexos**: O sistema de OCR se mostrou extremamente resiliente, conseguindo identificar letras mesmo em superfícies curvas, com sombras ou fontes estilizadas.
* **Contextualização Semântica**: A descrição da imagem não apenas lista os objetos soltos, mas entende a relação entre eles (ex: identificar "uma pessoa sentada trabalhando em um escritório" em vez de apenas listar "computador, cadeira, humano").

## 🚀 Possibilidades de Aplicação no Mundo Real

* **Acessibilidade**: Aplicativos que descrevem o ambiente e leem placas/textos em tempo real para pessoas com deficiência visual.
* **Automação de Processos (RPA)**: Leitura e cadastro automático de documentos que misturam fotos e dados textuais (como CNH, RG ou passaportes).
* **Segurança e Monitoramento**: Sistemas inteligentes de vigilância que reconhecem faces autorizadas e lêem placas de veículos ao mesmo tempo.
* **Moderação de Conteúdo**: Filtros para redes sociais que analisam o que há escrito e o que aparece em fotos antes de permitir a publicação.

