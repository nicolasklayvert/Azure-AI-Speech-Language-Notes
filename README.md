# Desafio DIO: Azure AI - Speech e Language Studios

## 📝 Documentação do Laboratório Prático

Este repositório documenta a aplicação prática dos conceitos de Inteligência Artificial da Microsoft, focando nos serviços Azure Speech Studio e Language Studio. O objetivo foi explorar as capacidades de voz e linguagem e documentar a experiência adquirida.

### 🚀 Objetivos de Aprendizagem

* Aplicar o uso de estúdios de IA para desenvolvimento rápido.
* Compreender a funcionalidade básica do Reconhecimento de Fala e Análise de Sentimento.
* Utilizar o GitHub para documentação técnica estruturada.

---

## 1. 🎤 Azure Speech Studio: Análise e Síntese de Fala

A prática no Speech Studio focou na conversão bidirecional: fala em texto (Speech-to-Text) e texto em fala (Text-to-Speech).

| Funcionalidade Testada | O que foi feito | Conclusão / Insight |
| :--- | :--- | :--- |
| **Transcrição de Áudio (Speech-to-Text)** | Utilizei a ferramenta para transcrever áudios de teste em português. | A transcrição foi **rápida** e demonstrou uma precisão de aproximadamente **98%** em vocabulário padrão. O sistema demonstrou uma dificuldade esperada com **gírias complexas** e **ruídos de fundo** altos, o que exige pré-processamento de áudio para produção. |
| **Conversão de Texto em Fala (Text-to-Speech)** | Testei o recurso TTS com vozes neurais em português (ex: Francisca). | As vozes neurais são surpreendentemente **naturais**, com entonação e ritmo que se aproximam da fala humana. O recurso é ideal para **narração de vídeos** e sistemas de atendimento automatizado, reduzindo a necessidade de gravações de estúdio. |

---

## 2. 📝 Azure Language Studio: Processamento de Linguagem Natural (PLN)

A prática focou em entender como o Language Studio extrai significado e estrutura de textos não estruturados.

| Funcionalidade Testada | O que foi feito | Resultado Observado |
| :--- | :--- | :--- |
| **Análise de Sentimento** | Testei frases simples com polaridade definida (positiva, negativa, neutra). | Ao testar uma frase claramente negativa ("Não gostei nada desta experiência"), o sistema retornou **Negativo** com uma confiança acima de **90%**, com indicação dos termos que influenciaram o resultado. |
| **Extração de Entidades Nomeadas (NER)** | Colei um texto sobre um evento ou local. | O sistema identificou e classificou corretamente entidades como **Pessoas**, **Locais** e **Organizações**, o que é crucial para indexação de conteúdo e organização de grandes volumes de texto. |
| **Detecção de Idioma** | Submeti textos em diferentes idiomas. | A detecção é quase instantânea e extremamente precisa, mesmo em textos curtos, confirmando a robustez do modelo pré-treinado. |

---

## 3. 📦 Conclusão e Entrega

As ferramentas da Azure AI são poderosas e permitem prototipagem rápida de soluções de voz e texto, mesmo sem conhecimento aprofundado em Machine Learning.

* **Documentação Técnica:** O uso do GitHub e do Markdown foi essencial para manter a documentação estruturada e acessível.
* **Aprendizado:** A principal lição é que o valor está em saber aplicar e combinar essas ferramentas, e não necessariamente em construir os modelos do zero.

---

### **Autor**

- Klayvert
