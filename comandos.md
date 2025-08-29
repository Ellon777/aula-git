# Comandos para git e Github
Neste arquivo iremos fazer um resumo de comandos para utilização do
git e Github nas aulas de Desenvolvimento Web da Fatec Jahu.

## Comandos do Terminal
Para ir até o C: ou qualquer raiz da unidade do Windows utilizamos a \
```bash
    cd \
```
**IMPORTANTE:** O CD troca de pastas no Prompt

Para criar pastas utilizamos o mkdir
```bash
    mkdir nome-da-pasta-sem-espaço
```

Para entrar na pasta criada utilizamos o cd
```bash
    cd nome-da-pasta-sem-espaço
```

Para abrir o explorer na pasta, chamamos ele com um ponto
```bash
    explorer .
```

Para voltar a pasta anterior utilizamos 2 pontos
```bash
    cd ..
```

> Estes comandos são utilizados para navegação do windows e devem ser 
repetidos conforme a necessidade de cada ação.

<br>

## Comando do Git
Para utilizar o git precisamos instalar no computador através do site:(https://git-scm.com/)

**OBSERVAÇÃO:** Para utilizar o git é necessário estar dentro da pasta do projeto que deseja versionar. <br>

**IMPORTANTE:** Não é possivel versionar uma pasta dentro de outra pasta que já está sendo versionada pelo git.

**CONFIGURAR O USUÁRIO E EMAIL**
```bash
    git config --global user.name "Elias Michelon"
    git config --global user.email xgamerblackwinter@gmail.com
```

Para começar a versionar uma pasta com git utilizamos o comando `init`:
**OBS:** Só é executado uma vez.
```bash
    git init
```

Podemos ver a situação do repositório a qualquer momento com `status`:
```bash
    git status
```

**VERMELHO:** Quando os arquivos estão em vermelho, foram criados ou editados e não estão prontos para serem salvos, precisa rodar o `add`:

O comando `add` prepara o arquivo para ser salvo, caso utilize com o nome do mesmo:
```bash
    git add nome-do-arquivo
```

E também prepara todos os arquivos para serem salvos da pasta em que estamos, caso utilize o ponto; `add .`:
```bash
    git add .
```

**VERDE:** Quando os arquivos estão verdes, já foram preparados para serem salvos, próximo passo é rodar o `commit`.

O comando `commit` salva as alterações de um ou mais arquivos que já passaram pela fase do `add`:
```bash
    git commit
```

Utilize `- m ""` para adicionar uma mensagem, caso esqueça o motivo de ter salvado:
```bash
    git commit -m "Mensagem"
```




