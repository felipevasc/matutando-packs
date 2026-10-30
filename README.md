# pituibinha-packs

Pacotes de conteúdo que o app **Pituibinha** baixa sob demanda: artes, modelos, músicas e fases de jogos que não vêm no app instalado.

Este repositório só serve as **Releases**. Nelas ficam:

- `catalog.json`: a lista de pacotes, com versão, tamanho, SHA-256 e link de cada um;
- `catalog.json.sig`: a assinatura RSA-SHA256 do catálogo. O app só aceita um catálogo assinado pela chave do projeto;
- `<id>-<versão>.pck`: os pacotes, no formato de pacote do Godot 4.

Os pacotes **não têm código**, só recursos. O código de todos os jogos já vem no app.

O app busca sempre `releases/latest/download/catalog.json`. As versões antigas ficam nas Releases anteriores, para quem ainda usa um app antigo.

Os pacotes são gerados pelo script `tools/packs/build_packs.py` do projeto do jogo.

---

## 🔒 Política de Privacidade

A política de privacidade oficial do aplicativo **Pituibinha** está disponível em:
- [Visualizar Política de Privacidade (Markdown)](PRIVACY.md)
- [Visualizar Política de Privacidade (HTML)](politica_de_privacidade.html)
