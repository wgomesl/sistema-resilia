# <p align="center">Sistema Resilia

## 📌 Objetivo: 

- O projeto deste módulo consistiu em criar um banco de dados (**escola**) que contivesse três entidades/tabelas (**cursos, turmas e alunos**).

### ⇨ Existem outras entidades além dessas três?
>Não, porém poderiam ter.

### ⇨ Quais são os principais campos e tipos?
> Os principais campos são id e cpf, porque são as chaves primárias. Os tipos estão definidos como int e varchar.

### ⇨ Como essas entidades estão relacionadas?
>A entidade turma possui no mínimo '1' e no máximo 'N' cursos. Cursos pode estar em '0' ou 'N' turmas;</br>
>Uma turma pode ter '0' ou no máximo 'N' aluno. Aluno pode estar no minimo '1' e máximo 'N' turmas;</br>
>Um aluno pode estar em '0' ou 'N' cursos. Cursos pode ter '0' ou 'N' alunos.</br>
