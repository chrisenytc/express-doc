ExpressDoc
=======

Translation of ExpressJS Documentation for the Portuguese language.

### Informações

A Tradução da Documentação está em andamento e você poderar ver como está o status e também contribuir para a tradução.

### Status

Traduzidos:

    * faq.jade
    * error-handling.jade

Em Processo:

    * executable.jade

### Como Contribuir

Para contribuir você precisa seguir os seguintes passos.

Passos:

    1. Fazer um Fork do Repositório.
    2. Clonar o Repositório
    3. Ler os Padrões do Projeto
    4. Traduzir
    5. Testar a Tradução
    6. Enviar um Pull Request

### Padrões do Projeto

Para organizar e melhorar a qualidade do projeto vai ser preciso seguir alguns padrões.

Commits:

Nas mensagens dos seus commits vamos seguir algus padrões como:

-- Enviando Traduções

  git commit -m "Translate: filename.jade"

Para mais de um arquivo:

    git commit -m "Translate: filename.jade, filename2.jade and filename3.jade"

Atenção: Para mais de um arquivo sempre o último tem o `and` e o restanto do começo separado por vírgula com espaços entre as vírgulas como no exemplo.

-- Enviando Correções

Caso você tenha errado alguma coisa no arquivo ou não saiu como planejado depois de testar e ler no GitHub. Você pode corrigir o arquivo e fazer um novo commit seguindo o exemplo:

    git commit -m "FixError: filename.jade"

    git commit -m "FixError: filename.jade, filename2.jade and filename3.jade"

O mesmo segue as regras de cima só que mudando a palavra para `FixError`.

### Testar a Tradução

Para Testar a tradução e ver como está ficando você vai precisar ter o `jade` e o `serve` instalado , caso não tenha instale:

    > sudo npm install -g jade
    > sudo npm install -g serve

Depois de instalado você pode converter seus arquivos `.jade` em `.html` com o seguinte comando:

    > jade {guide,api,faq}.jade

Se tudo deu certo, foram criados 3 arquivos `.html`: `guide.html`, `api.html` e `faq.html`.
Para testar no navegador vamos usar o `serve`.
Estando dentro da pasta onde estão os 3 arquivos.html execute o seguinte comando.

    > serve . &

O servidor estará online em http://localhost:3000


### Enviando Pull Request

Depois de testar, ler e revisar sua tradução, é hora de fazer um Pull Request. Após fazer o Pull Request, sua tradução será analisada e se estiver tudo certo será aceita e seu nome será referenciado como colaborador do projeto na Documentação. Você ajudará muitas pessoas na comunidade Node.js da lingua Portuguesa.

Depois de finalizada a tradução completa, será compilado os arquivos e a Documentação estará online em: [Express Doc](http://chrisenytc.github.io/docs/expressjs)


## Conclusão

Seguindo esses passos você poderar contribuir com o projeto e ajudar milhares de pessoas que irão usar as traduções.

Você também pode ver ou contribuir com outros projetos de traduções nos links abaixo:

* [Docs Lists](http://chrisenytc.github.io/docs/)
* [Chris Blog](http://chris.enytc.com)
