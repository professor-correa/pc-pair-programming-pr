# pc-pair-programming-pr

Este repositório foi criado para que vocês pratiquem programação em dupla e conquistem a badge de **Co-author** no GitHub.

## Descrição

Trabalhe em dupla para resolver as tarefas propostas. Cada dupla deve abrir um Pull Request (PR) incluindo ambos como co-autores dos commits.

> **Importante:** Para que o GitHub reconheça o trailer `Co-authored-by:`, você precisa **desativar a proteção de email** (Keep my email address private) nas configurações de **Email** do GitHub.

## Estrutura de Componentes

Cada componente deve ser criado em `src/components/NomeComponente` contendo:

- `index.html` com a marcação HTML do componente.
- `styles.css` com o CSS do componente.
- `README.md` explicando:
  - O propósito do componente.
  - As classes ou IDs utilizados.

Mantenha nomes de arquivos e pastas claros e consistentes.

## Passo a passo

1. **Fork**  
   - Clique em **Fork** neste repositório.

2. **Clone**  
   ```bash
   git clone https://github.com/seu-usuario/pc-pair-programming-pr.git
   cd pc-pair-programming-pr
   ```

3. **Crie uma branch**  
   ```bash
   git checkout -b dupla-nome-tarefa
   ```

4. **Implemente o componente**  
   - Em `src/components`, crie `NomeComponente/` e adicione:
     - `index.html`  
     - `styles.css`  
     - `README.md`

5. **Faça o commit** com trailers `Co-authored-by:`  
   ```bash
   git add .
   git commit -m "feat: adiciona NomeComponente

   Co-authored-by: Nome Aluno A <emailA@exemplo.com>
   Co-authored-by: Nome Aluno B <emailB@exemplo.com>"
   ```
   - **Dica:** Verifique se seus emails são públicos ou se você desativou a proteção de email.

6. **Push**  
   ```bash
   git push origin dupla-nome-tarefa
   ``` 

7. **Abra o Pull Request**  
   - **Título:** `Dupla: NomeA & NomeB – Descrição da tarefa`  
   - **Descrição:** Verifique se aparecem os trailers `Co-authored-by:`.

8. **Revisão e Merge**  
   - Após aprovação, faremos o merge e vocês receberão a badge de Co-author.