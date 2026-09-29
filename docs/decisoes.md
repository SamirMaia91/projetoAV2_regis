# Decisões do Projeto

## Integração das Features

As features dos alunos B e C foram integradas à branch develop.

Durante a integração, não foram identificados conflitos automáticos pelo Git nos arquivos index.html, styles.css e app.js.

### Decisões da equipe

A equipe optou por manter as alterações realizadas pelos dois alunos, garantindo a integração das funcionalidades desenvolvidas nas respectivas features.

A branch develop foi utilizada como branch de integração das funcionalidades antes da próxima etapa do fluxo Git Flow.

## Release 1.0.0

Foi criada a branch release/1.0.0 a partir da develop.

A versão do projeto foi atualizada para 1.0.0, foram adicionadas as release notes e a release foi integrada à branch main.

Também foi criada e enviada ao GitHub a tag v1.0.0.

## Hotfix

Após a release, foi identificado um problema no título da aplicação ao retornar do modo escuro para o modo claro.

Para corrigir o problema, foi criada a branch hotfix/titulo-claro a partir da main.

A correção foi realizada no arquivo app.js, fazendo com que o título retornasse corretamente para Mini App – GitFlow 1.0.0.

Após a correção, o hotfix foi integrado diretamente à branch main e posteriormente sincronizado com a branch develop.

## Conflitos e decisões

Durante as integrações das features, não ocorreram conflitos automáticos de merge que exigissem resolução manual.

O problema identificado no título ao retornar para o modo claro foi tratado como um hotfix da aplicação. A equipe registrou a correção e manteve a alteração nas branches main e develop.

## Resultado

Ao final do fluxo Git Flow, as branches main e develop foram atualizadas com as funcionalidades integradas e a correção do hotfix.

A versão v1.0.0 foi criada e enviada ao GitHub.
