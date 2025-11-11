# 🌿 Cuidar e Viver — Projeto Final

**Resumo**  
Site estático que apresenta ações de proteção animal e bem-estar. Esta entrega demonstra práticas profissionais de versionamento (GitFlow), acessibilidade (WCAG 2.1 AA), otimização e deploy em produção via GitHub Pages.

---

## 🔗 Link do projeto (deploy)
Site publicado:  
https://jessicabeatriz04.github.io/cuidar---viver-final/

---

## 🎯 Objetivos da entrega
- Controle de versão com Git/GitHub (GitFlow básico)
- Documentação técnica e histórico de versões
- Acessibilidade conforme WCAG 2.1 Nível AA
- Otimização para produção (minificação e imagens otimizadas)
- Deploy público (GitHub Pages)

---

## 📁 Estrutura do repositório
- `index.html` — página principal
- `style.css` / `style.min.css` — estilos
- `script.js` / `script.min.js` — scripts
- `images/` — imagens otimizadas (WebP/JPEG)
- `.github/` — templates de PR e issues
- `CHANGELOG.md` — histórico de releases

---

## Como visualizar (rápido)
1. Abra o link do GitHub Pages acima.  
2. Ou acesse `index.html` diretamente no repositório (clicando no arquivo).

---

## 🔧 Como editar direto no GitHub (passo a passo)
1. Abrir repositório no GitHub.  
2. Criar branch nova para alterações: clique no dropdown da branch (ex.: `main`) → digite `feature/nome-da-feature` → **Create branch**.  
3. Editar arquivos: **Add file → Create new file** ou abrir o arquivo e clicar no lápis ✏️ **Edit this file**.  
4. Fazer commit: escrever mensagem seguindo Conventional Commits (ex: `feat(header): adicionar skip link`) → **Commit changes** (para a branch).  
5. Abrir Pull Request (PR): **Pull requests → New pull request** → base `main` (ou `develop`) e compare sua branch → **Create pull request** → depois **Merge pull request**.

---

## ♿ Acessibilidade (ações implementadas)
- Estrutura semântica: `<header>`, `<main>`, `<section>`, `<footer>`.
- Skip link para pular para o conteúdo.
- Foco visível com `outline` para teclado.
- Alternador de tema (modo escuro/alto contraste).
- Imagens com `alt` significativo e `loading="lazy"`.
- Labels explicítos para formulários e `role`/`aria-*` onde necessário.
- Recomendação de checagem: Lighthouse e axe (extensão) — documentar resultados como evidência no PR.

---

## 🛠️ Otimização para produção
- Versões minificadas: `style.min.css` e `script.min.js` (incluir no `index.html` em produção).
- Imagens otimizadas (WebP e JPEG comprimido).
- Uso de `<picture>` e `srcset` para imagens responsivas.
- GitHub Pages faz compressão e serve via HTTPS.

---

## 🔖 Versionamento & Releases
- Branches sugeridas: `main`, `develop`, `feature/*`, `release/*`, `hotfix/*`.
- Tag e release seguindo SemVer (`v1.0.0`, etc.).  
- CHANGELOG mantido com resumo por release.

---

## ✅ Checklist da entrega (para anexar na atividade)
- [ ] Repositório público no GitHub
- [ ] README.md completo na raiz
- [ ] Branches e commits semânticos (Conventional Commits)
- [ ] Pull Requests criados e mergeados
- [ ] Issues e Milestone “Entrega Final” criadas e vinculadas
- [ ] Release `v1.0.0` publicada
- [ ] GitHub Pages ativo e link público
- [ ] Acessibilidade implementada: skip link, foco, labels, roles
- [ ] Arquivos minificados presentes

---

## 📎 Referências e evidências
- Incluir no PR screenshots do Lighthouse ou do axe, e comentário no PR sobre os testes manuais (navegação por teclado, leitura por leitor de tela).

---

## ✍️ Contato
Feito por: **Jessica Beatriz** — https://github.com/JessicaBeatriz04  
# cuidar---viver-final
Projeto final — acessibilidade, GitFlow e deploy
