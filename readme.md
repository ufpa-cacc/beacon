# UFPA Computer Science Beacon

Repositório Git como um diário de estudo do **Curso de Ciência da Computação da UFPA**.

Diretórios:

  - [`log/`](log/readme.md): notas de aula.
 
  - [`task/`](task/readme.md): tarefas.

  - [`pin/`](pin/readme.md): coisas importantes para fazer em cada turma (referências a tarefas vigentes).

  - [`doc/`](about/readme.md): curiosidades.

Os nomes das disciplinas eventualmente podem aparecer abreviados. Algumas delas são cursadas em mais de uma fase (semestre) e em modalidade teórica ou prática (laboratório), mas a abreviação descarta essas especificidades.

Nomes abreviados de (algumas) disciplinas:

| Abreviação | Disciplina |
|-|-|
| funmat | fundamentos de matemática |
| lnalg | álgebra linear |
| algo | algoritmos |
| arch | organização e arquitetura de computadores |
| prog | programação |
| os | sistemas operacionais |
| calc | cálculo |
| hci | interação humano-computador |
| disc | matemática discreta |
| prob | probabilidade e estatística |
| struct | estruturas de dados |
| auto | linguagens formais e autômatos |

## Contribuição

Cada alteração é registrada no histórico por um commit, com um título conciso de idealmente até 60 caracteres, no seguinte formato:

```
tipo(escopo): mensagem
```

O `tipo` é aquilo que está sendo modificado, seguido de um `escopo` para especificar o alvo da modificação quando necessário, e a `mensagem` do título é uma descrição curta da modificação em si.

Cada nome de diretório (`log`, `task`, `pin` e `doc`) é um tipo de commit. Eles são os tipos principais. Seus respectivos readmes tem as informações sobre escopo.

Também existem os de manutenção, que servem só para manter o repositório organizado e tem como escopo opcional um tipo principal:

  - `chore`: tarefa simples, sem informações novas, como correções de erros de escrita.

  - `meta`: mudança estrutural ou de convenção.

Exemplos de commit de manutenção:

```
chore(log/2026-06-30): fix math formulas

meta: change date format from dd/mm/yyyy to yyyy-mm-dd

meta: add doc/ scope
```

O estilo das mensagens de commit é uma adaptação do [Conventional Commits](https://www.conventionalcommits.org).

---

> *Nos meus primeiros dois semestres eu não anotava nada e, bom, a falta de informação sempre virava uma bola de neve.*
>
> *Comecei a organizar as coisas melhor ao longo do terceiro semestre.*
>
> *As informações aqui estão longe de serem completas. Mas serve para mim. E é o que eu consigo deixar para talvez servir para alguém no futuro.*
>
> *Carinhosamente,*
>
> *Seruna*
>
> (❍ᴥ❍ʋ)
