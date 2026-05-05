# Tools — WW2 Doc Production Squad

Ferramentas externas integradas ao squad de produção.

## 1. ContentMachine
- **Repo:** [Saganaki22/ContentMachine](https://github.com/Saganaki22/ContentMachine)
- **Função:** Pipeline completa de produção visual (imagens → vídeos → áudio → export)
- **Path:** `tools/content-machine/`
- **Iniciar:** `cd tools/content-machine && npm install && npm run dev`

## 2. Remotion Studio
- **Repo:** [remotion-dev/template-prompt-to-video](https://github.com/remotion-dev/template-prompt-to-video)
- **Função:** Motion graphics para cenas pontuais (mapas, transições, intro/outro)
- **Path:** `tools/remotion-studio/`
- **Iniciar:** `cd tools/remotion-studio && npm install && npm run dev`

## 3. Loki Fact-Check
- **Repo:** [Libr-AI/OpenFactVerification](https://github.com/Libr-AI/OpenFactVerification)
- **Função:** Verificação automática de fatos em roteiros
- **Path:** `tools/loki-factcheck/`
- **Iniciar:** `cd tools/loki-factcheck && pip install -r requirements.txt`

## APIs Necessárias
| API | Usado por | Link |
|-----|----------|------|
| Gemini | ContentMachine | [aistudio.google.com](https://aistudio.google.com/api-keys) |
| Replicate | ContentMachine | [replicate.com](https://replicate.com/account/api-tokens) |
| ElevenLabs | ContentMachine + Remotion | [elevenlabs.io](https://elevenlabs.io/app/settings/api-keys) |
| OpenAI | Remotion + Loki | [platform.openai.com](https://platform.openai.com/api-keys) |
| Serper | Loki | [serper.dev](https://serper.dev/) |
