# 🎤 Voz para Voz com IA: Python + JavaScript + Whisper + ChatGPT + gTTS

Este repositório demonstra um fluxo completo de interação por voz:
1. **Gravação de Áudio** com Python e JavaScript no Google Colab.
2. **Reconhecimento de Fala** com Whisper (OpenAI).
3. **Integração com a API do ChatGPT** para gerar respostas inteligentes.
4. **Síntese de Voz** com gTTS para transformar a resposta em áudio novamente.

🔗 [Abrir Notebook no Google Colab](https://colab.research.google.com/drive/1rHGq5N-sbEGtZsNUiQFT8q60BhRbj99b?usp=sharing#scrollTo=Rn_50q97XZNt)  
📖 Referência: [gist de Korakot](https://gist.github.com/korakot/c21c3476c024ad6d56d5f48b0bca92be)

---

## 📌 Etapas do Projeto

### 1. Gravação de Áudio 🎤
- Uso da **MediaStream Recording API** via JavaScript para capturar áudio do microfone.
- Integração com Python para salvar o arquivo `.wav` no Colab.
- Reprodução do áudio gravado diretamente no notebook.

### 2. Reconhecimento de Fala 🧠
- Transcrição do áudio usando **Whisper (OpenAI)**.
- Suporte a múltiplos idiomas e diferentes tamanhos de modelo (`tiny`, `small`, `medium`, `large`).

### 3. Integração com ChatGPT 💬
- Envio da transcrição para a **API do ChatGPT**.
- Geração de respostas contextuais e inteligentes.
- Uso da biblioteca oficial `openai`.

### 4. Síntese de Voz 🔊
- Conversão da resposta em áudio com **gTTS (Google Text-to-Speech)**.
- Reprodução automática da resposta sintetizada.

---

## 🚀 Como usar
1. Abra o notebook no Google Colab.
2. Execute as células em ordem:
   - Gravação de áudio.
   - Transcrição com Whisper.
   - Integração com ChatGPT.
   - Síntese de voz com gTTS.
3. Interaja por voz e receba respostas faladas!

---

## 📂 Estrutura
- `Notebook.ipynb` → Notebook principal com código e explicações.
- `request_audio.wav` → Áudio gravado do usuário.
- `response_audio.wav` → Áudio da resposta sintetizada pelo gTTS.
- `transcription.txt` → Texto transcrito pelo Whisper.

---

## 🛠️ Requisitos
- Python 3.x  
- Bibliotecas:  
  - `IPython.display`, `google.colab`, `base64`  
  - `whisper`  
  - `openai`  
  - `gtts`  
- Conta Google para rodar no Colab.  
- API Key da OpenAI para usar ChatGPT.  

---

## 📊 Demonstração
Fluxo simplificado:
1. 🎤 Você fala →  
2. 🧠 Whisper transcreve →  
3. 💬 ChatGPT responde →  
4. 🔊 gTTS fala a resposta.  

---

## 🤝 Contribuição
Contribuições são bem-vindas!  
Abra uma **issue** ou envie um **pull request** para sugerir melhorias.

---

## 📜 Licença
Este projeto está sob a licença [MIT](LICENSE).  
Você pode usar, modificar e distribuir livremente, desde que mantenha os créditos.
