# 📌 Git Checklist — Boas Práticas

## 🔑 Antes de começar a trabalhar
```bash
git status                # verifica se está limpo
git pull --rebase         # atualiza sua branch com o remoto


✍️ Durante o trabalho
1. Editar/criar arquivos
2. Conferir mudanças:
	git status	
	git diff                # opcional, mostra o que mudou

3. Escolher o que vai para o commit:
	git add <arquivo>       # adiciona arquivo específico
	git add .               # adiciona tudo

4. Registrar mudanças:
	git commit -m "mensagem explicando a mudança"

🔄 Antes de enviar
	git pull --rebase         # garante que seu commit está em cima do remoto

🚀 Enviar para o GitHub
	git push

⚡ Fluxo Resumido
	git pull --rebase
	editar arquivos
	git add + git commit
	git pull --rebase
	git push


