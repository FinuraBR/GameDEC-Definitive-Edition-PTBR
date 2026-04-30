# Tradução / Open-Source - GameDEC Definitive Edition (PT-BR)

## ⚠️ Sobre a Tradução e IA

Esta tradução foi gerada utilizando **modelos avançados de Inteligência Artificial**. Embora a IA tenha sido configurada para oferecer a melhor qualidade possível no contexto de jogos, é importante ter em mente algumas características inerentes a este método:

*   **Inconsistências**: Pode haver variações na terminologia ou no estilo entre diferentes partes do jogo, especialmente em termos muito específicos ou gírias.
*   **Literalidade**: Em alguns casos, a tradução pode ser mais literal, perdendo nuances ou expressões idiomáticas que um tradutor humano capturaria.
*   **Contexto**: A IA nem sempre compreende o contexto completo de uma frase como um ser humano. Isso pode levar a frases que, embora gramaticalmente corretas, soem um pouco estranhas ou menos naturais.
*   **Aprimoramento Contínuo**: Este projeto serve como uma base sólida. A comunidade é bem-vinda para identificar e sugerir melhorias, tornando a tradução ainda mais fluida e precisa no futuro.

---

## 🛠️ Instalação (Para Jogadores)

A instalação é simples e direta, adicionando o arquivo de tradução como um mod no jogo.

1.  Acesse a aba **[Releases](https://github.com/FinuraBR/GameDEC-Definitive-Edition-PTBR/releases)** deste repositório e baixe o arquivo `.pak` mais recente.
2.  Localize a pasta de instalação do seu jogo. Geralmente, o caminho é algo como:
    `C:\Program Files (x86)\Steam\steamapps\common\gamedec\` (ou onde você instalou).
3.  Dentro da pasta do jogo, navegue até o seguinte diretório:
    `[PastaDoJogo]\GameDEC\Content\Paks\`
4.  **Arraste e solte** o arquivo `.pak` que você baixou diretamente nesta pasta (`Paks`).
5.  Inicie o jogo! A tradução estará ativa automaticamente.

---

## 🤝 Workflow e Estrutura Técnica (Para Desenvolvedores/Curiosos)

O processo de tradução desta versão do GameDEC foi realizado utilizando um **workflow automatizado** baseado em Python, projetado especificamente para Unreal Engine. Este workflow lida com a extração, tradução via IA, verificação e injeção de texto em arquivos `.uasset` e `.locres`.

Para detalhes completos sobre a arquitetura dos scripts, as etapas de processamento e as ferramentas utilizadas, por favor, consulte o repositório principal do workflow:

**[UE Translation Workflow - Repositório](https://github.com/FinuraBR/UE-Translation-Workflow)**

### Ferramentas Fundamentais do Workflow:
*   **UAssetGUI / UAssetAPI:** Para manipular arquivos `.uasset` (conteúdo de assets).
*   **Ferramentas de Localização UE4 (Externas):** Para extração e injeção de `.locres` (recursos de localização).
*   **Python 3.14+:** O motor de automação central, incluindo comunicação com modelos de IA e gerenciamento de arquivos.
*   **Google AI Studio (Gemini):** Modelo de linguagem AI utilizado para a tradução do conteúdo.

---

### 📜 Licença e Créditos

Este projeto de tradução é de código aberto. Caso utilize esta base de tradução ou o workflow subjacente em outros projetos, solicita-se a **manutenção dos créditos ao criador original**.

**Créditos da Tradução e Workflow:** ツFinuraBR

---
