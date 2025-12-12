# Clube do Livro SJBV — Diagramas UML (Semana 3)

Este repositório contém os diagramas UML preparados para o **Clube do Livro SJBV**:
- Diagrama de Casos de Uso (`diagrams/plantuml/usecase-clube-do-livro.puml`)
- Diagrama de Sequência — *Realizar Empréstimo* (`diagrams/plantuml/sequence-realizar-emprestimo.puml`)
- Diagrama de Classes (`diagrams/plantuml/class-diagram-clube-do-livro.puml`)
- Imagens geradas (em `diagrams/images/`): `registrar-pedido-cafe-dev.png`, `fazer-deposito-app-bancario.png`

---

## Como usar este repositório
1. **Visualizar PlantUML localmente**
   - Instale o [PlantUML](https://plantuml.com/pt/starting) e o Java (se necessário).
   - Gere PNGs a partir dos arquivos `.puml`:
     ```bash
     plantuml diagrams/plantuml/*.puml
     ```
   - Os PNGs serão criados ao lado dos arquivos `.puml`.

2. **Publicar no GitHub (passo a passo)**
   - Crie uma pasta local (já existe se você baixou este ZIP).
   - Inicie o repositório Git e faça o commit:
     ```bash
     cd clube-do-livro-sjbv-uml
     git init
     git add .
     git commit -m "Adicionar diagramas UML da Semana 3"
     ```
   - Crie o repositório no GitHub:
     - Opção web: vá para https://github.com/new e crie um repositório com o nome `clube-do-livro-sjbv-uml`.
     - Ou use a CLI `gh`:
       ```bash
       gh repo create seu-usuario/clube-do-livro-sjbv-uml --public --source=. --remote=origin
       ```
   - Envie (push) para o GitHub:
     ```bash
     git branch -M main
     git push -u origin main
     ```

3. **Dicas para visualizar PlantUML no GitHub**
   - O GitHub não renderiza PlantUML por padrão. Sugestões:
     - Inclua as imagens geradas (`diagrams/images/*.png`) no repositório (já incluídas aqui).
     - Use uma Action para gerar diagramas automaticamente (ex.: `plantuml/plantuml-action`).
     - Ou adicione os arquivos `.puml` e use a extensão do VS Code: *PlantUML* para visualizar localmente.

4. **Sugestões de README/Documentação**
   - Explique o propósito dos diagramas.
   - Acrescente legendas para cada diagrama.
   - Se quiser, adicione um `docs/` com versões em PDF e slides.

---

## Arquivos inclusos
- `diagrams/plantuml/*.puml` — fontes PlantUML
- `diagrams/images/*.png` — imagens geradas
- `README.md` — este arquivo

---

Se quiser, eu também:
- Gerar um ZIP pronto para download.  
- Criar um PR em um repositório existente (se você me fornecer o link).  
- Gerar um PowerPoint com os diagramas prontos para apresentação.