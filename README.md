# Nome do Projeto: Integra-o-API-RDSM---App-X
# Objetivo do projeto: Decrição das APIs consumidas pela integração 

## Descrição do Projeto

[Descrição detalhada do projeto e sua finalidade]

## Endpoints da API Consumidos

- [Consultar contato pelo uuid/email](https://developers.rdstation.com/reference/get_platform-contacts-identifier-value)
- [Endpoint 2](#endpoint-2)
- [Endpoint 3](#endpoint-3)
- ...

| API          | Endpoint | Descrição   | É utilizado pela aplicação? | É personalizável | Envia campos personalizados? | Envia tags? | Envia a Origem? | Envia Bases Legais? | Observações |  
|----------------|---------------|---------------|----------------|-----------|-----------|-----------|-----------|-----------|-----------|
| API de Contatos | [Consultar contato pelo uuid/email](https://developers.rdstation.com/reference/get_platform-contacts-identifier-value) | Retorna dados de um contato específico. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Contatos | [Criar contato](https://developers.rdstation.com/reference/post_platform-contacts) | Cria um contato na Base de Leads. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |  | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | ... |
| API de Contatos | [Atualizar contato pelo uuid/email](https://developers.rdstation.com/reference/patch_platform-contacts-identifier-value) | Cria ou atualiza um contato existente na Base de Leads. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |  | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | ... |
| API de Contatos | [Excluir contato pelo uuid/email](https://developers.rdstation.com/reference/delete_platform-contacts-identifier-value) | Deleta um contato específico. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Contatos | [Criar uma tag para o lead pelo uuid/email](https://developers.rdstation.com/reference/post_platform-contacts-identifier-value-tag)  | Apenas atualiza um novo contato na Base de Leads. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul>  | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Contatos | [Consultar eventos associado ao contato](https://developers.rdstation.com/reference/get_platform-contacts-uuid-events) | Retorna uma lista de eventos associados ao contato. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Contatos | [Melhor Horário para Mensagem](https://developers.rdstation.com/reference/best-time-to-message) | Prevê o melhor horário para enviar uma mensagem através de algoritmos de inteligência artificial. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Campos Personalizados   | [Consultar campo personalizado](https://developers.rdstation.com/reference/get_platform-contacts-fields) | Retorna os campos e seus atributos. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Campos Personalizados   | [Criar campo personalizado](https://developers.rdstation.com/reference/post_platform-contacts-fields) | Criar campo personalizado. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Campos Personalizados   | [Atualizar campo personalizado](https://developers.rdstation.com/reference/patch_platform-contacts-fields-uuid) | Atualizar campo personalizado. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Campos Personalizados   | [Excluir campo personalizado](https://developers.rdstation.com/reference/delete_platform-contacts-fields-uuid) | Exclui um campo personalizado. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Eventos   | [Eventos de Conversão Padrão]()  |  Esse evento é registrado sempre que ocorre uma conversão. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |  | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | ... |
| API de Eventos   | [Evento de Marcação de Oportunidade]()  |  O evento de Marcação de Oportunidade, registra a marcação de um contato como oportunidade no RD Station Marketing. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Eventos   | [Evento de Marcação de Oportunidade Ganha]()  |  O evento de Marcação de Oportunidade Ganha, registra um contato como oportunidade ganha no RD Station Marketing. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | | | | | Envia o valor da venda? <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Eventos   | [Evento de Marcação de Oportunidade Perdida]()  |  O evento de Marcação de Oportunidade Perdida, registra um contato como oportunidade perdida no RD Station Marketing. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | | | | | Envia o motivo da perda? <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Eventos   | [Evento de Fechamento de Pedido]()  |  Esse evento é registrado sempre que ocorre o fechamento de pedido em uma plataforma de e-commerce. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | | | | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |  |
| API de Eventos   | [Evento de Fechamento de Pedido com um Item específico]()  |  Esse evento é registrado sempre que ocorre o fechamento de pedido com um item específico em uma plataforma de e-commerce. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | | | | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |  |
| API de Eventos   | [Evento de Abandono de Carrinho]()  |  Esse evento é registrado sempre que ocorre o abandono de carrinho em uma plataforma de e-commerce. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | | | | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |  |
| API de Eventos   | [Evento de Abandono de um Item do Carrinho]()  |  Esse evento é registrado sempre que ocorre o abandono de carrinho com um item específico em uma plataforma de e-commerce. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | | | | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |  |
| API de Eventos   | [Evento de Início da Conversa]()  |  Esse evento é registrado sempre que ocorre o início de uma conversa em um chat. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | | | | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |  |
| API de Eventos   | [Evento de Término da Conversa]()  |  Esse evento é registrado sempre que ocorre o término de uma conversa em um chat. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | | | | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |  |
| API de Eventos   | [Evento de Chamada Concluída]()  |  Esse evento é registrado sempre que uma chamada é concluída. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | | | | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |  |
| API de Eventos   | [Evento de Início do Playback de uma Mídia]()  |  Esse evento é registrado sempre que ocorre o início do playback de uma mídia. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | | | | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |  |
| API de Eventos   | [Evento de Término do Playback de uma Mídia]()  |  Esse evento é registrado sempre que ocorre o término do playback de uma mídia. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | | | | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |  |
| API de Eventos   | [Batch de Eventos]()  |  O endpoint de grupo de eventos permite que o RD Station receba mais de um evento ao mesmo tempo. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |  | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | ... |
| API de Funis de Contatos   | [Consultar pelo UUID/email do contato](https://developers.rdstation.com/reference/get_platform-contacts-identifier-value-funnels-default) | Retorna uma lista de Funis associados ao contato. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Funis de Contatos   | [Atualizar pelo UUID/email do contato](https://developers.rdstation.com/reference/put_platform-contacts-identifier-value-funnels-default) | Atualiza as informações do funil associado ao contato. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | | | | | Marca oportunidade? <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> <br> Atualiza o Dono do Lead? <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Segmentações   | [Consultar segmentações](https://developers.rdstation.com/reference/get_platform-segmentations)  | Retorna uma lista de segmentações da conta. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Segmentações   | [Consultar contatos de uma segmentação](https://developers.rdstation.com/reference/get_platform-segmentations-id-contacts)  | Retorna uma lista de contatos associados a uma segmentação. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Fluxo de Automação   | [Consultar fluxos de automação](https://developers.rdstation.com/reference/get_platform-workflows)  | Retorna uma lista com os fluxos de automação. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Fluxo de Automação   | [Consultar dados de um fluxo a partir de um id](https://developers.rdstation.com/reference/get_platform-workflows-id)  | Retorna informações das ações de um fluxo de automação. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Fluxo de Automação   | [Inserir leads em um fluxo](https://developers.rdstation.com/reference/post_platform-workflows-id-leads)  | Permite inserir leads num fluxo de automação. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>[x] item1</li><li>[ ] item2</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Fluxo de Automação   | [Consultar leads que iniciaram um fluxo](https://developers.rdstation.com/reference/get_platform-workflows-id-leads-started)  | Retorna uma lista com os leads que iniciaram um fluxo de automação. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Fluxo de Automação   | [Consultar leads que encerraram um fluxo](https://developers.rdstation.com/reference/get_platform-workflows-id-leads-left)  | Retorna uma lista com os leads que encerraram um fluxo de automação. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Fluxo de Automação   | [Consultar leads que atingiram uma ação específica de um fluxo](https://developers.rdstation.com/reference/get_platform-workflows-id-leads-action-action-id)  | Retorna uma lista com os leads que atingiram uma ação específica de um fluxo. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>[x] item1</li><li>[ ] item2</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Email   | [Listar todos os emails](https://developers.rdstation.com/reference/get_platform-emails)  | Consultar lista de emails. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Email   | [Buscar email por id](https://developers.rdstation.com/reference/get_platform-emails-id)  | Consultar lista de emails da conta. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Landing Pages   | [Consultar landing pages](https://developers.rdstation.com/reference/get_platform-landing-pages)  | Retorna uma lista com todas as landing pages de uma conta. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Pop-ups  | [Consultar pop-ups](https://developers.rdstation.com/reference/get_platform-popups)  | Retorna uma lista com todos os pop-ups de uma conta. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Formulários   | [Consultar formulários](https://developers.rdstation.com/reference/get_platform-embeddables)  | Retorna uma lista com todos os formulários de uma conta. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Webhooks   | [Listar todos os webhooks](https://developers.rdstation.com/reference/get_integrations-webhooks)  | Retorna uma lista com todos os Webhooks criados pelo seu aplicativo na conta que ele está vinculado. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Webhooks   | [Criar um webhook](https://developers.rdstation.com/reference/post_integrations-webhooks)  | Cria uma assinatura de webhook. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | | | | | Cria Webhook de "Conversão?" <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> <br> Cria Webhook de "Marcação de Oportunidade?" <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> <br> É possível criar mais de um Webhook?" <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> <br> A aplicação fornece URL de Integração para criar o Webhook manualmente?" <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Webhooks   | [Atualizar webhook pelo uuid](https://developers.rdstation.com/reference/put_integrations-webhooks-uuid)  | Atualiza uma assinatura de webhook. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | | | | | É possível atualizar o tipo do Webhook?" <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |
| API de Webhooks   | [Deletar um webhook](https://developers.rdstation.com/reference/delete_integrations-webhooks-uuid)  | Deleta uma assinatura de webhook da conta atual. | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> | <ul><li>- [ ] Sim</li><li>- [ ] Não</li></ul> |


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
