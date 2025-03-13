## **Convenção de Padronização de Branches e Commits**  

Referência: [Uma Convenção Simplificada para Nomear Branches e Commits no Git](https://dev.to/varbsan/a-simplified-convention-for-naming-branches-and-commits-in-git-il4)  

**Exemplo de branch:**  
```bash
git branch <categoria/referência/descrição-em-kebab-case>
```
  
**Exemplo de commit:**  
```bash
git commit -m '<categoria: descrição da mudança>'
```

### **Categorias de commit**  

- `feat` → Adiciona um novo recurso.  
- `fix` → Corrige um bug.  
- `refactor` → Modifica o código para melhorar desempenho, legibilidade ou estrutura.  
- `chore` → Alterações não relacionadas ao código principal (ex.: documentação, testes, formatação).  

**Formato sugerido para commits:**  
```bash
git commit -m '<categoria: ação principal; ação secundária>'
```
Cada ação deve ser descrita de forma imperativa e separada por `;`.