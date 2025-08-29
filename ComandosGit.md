# Comandos para git e github
Neste arquivo iremos fazer um resumo de comandos para a utilização do Git e Github nas aulas de Desenvolvimento Web da Fatec Jahu.

# Comandos do Terminal
Para ir até o C: ou qualquer raiz da unidade do Windows utilizamos a \
``` bash cd \ ```

**IMPORTANTE:** O CD troca de pastas no Prompt.

Para criar pastas utilizamos o mkdir
```bash mkdir nome-da-pasta-sem-espaço ```

Para entrar na pasta criada utilizamos o CD
```bash cd nome-da-pasta ```

Para abrir o explorer na pastra chamamos ele com um ponto
```bash explorer . ```

Para voltar a pasta anterior utilizamos 2 pontos
```bash cd .. ``` 

## Comando do Git
Para utilizar o git precisamos instalar no computador através do site:(https://git-scm.com/)


**Observação** Para utilizar o git é necessário estar dentro da pasta do projeto que deseja versionar.

**Importante** Não é possível versionar uma pasta dentro de outra pasta que já está sendo versionada pelo git. 

**Configurar o usuário e e-mail**
```bash
git config --global user.name "Samuel Custódio dos Santos"
git config --global user.email samuelcustodiosantos2020@gmail.com
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

**VERMELHO:** Quando os arquivos estão em vermelho, foram criados ou editados e não estão prontos para serem salvos, precisa rodar o `add`.

**Verde:** Quando os arquivos estão verdes, já foram preparados para serem salvos, próximo passo é rodar o `commit`.

Para escolher o que será "comitado", ou seja, eviado a nuvem, usamos o `add`
```bash
git add
```

Para enviar as alterações para a nuvem usamos o `commit`
```bash
git commit
``` 
 
