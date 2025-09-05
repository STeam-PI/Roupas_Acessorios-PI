# Guia de Contribuição

Este documento explica como nossa equipe deve colaborar de forma organizada, respeitando as responsabilidades de cada time.

---

## 📌 Estrutura da Organização

Nosso trabalho está dividido em **3 times principais**:

1. **Controle da Organização (Admins/Maintainers)**  
   - Administram permissões, merges e pull requests.  
   - Mantêm a integridade da branch principal (`main`).  
   - Validam contribuições antes de entrarem em produção.  

2. **Equipe de Desenvolvimento (HTML/CSS e afins)**  
   - Responsável por implementar a aplicação web.  
   - Contribuem com código, estilos e integração.  
   - Trabalham em branches específicas e submetem PRs para revisão.  

3. **Equipe de Layout/Design (UI/UX)**  
   - Responsável pela aparência e experiência da aplicação.  
   - Produzem protótipos, wireframes e guias visuais (ex.: via Figma).  
   - Trabalham em conjunto com os desenvolvedores para garantir consistência.  

---

## 📌 Fluxo de Trabalho (Workflow)

1. **Criação de Branch**  
   - Sempre criar uma branch a partir da `main`:  
     ```bash
     git checkout main
     git pull origin main
     git checkout -b feature/nome-da-feature
     ```

2. **Implementação**  
   - Equipe de **desenvolvimento** implementa novas funcionalidades ou correções.  
   - Equipe de **layout** mantém arquivos/documentos de design e sugere ajustes.  
   - Sempre seguir os protótipos/designs aprovados antes de codar.  

3. **Pull Requests (PRs)**  
   - Todo PR deve ser aberto contra a branch `main`.  
   - Inclua uma descrição clara do que foi feito e, se possível, imagens/prints (quando for mudança visual).  
   - Se o PR estiver relacionado a um protótipo do Figma, adicione o link.  

4. **Revisão e Merge**  
   - O merge **só pode ser feito pelo time de Controle da Organização**.  
   - Todo PR precisa de **pelo menos 1 aprovação** antes do merge.  
   - PRs que alteram layout devem ter validação da equipe de design.  

---

## 📌 Convenções de Branches

- `feature/nome-da-feature` → novas funcionalidades  
- `bugfix/descricao` → correções de bugs  
- `layout/nome-da-alteracao` → mudanças propostas pela equipe de design  
- `hotfix/descricao` → correções urgentes  

---

## 📌 Convenções de Commits

Usamos mensagens curtas, claras e no **imperativo**:  

- `Adiciona componente de navegação`  
- `Corrige bug no formulário de login`  
- `Atualiza layout da página inicial`  

---

## 📌 Boas Práticas

- Mantenha os commits pequenos e objetivos.  
- Atualize sua branch com frequência usando `git pull origin main`.  
- Respeite as diretrizes da equipe de design (UI/UX).  
- Documente mudanças significativas no código ou design.  

---

## 📌 Comunicação

- **Issues** → para relatar bugs, propor melhorias ou discutir ideias.  
- **Pull Requests** → para enviar contribuições de código ou layout.  
- **Figma** → para colaboração em protótipos e fluxos de design.  

---

## 📌 Contato

Dúvidas ou sugestões devem ser discutidas abrindo uma **issue** no repositório.  
Em casos críticos, entrar em contato diretamente com os **Admins/Maintainers**.
