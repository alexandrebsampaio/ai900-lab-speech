# Processamento de Texto com IA da Azure  

Este repositório contém um projeto prático desenvolvido durante o curso de Inteligência Artificial da Azure na DIO. O objetivo deste projeto é explorar e aplicar conceitos como transcrição em tempo real, resumo de textos e conversão de texto em avatar de fala.  

## 📌 Estrutura do Projeto  

📂 `inputs/` - Contém um documento de texto com sentenças utilizadas na análise.  
📂 `output/` - Contém prints e resultados dos testes realizados.  
📄 `README.md` - Documentação do projeto, insights e aprendizados.  

## 🚀 Processo de Desenvolvimento  

1. **Transcrição em Tempo Real (Real-time Transcription)**  
   - Utilizamos o serviço de transcrição da Azure para converter fala em texto em tempo real.  
   - Testamos diferentes cenários, como transcrição de uma conversa e de um áudio previamente gravado.  

2. **Resumo de Texto (Summarize Text)**  
   - Enviamos textos longos para a API da Azure, que gerou resumos concisos e objetivos.  
   - Comparação entre o texto original e o resumo gerado.  

3. **Texto para Avatar de Fala (Text to Speech Avatar)**  
   - Criamos um avatar falante que interpreta o texto enviado.  
   - Fiz uma brincadeira com minha filha, utilizando frases divertidas para testar a funcionalidade.  

## 📸 Exemplos e Resultados  

### 🎙️ Exemplo de Transcrição em Tempo Real  
Áudio original:  
🔊 [Clique para ouvir](inputs/WhatAICanDo.m4a)  

Texto transcrito:  
Olá, estou testando a transcrição em tempo real da Azure! Funciona muito bem!

![Transcrição em Tempo Real](output/image-speech.png)  

---

### 📄 Exemplo de Resumo de Texto  
Texto original:  
O avanço da inteligência artificial tem transformado diversas indústrias, desde saúde até finanças. Com algoritmos cada vez mais sofisticados, a IA permite automação, geração de insights e melhoria na eficiência operacional. No entanto, desafios éticos e regulatórios ainda precisam ser superados.

Resumo gerado pela IA:  
A IA está revolucionando indústrias, melhorando eficiência, mas enfrenta desafios éticos e regulatórios.

![Resumo de Texto](output/image-summarize.png)  

---

### 🎭 Exemplo de Texto para Avatar de Fala  
Frase utilizada na brincadeira com minha filha: 
Oi, Clara! Hoje vamos brincar com um robô que fala como gente!

*Avatar falando:*  
![Avatar de Fala](output/video.mp4)  

---

## 📌 Insights e Possibilidades  

- A transcrição em tempo real pode ser aplicada em reuniões, legendas automáticas e assistentes virtuais.  
- A geração automática de resumos é útil para otimizar a leitura de grandes volumes de texto.  
- O Text to Speech Avatar pode ser aplicado em educação, acessibilidade e entretenimento.  

## 🔗 Links Úteis  

- [Laboratório de Transcrição de Áudio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/09-speech.html)  
- [Laboratório de Resumo de Texto](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/06-text-analysis.html)  
