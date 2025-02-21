# Sistema de Assistência Virtual com Processamento de Linguagem Natural (PLN)

Este é um projeto de criação de um sistema de assistência virtual utilizando técnicas de Processamento de Linguagem Natural (PLN). O sistema é capaz de realizar diversas ações por meio de comandos de voz, como transformar texto em fala, converter fala em texto e realizar buscas em plataformas como Wikipedia e YouTube, além de buscar a localização da farmácia mais próxima.

## Funcionalidades

1. **Transformação de Texto em Áudio (Text-to-Speech)**: Converte textos digitados em áudio, utilizando a biblioteca `gTTS` (Google Text-to-Speech).
   
2. **Transformação de Fala em Texto (Speech-to-Text)**: Converte áudio de fala para texto utilizando a biblioteca `speech_recognition`.

3. **Ações Automatizadas por Comando de Voz**: O sistema é capaz de realizar ações como:
   - Pesquisar no Wikipedia.
   - Abrir o YouTube.
   - Localizar a farmácia mais próxima utilizando geolocalização.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação principal.
- **gTTS**: Biblioteca para conversão de texto para fala.
- **SpeechRecognition**: Biblioteca para reconhecimento de fala.
- **Wikipedia**: API para consultas ao Wikipedia.
- **Geopy**: Biblioteca para geolocalização.
- **Webbrowser**: Para abrir links em um navegador.

## Pré-requisitos

Certifique-se de que as seguintes bibliotecas estão instaladas no seu ambiente:

```bash
pip install gTTS
pip install SpeechRecognition
pip install wikipedia
pip install geopy
