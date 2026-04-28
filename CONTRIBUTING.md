# Como Contribuir

Obrigado por participar da turma! Siga as instruções abaixo para enviar seus trabalhos corretamente.

## 1. Fork e Clone

```bash
# Faça fork pelo GitHub, depois clone o seu fork
git clone https://github.com/SEU_USUARIO/turma-visualizacao-de-dados.git
cd turma-visualizacao-de-dados
```

## 2. Configure o upstream

```bash
git remote add upstream https://github.com/cfneves/turma-visualizacao-de-dados.git
```

## 3. Crie sua pasta de aluno

Dentro de `alunos/`, crie uma pasta com seu nome (sem espaços, letras minúsculas):

```
alunos/
└── nome-sobrenome/
    ├── README.md       ← Apresentação pessoal (opcional)
    ├── exercicios/
    └── projetos/
```

## 4. Crie uma branch para cada entrega

```bash
git checkout -b exercicio-01-nome-sobrenome
```

## 5. Commit e Push

```bash
git add .
git commit -m "feat(alunos): adiciona exercício 01 - Nome Sobrenome"
git push origin exercicio-01-nome-sobrenome
```

## 6. Abra um Pull Request

- Vá até o repositório original no GitHub
- Clique em **New Pull Request**
- Preencha o template disponível
- Aguarde o review

## Convenção de Commits

| Prefixo | Uso |
|---------|-----|
| `feat`  | Nova entrega ou exercício |
| `fix`   | Correção de algo enviado |
| `docs`  | Atualização de documentação |
| `data`  | Adição de dataset |

## Dúvidas

Abra uma **Issue** com a tag `[dúvida]` no título.
