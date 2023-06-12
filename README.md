# Nome do Projeto: Integra-o-API-RDSM---App-X
# Objetivo do projeto: Decrição das APIs consumidas pela integração 

## Descrição do Projeto

[Descrição detalhada do projeto e sua finalidade]

## Endpoints da API Consumidos

- [Consultar contato pelo uuid/email](https://developers.rdstation.com/reference/get_platform-contacts-identifier-value)
- [Endpoint 2](#endpoint-2)
- [Endpoint 3](#endpoint-3)
- ...

| API          | Endpoint | Descrição   | É utilizado pela aplicação? | É personalizável | 
|----------------|---------------|---------------|----------------|-----------|
| API de Contatos | [Consultar contato pelo uuid/email](https://developers.rdstation.com/reference/get_platform-contacts-identifier-value) |  | Retorna dados de um contato específico. | <ul><li>- [x] item1</li><li>- [ ] item2</li></ul> <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Contatos | [Criar contato](https://developers.rdstation.com/reference/post_platform-contacts)) |  | Cria um contato na Base de Leads | <ul><li>- [x] item1</li><li>- [ ] item2</li></ul> <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Contatos | [Atualizar contato pelo uuid/email](https://developers.rdstation.com/reference/patch_platform-contacts-identifier-value) |  | Cria ou atualiza um contato existente na Base de Leads. | <ul><li>- [x] item1</li><li>- [ ] item2</li></ul> <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Contatos | [Excluir contato pelo uuid/email](https://developers.rdstation.com/reference/delete_platform-contacts-identifier-value) |  | Deleta um contato específico. | <ul><li>- [x] item1</li><li>- [ ] item2</li></ul> <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Contatos | [Criar uma tag para o lead pelo uuid/email](https://developers.rdstation.com/reference/post_platform-contacts-identifier-value-tag) |  | Apenas atualiza um novo contato na Base de Leads | <ul><li>- [x] item1</li><li>- [ ] item2</li></ul> <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Contatos | [Consultar eventos associado ao contato](https://developers.rdstation.com/reference/get_platform-contacts-uuid-events) |  | Retorna uma lista de eventos associados ao contato. | <ul><li>- [x] item1</li><li>- [ ] item2</li></ul> <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Contatos | [Melhor Horário para Mensagem](https://developers.rdstation.com/reference/best-time-to-message) |  | Prevê o melhor horário para enviar uma mensagem através de algoritmos de inteligência artificial. | <ul><li>- [x] item1</li><li>- [ ] item2</li></ul> <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Campos Personalizados   | [Consultar campo personalizado](https://developers.rdstation.com/reference/get_platform-contacts-fields) |  | Retorna os campos e seus atributos.  | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Campos Personalizados   | [Criar campo personalizado](https://developers.rdstation.com/reference/post_platform-contacts-fields) |  | Criar campo personalizado. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Campos Personalizados   | [Atualizar campo personalizado](https://developers.rdstation.com/reference/patch_platform-contacts-fields-uuid) |  | Atualiza campo personalizado. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Campos Personalizados   | [Excluir campo personalizado](https://developers.rdstation.com/reference/delete_platform-contacts-fields-uuid) |  | Exclui um campo personalizado. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Eventos   | > 5 hours  |  | in progress | <ul><li>- [x] item1</li><li>- [ ] item2</li></ul> |
| API de Funis de Contatos   | [Consultar pelo UUID/email do contato](https://developers.rdstation.com/reference/get_platform-contacts-identifier-value-funnels-default)  |  | Retorna uma lista de Funis associados ao contato. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Funis de Contatos   | [Atualizar pelo UUID/email do contato](https://developers.rdstation.com/reference/put_platform-contacts-identifier-value-funnels-default)  |  | Atualiza as informações do funil associado ao contato. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Segmentações   | [Consultar segmentações](https://developers.rdstation.com/reference/get_platform-segmentations)  |  | Retorna uma lista de segmentações da conta. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Segmentações   | [Consultar contatos de uma segmentação](https://developers.rdstation.com/reference/get_platform-segmentations-id-contacts)  |  | Retorna uma lista de contatos associados a uma segmentação. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Fluxo de Automação   | [Consultar fluxos de automação](https://developers.rdstation.com/reference/get_platform-workflows)  |  | Retorna uma lista com os fluxos de automação. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Fluxo de Automação   | [Consultar dados de um fluxo a partir de um id](https://developers.rdstation.com/reference/get_platform-workflows-id)  |  | Retorna informações das ações de um fluxo de automação. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Fluxo de Automação   | [Inserir leads em um fluxo](https://developers.rdstation.com/reference/post_platform-workflows-id-leads)  |  | Permite inserir leads num fluxo de automação. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Fluxo de Automação   | [Consultar leads que iniciaram um fluxo](https://developers.rdstation.com/reference/get_platform-workflows-id-leads-started)  |  | Retorna uma lista com os leads que iniciaram um fluxo de automação. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Fluxo de Automação   | [Consultar leads que encerraram um fluxo](https://developers.rdstation.com/reference/get_platform-workflows-id-leads-left)  |  | Retorna uma lista com os leads que encerraram um fluxo de automação. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Fluxo de Automação   | [Consultar leads que atingiram uma ação específica de um fluxo](https://developers.rdstation.com/reference/get_platform-workflows-id-leads-action-action-id)  |  | Retorna uma lista com os leads que atingiram uma ação específica de um fluxo. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Email   | [Listar todos os emails](https://developers.rdstation.com/reference/get_platform-emails)  |  | in progress | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Email   | [Buscar email por id](https://developers.rdstation.com/reference/get_platform-emails-id)  |  | Consultar lista de emails da conta. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Landing Pages   | [Consultar landing pages](https://developers.rdstation.com/reference/get_platform-landing-pages)  |  | Retorna uma lista com todas as landing pages de uma conta. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Pop-ups  | [Consultar pop-ups](https://developers.rdstation.com/reference/get_platform-popups)  |  | Retorna uma lista com todos os pop-ups de uma conta | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Formulários   | [Consultar formulários](https://developers.rdstation.com/reference/get_platform-embeddables)  |  | Retorna uma lista com todos os formulários de uma conta. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Webhooks   | [Listar todos os webhooks](https://developers.rdstation.com/reference/get_integrations-webhooks)  |  | Retorna uma lista com todos os Webhooks criados pelo seu aplicativo na conta que ele está vinculado. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Webhooks   | [Criar um webhook](https://developers.rdstation.com/reference/post_integrations-webhooks)  |  | Cria uma assinatura de webhook. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Webhooks   | [Atualizar webhook pelo uuid](https://developers.rdstation.com/reference/put_integrations-webhooks-uuid)  |  | Atualiza uma assinatura de webhook. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |
| API de Webhooks   | [Deletar um webhook](https://developers.rdstation.com/reference/delete_integrations-webhooks-uuid)  |  | Deleta uma assinatura de webhook da conta atual. | <ul><li>[x] item1</li><li>[ ] item2</li></ul> |


## Como a Aplicação Engatilha os Endpoints

### Endpoint 1

[Descreva aqui as ações ou eventos na plataforma que acionam o consumo do Endpoint 1]

### Endpoint 2

[Descreva aqui as ações ou eventos na plataforma que acionam o consumo do Endpoint 2]

### Endpoint 3

[Descreva aqui as ações ou eventos na plataforma que acionam o consumo do Endpoint 3]

...

## Conteúdo da Requisição de Cada Endpoint

### Endpoint 1

- Método HTTP: [GET/POST/PUT/DELETE]
- URL: [URL completa do Endpoint 1]
- Dados enviados na requisição:
  - [Parâmetro 1]: [Descrição do parâmetro 1]
  - [Parâmetro 2]: [Descrição do parâmetro 2]
  - ...

### Endpoint 2

- Método HTTP: [GET/POST/PUT/DELETE]
- URL: [URL completa do Endpoint 2]
- Dados enviados na requisição:
  - [Parâmetro 1]: [Descrição do parâmetro 1]
  - [Parâmetro 2]: [Descrição do parâmetro 2]
  - ...

### Endpoint 3

- Método HTTP: [GET/POST/PUT/DELETE]
- URL: [URL completa do Endpoint 3]
- Dados enviados na requisição:
  - [Parâmetro 1]: [Descrição do parâmetro 1]
  - [Parâmetro 2]: [Descrição do parâmetro 2]
  - ...

...
