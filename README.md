## 🔁 Workflow

Se você deseja contribuir com este projeto, siga os passos abaixo:

### 1. Fork do Repositório
Crie um fork deste repositório para o seu GitHub. Isso permitirá que você trabalhe no projeto de forma independente.

### 2. Crie uma Nova Branch
Crie uma branch a partir da `main` para desenvolver sua funcionalidade ou correção:

`git checkout -b nome-da-sua-branch`

### 3. Implemente a Funcionalidade
Faça suas alterações no código e registre seus commits com mensagens claras e descritivas:

`bash
Copiar
Editar
git add .
git commit -m "feat: descrição da nova funcionalidade"`

### 4. Envie sua Branch
Envie a branch para o seu repositório remoto no GitHub:

`bash
Copiar
Editar
git push origin nome-da-sua-branch`

### 5. Crie um Pull Request
Acesse seu repositório no GitHub e clique em "Compare & pull request" para abrir um PR com suas alterações. Certifique-se de direcioná-lo para a branch main deste repositório.

### 6. Aguarde a Revisão
Seu PR será revisado e pode receber comentários ou sugestões de ajustes. Após a aprovação, ele será mesclado à branch principal do projeto.

### 7. Delete a Branch (opcional, mas recomendado)
Depois que o merge for concluído, exclua a branch local e remota para manter o repositório limpo:

`bash
Copiar
Editar
git branch -d nome-da-sua-branch
git push origin --delete nome-da-sua-branch`
