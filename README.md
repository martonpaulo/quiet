# quiet

Nossa missão é reduzir os conflitos causados pela poluição sonora. Criamos uma aplicação na qual é possível reportar incômodos e registrar eventos, a fim de melhorar a comunicação dos incomodados com os organizadores.

<br>

## Sobre o gerenciamento do projeto

O gerenciamento do projeto é feito pelo próprio GitHub. As issues abertas são atribuídas a um ou mais membros da equipe, e elas são agrupadas em quatro milestones, que são nossos módulos:
- [ ] [Frontend](https://github.com/martonpss/quiet/);
- [ ] Backend;
- [ ] Banco de Dados;
- [ ] [Hardware](https://github.com/costa402/quiet-esp32).

<br>

## Para os desenvolvedores

### Configuração do ambiente

Para rodar o projeto na sua máquina, tenha instalados [Node.js](https://nodejs.org/en/download/), [npm](https://www.npmjs.com/get-npm) e [Yarn](https://yarnpkg.com/docs/install).
* **Passo 1**: clone este repositório na sua máquina;
* **Passo 2**: rode `$ npm install` na raiz do projeto;
* **Passo 3**: rode `$ yarn start`, e automaticamente se abrirá uma página no seu navegador.

Se houver o erro ```npm ERR! Cannot read property 'match' of undefined```, rode o comando:
```bash
$ rm -rf package-lock.json node_modules
```

### Para rodar os testes

Acesse a pasta ```src``` e rode o comando ```mocha```:
``` bash
$ cd src
$ mocha
```

Atenção para o Chromedrive, ele deve ser compatível com a versão do seu navegador. Faça o download nesse [link](http://chromedriver.storage.googleapis.com/index.html) e substitua pelo existente na pasta ```src```.

### Adição de tags

Do repositório local, use as seguintes linhas de comando:
```bash
$ git tag -a v0.X -m "Comentário com a principal novidade da release"
$ git push --follow-tags
```

### Boas práticas

* Mantenha os comentários do código, commits e issues abertas em português;
* Não faça commits na branch principal. Ao final do dia, um responsável passará os commits para a branch principal.

<br>

## Observações

Migramos o projeto para esse repositório. É possível acessar os antigos em:
* https://github.com/naftalima/quiet
* https://github.com/igormp/quiet-backend
