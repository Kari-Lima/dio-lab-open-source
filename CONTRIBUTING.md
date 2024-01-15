<h1>
    <a href="https://www.dio.me/">
     <img align="center" width="40px" src="https://hermes.digitalinnovation.one/assets/diome/logo-minimized.png"></a>
    <span> Guia de Contribuição</span>
</h1>

[![Star](https://img.shields.io/github/stars/digitalinnovationone/dio-lab-open-source?style=social)](https://github.com/digitalinnovationone/dio-lab-open-source/stargazers)
[![Forks](https://img.shields.io/github/forks/digitalinnovationone/dio-lab-open-source?style=social)](https://github.com/digitalinnovationone/dio-lab-open-source/forks)
[![GitHub Issues](https://img.shields.io/github/issues/digitalinnovationone/dio-lab-open-source?style=social)](https://github.com/digitalinnovationone/dio-lab-open-source/issues/)

 Este é um projeto feito para a comunidade, então sinta-se livre para contribuir. Algumas formas de contribuição além do seu exemplo de Profile README, é inserir outros utilitários na pasta [`utils`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/utils), ou melhorar a página de pesquisa dos READMEs fazendo modificações nos arquivos da pasta [`docs`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/docs). <br>
 Além disso, você também pode contribuir:
 
⚠️ Resolvendo, respondendo ou indicando **issues**

⭐ Adicionando aos favoritos (**star**) 

##  Contribuindo no diretório "Community" 
 A contribuição no diretório "Community" faz parte do Desafio do lab **Contribuindo em um Projeto Open Source no GitHub** da [Digital Innovation One](https://www.dio.me/). Você pode colaborar criando um Profile README contendo informações sobre você que deseje compartilhar com a comunidade. Para isso, você pode inserir: badges indicando suas habilidades; cards com suas estatísticas no GitHub e projetos que criou, colaborou ou que deseje que outras pessoas colaborem. Além disso, você pode inserir também links para seus desafios de projeto e artigos na plataforma da [Digital Innovation One](https://www.dio.me/). <br>
 Inspire-se consultando os exemplos na pasta [`community`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/community), confira alguns utilitários na pasta [`utils`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/utils) e use sua criatividade para criar o seu 😊💙.

### Instruções
1. Faça um **Fork** deste repositório;
2. Clone localmente: `git clone https://github.com/SEU_USERNAME/dio-lab-open-source.git`;
3. Adicione o remote upstream para manter seu repositório local atualizado: `git remote add upstream https://github.com/elidianaandrade/dio-lab-open-source.git`;
    > Utilize o comando `git pull upstream main` para baixar e mesclar as alterações no seu repositório local com base na branch `main` deste repositório original de onde você fez o fork, ou `git fetch upstream main` para baixar sem mesclar. Veja mais em: [Primeiros Passos com Git e GitHub](https://github.com/elidianaandrade/dio-curso-git-github/blob/main/materiais-de-apoio/03-primeiros-passos-com-git-e-github.md).
4. Crie uma nova **branch** e nomeie como `feat/community/SEU_USERNAME`:
    > Exemplo: `git checkout -b feat/community/elidianaandrade`
5. Dentro da pasta [`community`](https://github.com/elidianaandrade/dio-lab-open-source/tree/main/community), crie um arquivo em Markdown (extensão `.md`) e nomeie com o mesmo nome do seu usuário no GitHub;
    > Exemplo: `community/elidianaandrade.md` <br>
6. Desenvolva o seu perfil. Para isso, você pode ver exemplos na pasta [`community`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/community) e adicionar alguns dos utilitários presentes na pasta [`utils`](https://github.com/digitalinnovationone/dio-lab-open-source/tree/main/utils);
    > **Observação:** Use os outros exemplos como inspiração e não cópia.
7. Adicione suas alterações à "staging area" com o comando `git add community/SEU_USERNAME.md`;
    > **Observação:** Você pode utilizar o comando `git add .` para adicionar todas as alterações de uma vez só.
8. Crie um commit e adicione a mensagem indicando a adição do seu perfil `git commit -m"feat: add SEU_USERNAME profile"`;
    > **Observação:** Verificar a [`Convenção de Commits`](https://github.com/kkademorais/dio-lab-open-source/blob/main/CONTRIBUTING.md#conven%C3%A7%C3%A3o-de-commits) para escrever a mensagem do seu commit de forma clara e padronizada.
9. Envie as alterações para o seu repositório remoto `git push origin feat/community/SEU_USERNAME`;
    > **Observação:** Você pode utilizar o comando `git push origin` para mandar as alterações sem precisar especificar a URL, desde que você tenha feito o passo **3**. 
10. Crie um **Pull Request**.

## Convenção de Commits 

| Tipo de Commit | Descrição|
| ---------------|----------|
| `feat`         | Adiciona uma nova funcionalidade ao projeto.   |
| `fix`          | Corrige um bug ou problema no projeto.         |
| `docs`         | Altera a documentação do projeto. Ex.: README, comentários no código.                                            |
| `style`        | Realiza mudanças na aparência, sem alterar a funcionalidade.                                                   |
| `refactor`     | Realiza mudanças no código que não alteram a funcionalidade.                                                   |
| `test`         | Adiciona ou modifica testes no projeto.        |

## Carregar commits para um repositório remoto
Use git pushpara enviar commits feitos na ramificação local para um repositório remoto.

## Acerca de`git push`
El comando `git push` toma dos argumentos:

Um nome remoto, por exemplo,`origin`
Um nome de filial, por exemplo,`main`
Por exemplo:

```git push REMOTE-NAME BRANCH-NAME```
Por exemplo, normalmente é executado git push origin mainpara enviar alterações locais ao repositório online.

## Renomear filiais
Para renomear uma ramificação, você teria que usar o mesmo comando ``git push``, mas adicionar mais um argumento: o nome da nova ramificação. Por exemplo:

```git push REMOTE-NAME LOCAL-BRANCH-NAME:REMOTE-BRANCH-NAME```

Isso é inserido ``LOCAL-BRANCH-NAME`` em ``REMOTE-NAME``, mas é renomeado para ``REMOTE-BRANCH-NAME``.
## Resolva erros sem encaminhamento rápido

Se a cópia local de um repositório estiver fora de sincronia ou "atrasada" em relação ao repositório upstream para o qual está sendo enviado, você receberá uma mensagem indicando ``non-fast-forward updates were rejected``. Isso significa que você deve recuperar as alterações upstream antes de poder enviar alterações locais.

Para obter mais informações sobre esse erro, consulte " Tratando erros sem encaminhamento rápido ".

## Subir etiquetas
Por padrão, e sem parâmetros adicionais, ``git pushele`` envia todas as ramificações correspondentes para terem o mesmo nome das ramificações remotas.

Para fazer upload de uma única tag, você pode emitir o mesmo comando usado para fazer upload de um branch:

``git push REMOTE-NAME TAG-NAME``

Para fazer upload de todas as suas tags, você pode digitar o comando:

``git push REMOTE-NAME --tags``

## Eliminar una etiqueta o rama remota
A sintaxe para excluir uma ramificação é um pouco enigmática à primeira vista:

``git push REMOTE-NAME :BRANCH-NAME``

Observe que há um espaço antes dos dois pontos. O comando se parece com as mesmas etapas que você executaria para renomear uma ramificação. Mas aqui você diz ao Git para não inserir nada en . Por esse motivo, exclui o branch do repositório remoto.``BRANCH-NAME`` ``REMOTE-NAME`` ``git push``

## Controles remotos e garfos
Você já deve saber que pode “fork” repositórios no GitHub.

Ao clonar um repositório de sua propriedade, você fornece a ele uma URL remota que informa ao Git onde recuperar e enviar atualizações. Se quiser colaborar com o repositório original, você precisará adicionar uma nova URL remota, geralmente chamada ``upstream``, ao clone local do Git:

``git remote add upstream THEIR_REMOTE_URL``

Agora você pode capturar atualizações e ramificações do seu fork:

```
git fetch upstream                                
# Grab the upstream remote's branches             
> remote: Counting objects: 75, done.             
> remote: Compressing objects: 100% (53/53), done.
> remote: Total 62 (delta 27), reused 44 (delta 9)
> Unpacking objects: 100% (62/62), done.          
> From https://github.com/OCTOCAT/REPO            
>  * [new branch]      main     -> upstream/main  

```

Quando terminar as alterações locais, você poderá enviar a ramificação local para o GitHub e iniciar uma solicitação pull .

Para obter mais informações sobre como trabalhar com ramificações, consulte " Sincronizando uma ramificação ".

## Desafios Git e GitHub
- [50 minutos de desafios para treino](https://www.youtube.com/watch?v=kB5e-gTAl_s)


## Referências
- [ANGULAR. Contributing to Angular](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md)
- [CONVENTIONAL COMMITS. Summary](https://www.conventionalcommits.org/en/v1.0.0/)
- [GITHUB. Configurar diretrizes para os contribuidores do repositório](https://docs.github.com/pt/communities/setting-up-your-project-for-healthy-contributions/setting-guidelines-for-repository-contributors)
