# Controle de Versão com GIT

Esse projeto tem o objetivo de apresentar o git e github para práticas nas fábricas da desenvolvimento na disciplina de engenharia de software na Unijuazeiro. Os conceitos iniciais do capítulo apresentado se encontram na [parte 1 do slide de gerencia da configuração de software](https://slides.com/samuelclerod/cg-parte1) .

## Comandos básicos

- **status**: Verica o estado do projeto (*work directory/staging area/repository*);

- **add**: adiciona arquivos ao *staging area* do git;

- **commit**: cria a revisão a partir dos arquivos adicinados no *staging area*. Verifique padrões de mensagens em [Conventional Commits](https://www.conventionalcommits.org/pt-br/v1.0.0-beta.4/), compatíveis com o [versionamento semântico](https://www.google.com/search?q=versionamento+semantico&oq=versionamento+semantico&aqs=chrome.0.69i59l2j0l2.8031j0j7&sourceid=chrome&ie=UTF-8);

- **diff**: Mostra as mudanças entre commits, arquivos ou do com o staging area.

- **resert**: Desfaz mudanças;

- **log**: Mostra histórico de revisões (*commits*), podenso ser visto em uma linha com a *flag* `--oneline` ou de forma gráfica utilizando `--graph` , ou personalize conforme descrito por [Will Anderson](https://willi.am/blog/2015/02/19/customize-your-git-log-format/);

- **checkout**: permite navegar entre commits;

- **branch**: cria novas branch. É possível criar ainda utilizando o comando `git checkout -b <nomeDaBranch>`, o qual cria e navega diretamente para a branch;

- **remote**: permite executar operações com repositorios remotos;

- **fetch**: faz download do rempositório remoto;

- **pull**: fez download e merge do rempositório remoto, incorporando as mudanças também no workspace;

- **push**: sincroniza o repositóro local com o repositório remoto;

- **tag**: comando utilizado para identificar as versões liberadas. Comumente segue [versionamento semantico](https://semver.org/lang/pt-BR/).

## Conceitos/Recursos do Github

 - **Issues**: Problemas, bugs, solicitações de mudanças, adicição features/funcionalidades, solictadas pela equipe ou por algum usuário ou pessoa externa equipe de manutenção do projeto. É um forma de formalizar todas as mudanças que o projeto sofre. É possível fechar automaticamente a issue fazendo referencia com o id da Issue na mensagem de commit.
 
