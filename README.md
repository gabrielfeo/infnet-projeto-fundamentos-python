# infnet-projeto-fundamentos-python

Este repositório contém um esqueleto das classes que você deve implementar como parte do projeto. Cada classe da pasta [projeto](/projeto) é um esqueleto, por exemplo:

```python
class Trabalhador:
  def receber_aumento(self, novo_salario):
    pass
```

Você deve implementar o estado e implementar cada função (comportamento):

```python
class Trabalhador:
  def __init__(self, salario_atual):
    self.salario = salario_atual

  def receber_aumento(self, novo_salario):
    self.salario = novo_salario
```

## Projeto Back-End Sistema Acadêmico

Simule a operação do Moodle implementando pelo menos 4 propriedades (estado) para as seguintes classes do domínio:

- Turma
- Disciplina
- Aluno
- Professor

Operações (comportamento) que devem ser implementadas:

- Alunos matriculam-se em turmas
- Uma turma está associada a uma disciplina lecionada por um professor
- Professores avaliam AT de alunos nas turmas das disciplinas que lecionam
- Aluno escolhe um professor orientador
- CR de um aluno é a média da nota desse aluno em todas as turmas que ele cursou
