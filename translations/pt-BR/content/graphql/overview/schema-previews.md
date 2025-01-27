---
title: Pré-visualizações de esquema
intro: 'Você pode visualizar os próximos recursos e alterações para o esquema do GraphQL do {% data variables.product.prodname_dotcom %} antes de eles serem adicionados à API do GraphQL de {% data variables.product.prodname_dotcom %}.'
redirect_from:
  - /v4/previews
versions:
  fpt: '*'
  ghec: '*'
  ghes: '*'
  ghae: '*'
topics:
  - API
---

## Sobre pré-visualizações de esquemas

Durante o período de pré-visualização, poderemos alterar alguns recursos com base no feedback do desenvolvedor. Se fizermos alterações, iremos anunciá-las no [blogue do desenvolvedor](https://developer.github.com/changes/) sem aviso prévio.

Para acessar uma pré-visualização de esquema, você deverá fornecer um [tipo de mídia personalizado](/rest/overview/media-types) no cabeçalho `Aceitar` para as suas solicitações. A documentação dos recursos para cada pré-visualização especifica qual tipo de mídia personalizado deve ser fornecido.

{% note %}

**Observação:** Os integrantes do esquema do GraphQL na pré-visualização não podem ser acessados pelo Explorador no momento.

{% endnote %}
