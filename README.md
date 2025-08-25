<p align="center">
  <a href="https://onsac.com/">
    <img src="https://github.com/onsac/Libera-o-de-Acessos-do-Sienge/blob/main/onsac_01.png" width="200" height="100" >
  </a>
</p>
<p align="center">
 Integração e  Automação em tempo real
  <br>
  <a href="https://onsac.com/"><strong>Conheça mais sobre nosso serviço »</strong></a>
  </p>

## Parceria OnSAC com Sienge 
<p align="center">
     <img src="https://github.com/onsac/Libera-o-de-Acessos-do-Sienge/blob/main/OnSAC%20%2B%20Sienge.png" >
</p>

A parceria entre a OnSAC e o Sienge é uma colaboração estratégica para fornecer soluções de automação e integração para empresas da construção civil. A OnSAC possui expertise em automação de processos de negócio e integração de sistemas, enquanto o Sienge é um software especializado em gestão para o setor da construção.
Essa parceria visa oferecer aos clientes do Sienge a possibilidade de automatizar e otimizar seus processos, como o lançamento de notas fiscais, validação de pedidos, entre outros. A integração entre os sistemas permite uma maior eficiência operacional, redução de erros e agilidade nos pagamentos.



## Liberação de acessos de API’s do Sienge


Processo de enriquecimento para Validação de Notas Fiscais


Empreendimentos (Obras): https://api.sienge.com.br/docs/?utm_source=cpc_google-pmax-ads&utm_medium=cpc&utm_content=plataforma&utm_campaign=f2-p1p2p3p4-performance-max&gad_source=1&gclid=CjwKCAjw-qi_BhBxEiwAkxvbkFxSbFO_3ZPyWh8BheBH7R2gi44PvSI-Rz6hodUfvG-u49qYlgyFHxoCnGwQAvD_BwE#/enterprise-v1

sh ```
| Verbo | API |
| --- | --- |
| GET | /enterprises |
```
Credores: https://api.sienge.com.br/docs/?utm_source=cpc_google-pmax-ads&utm_medium=cpc&utm_content=plataforma&utm_campaign=f2-p1p2p3p4-performance-max&gad_source=1&gclid=CjwKCAjw-qi_BhBxEiwAkxvbkFxSbFO_3ZPyWh8BheBH7R2gi44PvSI-Rz6hodUfvG-u49qYlgyFHxoCnGwQAvD_BwE#/creditor-v1
```
| Verbo | API |
| --- | --- |
| GET | /companies |
```

Centro de Custos: https://api.sienge.com.br/docs/?utm_source=cpc_google-pmax-ads&utm_medium=cpc&utm_content=plataforma&utm_campaign=f2-p1p2p3p4-performance-max&gad_source=1&gclid=CjwKCAjw-qi_BhBxEiwAkxvbkFxSbFO_3ZPyWh8BheBH7R2gi44PvSI-Rz6hodUfvG-u49qYlgyFHxoCnGwQAvD_BwE#/cost-center-v1
```
| Verbo | API |
| --- | --- |
| GET | /cost-centers |
```

Credores: https://api.sienge.com.br/docs/?utm_source=cpc_google-pmax-ads&utm_medium=cpc&utm_content=plataforma&utm_campaign=f2-p1p2p3p4-performance-max&gad_source=1&gclid=CjwKCAjw-qi_BhBxEiwAkxvbkFxSbFO_3ZPyWh8BheBH7R2gi44PvSI-Rz6hodUfvG-u49qYlgyFHxoCnGwQAvD_BwE#/creditor-v1
```
| Verbo | API |
| --- | --- |
| GET | /creditors |
| POST | /creditors |
```

Processo de verificação de Lançamento de Notas Fiscais

Títulos do Contas a Pagar: https://api.sienge.com.br/docs/?utm_source=cpc_google-pmax-ads&utm_medium=cpc&utm_content=plataforma&utm_campaign=f2-p1p2p3p4-performance-max&gad_source=1&gclid=CjwKCAjw-qi_BhBxEiwAkxvbkFxSbFO_3ZPyWh8BheBH7R2gi44PvSI-Rz6hodUfvG-u49qYlgyFHxoCnGwQAvD_BwE#/bill-debt-v1
```
| Verbo | API |
| --- | --- |
| GET | /bills |
| GET | /bills/{billId} |
| GET | /bills/by-change-date |
```


Processo de Lançamento de Notas Fiscais

Nota Fiscal de Compra: https://api.sienge.com.br/docs/?utm_source=cpc_google-pmax-ads&utm_medium=cpc&utm_content=plataforma&utm_campaign=f2-p1p2p3p4-performance-max&gad_source=1&gclid=CjwKCAjw-qi_BhBxEiwAkxvbkFxSbFO_3ZPyWh8BheBH7R2gi44PvSI-Rz6hodUfvG-u49qYlgyFHxoCnGwQAvD_BwE#/purchase-invoices-v1
```
| Verbo | API |
| --- | --- |
| GET | /purchase-invoices/{sequentialNumber} |
| GET | /purchase-invoices/{sequentialNumber}/items |
| POST | /purchase-invoices |
| POST | /purchase-invoices/{sequentialNumber}/items/purchase-orders/delivery-schedules |
| GET | /purchase-invoices/deliveries-attended |
```

/purchase-invoices/{sequentialNumber}
  GET
/purchase-invoices/{sequentialNumber}/items
  GET
/purchase-invoices
  POST
/purchase-invoices/{sequentialNumber}/items/purchase-orders/delivery-schedules
  POST
/purchase-invoices/deliveries-attended
  GET

/nfes
  GET
/nfes/{nfeKey}
  GET
/nfes/{nfeKey}/issuers-recipients
  GET
/nfes/{nfeKey}/payments
  GET
/nfes/{nfeKey}/deliveries
  GET
/nfes/{nfeKey}/linked-nfes
  GET
/nfes/{nfeKey}/icms
  GET
/nfes/{nfeKey}/carriers
  GET
/nfes/{nfeKey}/issqn
  GET
/nfes/{nfeKey}/itens
  GET
/nfes/{nfeKey}/itens/{itemId}/ipi
  GET
/nfes/{nfeKey}/itens/{itemId}/pis-cofins
  GET
/nfes/{nfeKey}/itens/{itemId}/simplified-icms
  GET
/nfes/{nfeKey}/itens/{itemId}/issqn
  GET
/nfes/{nfeKey}/itens/{itemId}/icms
  GET

Processo de Saneamento da Base de Insumos

/building-cost-estimations/{buildingId}/resources
  GET
/building-cost-estimations/{buildingId}/resources
  POST
/building-cost-estimations/{buildingId}/resources/{id}
  GET
/building-cost-estimations/{buildingId}/resources/{id}
  PATCH
/building-cost-estimations/{buildingId}/cost-estimate-resources
  GET
/building-cost-estimation-items
  GET
/building/resources
  GET

Processo de Integração com Mercado Eletrônico (Requisição de Compras)

/purchase-requests
  GET & POST
/purchase-requests/{purchaseRequestId}
  GET
/purchase-requests/all/items
  GET
/purchase-requests/{purchaseRequestId}/items/{purchaseRequestItemNumber}/buildings-appropriations
  GET
/purchase-requests/{purchaseRequestId}/items/{purchaseRequestItemNumber}/delivery-requirements
  GET
/purchase-requests/{purchaseRequestId}/items
  POST

Processo de Integração com Mercado Eletrônico (Cotação)

/purchase-quotations
  GET
/purchase-quotations
  POST
/purchase-quotations/{purchaseQuotationId}/items
  POST
/purchase-quotations/{purchaseQuotationId}/items/from-purchase-request
  POST
/purchase-quotations/{purchaseQuotationId}/items/{purchaseQuotationItemNumber}/suppliers
  POST
/purchase-quotations/{purchaseQuotationId}/suppliers/{supplierId}/negotiations
  POST
/purchase-quotations/{purchaseQuotationId}/suppliers/{supplierId}/negotiations/{negotiationNumber}
  PUT
/purchase-quotations/{purchaseQuotationId}/suppliers/{supplierId}/negotiations/{negotiationNumber}/items/{quotationItemNumber}
  PUT

Processo de Integração com Mercado Eletrônico (Pedido de Compras)

/purchase-orders
  GET
/purchase-orders/{purchaseOrderId}
  GET
/purchase-orders/{purchaseOrderId}/items
  GET
/purchase-orders/{purchaseOrderId}/items/{itemNumber}
  GET
/purchase-orders/{purchaseOrderId}/items/{itemNumber}/delivery-schedules
  GET
/purchase-orders/{purchaseOrderId}/items/{itemNumber}/buildings-appropriations
  GET
/purchase-orders/{purchaseOrderId}/totalization
  GET
/purchase-orders/{purchaseOrderId}/supplier-evaluation-criteria
  GET
/purchase-orders/{purchaseOrderId}/evaluation
  POST
/purchase-orders/{purchaseOrderId}/evaluation
  PUT

Processo de Integração com Mercado Eletrônico (Contratos)

/supply-contracts
  GET
/supply-contracts/all
  GET
/supply-contracts/buildings
  GET
/supply-contracts/items
  GET

Processo de Recepção de Eventos do Sienge via Webhooks para Integração com Mercado Eletrônico (Requisições, Pedidos e Contratos)

WebHooks

/hooks
  GET
/hooks
  POST
/hooks/{hookId}
  GET
/hooks/{hookId}
  DELETE
```
## Liberação de acessos de Ações do usuário no Sienge
## ACESSO CAD APOIO (Suporte Backoffice ONSAC)

| ID | AÇAO |
| --- | --- |
| 4588 | CAD - Apoio - Setores/Obras - Consultar |

## ACESSO CAD  Empresas (Suporte Backoffice ONSAC)

| ID | AÇAO |
| --- | --- |
| 898	| CAD - Empresas - Cadastros - Consultar |
| 883	| CAD - Empresas - Grupos de Empresas - Consultar |
| 861	| CAD - Empresas - Holdings - Consultar |
| 860	| CAD - Empresas - Subsidiárias - Consultar |

## ACESSO CAD Obras/Centros de Custo (Suporte Backoffice ONSAC)

| ID | AÇAO |
| --- | --- |
| 1101 |	CAD - Obras/Centros de Custo - Cadastros - Consultar |
| 1085 |	CAD - Obras/Centros de Custo - Projetos - Consultar |
| 1076 |	CAD - Obras/Centros de Custo - Responsáveis Técnicos - Consultar |
| 1072 |	CAD - Obras/Centros de Custo - Tipos de Obra - Consultar |
| 1156 | 	CAD - Obras/Centros de Custo - Unidades Construtivas por Obra - Consultar |
| 1081 |	CAD - Obras/Centros de Custo - Áreas de Negócio - Consultar |

## ACESSO CAD  Pessoas - Credores (Suporte Backoffice ONSAC) 

| ID | AÇAO |
| --- | --- |
| 974 |	CAD - Pessoas - Credores - Consultar |
| 7729 |	CAD - Pessoas - Credores - Informações Bancárias - Visualizar |
| 5051 |	CAD - Pessoas - Credores - Qualidade - Visualizar qualificação |
| 1003 |	CAD - Pessoas - Credores - Representantes - Consultar |
| 1004 |	CAD - Pessoas - Credores - Representantes - Salvar |

## ACESSO CAD  Pessoas - Credores (Automação BOT ONSAC) 

| ID | AÇAO |
| --- | --- |
| 974 |	CAD - Pessoas - Credores - Consultar |
| 1003 |	CAD - Pessoas - Credores - Representantes - Consultar |
| 1004 |	CAD - Pessoas - Credores - Representantes - Salvar |

## ACESSO FIN-CPG  Consultas (Suporte Backoffice ONSAC)

| ID | AÇAO |
| --- | --- |
|104 |	FIN-CPG - Consultas - Títulos - Consultar |

## ACESSO FIN-CPG  Relatórios (Suporte Backoffice ONSAC)

| ID | AÇAO |
| --- | --- |
| 4916 |	FIN-CPG - Relatórios - Impostos - Títulos por Guia de Imposto |
| 5574 |	FIN-CPG - Relatórios - Inconsistências de Títulos |
| 373 |	FIN-CPG - Relatórios - Títulos por data |

## ACESSO FIN-CPG  Títulos (Suporte Backoffice e Automação BOT ONSAC)

Ajuste em Vencimentos e Parcelas de acordo como especificado na Nota Fiscal,
Geralmente é diferente do que está previsto no Pedido de Comprtas

| ID | AÇAO |
| --- | --- |
| 83 |	FIN-CPG - Títulos - Anexos - Consultar |
| 84 |	FIN-CPG - Títulos - Anexos - Salvar |
| 1608 |	FIN-CPG - Títulos - Cadastrar |
| 1745 |	FIN-CPG - Títulos - Cadastro de Parcelas |
| 1604 |	FIN-CPG - Títulos - Consultar |
| 1607 |	FIN-CPG - Títulos - Editar |
| 1606 |	FIN-CPG - Títulos - Excluir |
| 7029 |	FIN-CPG - Títulos - Informações Fiscais - Totalizações - Editar |
| 7030 |	FIN-CPG - Títulos - Informações Fiscais - Totalizações - Salvar |
| 1605 |	FIN-CPG - Títulos - Salvar |

## ACESSO FIN-CPG Alteração de Títulos/Parcelas (Suporte Backoffice e Automação BOT ONSAC)

| ID | AÇAO |
| --- | --- |
| 8994 |	FIN-CPG -Alteração de Títulos/Parcelas - Consultar |

## ACESSO SUP-ADC  Cotações de Preços (Suporte Backoffice e Automação BOT ONSAC)

| ID | AÇAO |
| --- | --- |
| 1232 |	SUP-ADC - Cotações de Preços - Cadastros - Consultar |
| 1237 |	SUP-ADC - Cotações de Preços - Cadastros - Insumos - Consultar | 
| 3195 |	SUP-ADC - Cotações de Preços - Cancelamentos de Saldos - Consultar |
| 1335 |	SUP-ADC - Cotações de Preços - Fornecedores por Insumo - Consultar |
| 1302 |	SUP-ADC - Cotações de Preços - Históricos - Consultar |
| 1418 |	SUP-ADC - Cotações de Preços - Negociações - Condições de Pagamento - Consultar |
| 1351 |	SUP-ADC - Cotações de Preços - Negociações - Consultar |
| 1362 |	SUP-ADC - Cotações de Preços - Negociações - Consultar insumos |
| 1363 |	SUP-ADC - Cotações de Preços - Negociações - Promoções - Consultar |
| 1453 |	SUP-ADC - Cotações de Preços - Negociações - Resumo - Consultar |
| 1292 |	SUP-ADC - Cotações de Preços - Promoções - Consultar |

## ACESSO SUP-ADC  Notas Fiscais de Compra (Suporte Backoffice e Automação BOT ONSAC)

| ID | AÇAO |
| --- | --- |
| 1871 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Anexos - Baixar |
| 1869 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Anexos - Consultar |
| 1870 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Anexos - Salvar |
| 1549 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Cadastrar |
| 1548 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Consultar |
| 1551 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Editar |
| 1550 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Excluir |
| 1555 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Insumos - Cadastrar |
| 1554 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Insumos - Consultar |
| 1557 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Insumos - Editar |
| 1556 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Insumos - Excluir |
| 1558 |  SUP-ADC - Notas Fiscais de Compra - Cadastros - Insumos - Salvar |
| 1552 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Salvar |
| 1891 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Totalização - Editar |
| 1892 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Totalização - Salvar |
| 1923 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Título - Editar |
| 1924 |	SUP-ADC - Notas Fiscais de Compra - Cadastros - Título - Salvar |
| 1710 |	SUP-ADC - Notas Fiscais de Compra - Insumos - Avaliação - Cadastrar |
| 1711 |	SUP-ADC - Notas Fiscais de Compra - Insumos - Avaliação - Salvar |
| 1723 |	SUP-ADC - Notas Fiscais de Compra - Pedido - Consultar |
| 1724 |	SUP-ADC - Notas Fiscais de Compra - Pedido -Associar |

## ACESSO SUP-ADC  Pedidos de Compra (Suporte Backoffice e Automação BOT ONSAC)

| ID | AÇAO |
| --- | --- |
| 1506 |	SUP-ADC - Pedidos de Compra - Autorizações - Consultar |
| 161 |	SUP-ADC - Pedidos de Compra - Cadastros - Anexos - Baixar |
| 163 |	SUP-ADC - Pedidos de Compra - Cadastros - Anexos - Consultar |
| 1441 |	SUP-ADC - Pedidos de Compra - Cadastros - Consultar |
| 1444 |	SUP-ADC - Pedidos de Compra - Cadastros - Editar |
| 4173 |	SUP-ADC - Pedidos de Compra - Cadastros - Insumos - Avaliação - Consultar |
| 1529 |	SUP-ADC - Pedidos de Compra - Cadastros - Insumos - Consultar |
| 1531 |	SUP-ADC - Pedidos de Compra - Cadastros - Insumos - Editar |
| 4171 |	SUP-ADC - Pedidos de Compra - Cadastros - Insumos - Programação - Consultar |
| 1502 |	SUP-ADC - Pedidos de Compra - Cadastros - Observação - Editar |
| 1833 |	SUP-ADC - Pedidos de Compra - Cadastros - Previsão financeira - Cadastrar |
| 1813 |	SUP-ADC - Pedidos de Compra - Cadastros - Totalização - Cadastrar |
| 1997 |	SUP-ADC - Pedidos de Compra - Cancelamentos de Saldos - Consultar |
| 1720 |	SUP-ADC - Pedidos de Compra - Consultar |
| 1742 |	SUP-ADC - Pedidos de Compra - Históricos - Consultar |
| 314 |	SUP-ADC - Pedidos de Compra - Insumos - Cotação - Consultar |
| 1693 |	SUP-ADC - Pedidos de Compra - Insumos - Solicitação - Consultar |
| 2028 |	SUP-ADC - Pedidos de Compra - Pedidos Atendidos - Consultar |
| 2049 |	SUP-ADC - Pedidos de Compra - Pedidos Atendidos - Insumos - Consultar |
| 1996 |	SUP-ADC - Pedidos de Compra - Reprogramações - Consultar |
| 1655 |	SUP-ADC - Pedidos de Compra - Reprogramações de Entrega - Consultar |

## ACESSO SUP-ADC  Relatórios (Suporte Backoffice e Automação BOT ONSAC)

| ID | AÇAO |
| --- | --- |
| 2009 |	SUP-ADC - Relatórios - Notas Fiscais Devolvidas |
| 1998 |	SUP-ADC - Relatórios - Notas Fiscais por Datas de Emissões |
| 1986 |	SUP-ADC - Relatórios - Relação de Notas Fiscais |

## ACESSO SUP-ADC  Solicitações de Compra (Suporte Backoffice e Automação BOT ONSAC)

| ID | AÇAO |
| --- | --- |
|892 |	SUP-ADC - Solicitações de Compra - Autorização - Consultar |
|736 |	SUP-ADC - Solicitações de Compra - Cadastros - Consultar |
|3285 |	SUP-ADC - Solicitações de Compra - Cadastros - Insumos - Consultar |
|840 |	SUP-ADC - Solicitações de Compra - Cadastros - Insumos - Cópia - Consultar |
|2140 |	SUP-ADC - Solicitações de Compra - Cadastros - Insumos - Estoque - Cadastrar / Consultar / Excluir |
|1123 |	SUP-ADC - Solicitações de Compra - Cadastros - Insumos - Estoque - Consultar - Salvar |
|1097 |	SUP-ADC - Solicitações de Compra - Cancelamento de Saldo - Consultar |
|1135 |	SUP-ADC - Solicitações de Compra - Distribuição - Consultar |
|4218 |	SUP-ADC - Solicitações de Compra - Necessidades de Compra - Consultar |
|1064 |	SUP-ADC - Solicitações de Compra - Reprogramação - Consultar |
|2066 |	SUP-ADC - Solicitações de Compra - Solicitações Atendidas - Consultar |
|4233 |	SUP-ADC - Solicitações de Compras - Cadastros - Insumos - Detalhar - Consultar |

## ACESSO SUP-MED  Medições (Suporte Backoffice e Automação BOT ONSAC)

| ID | AÇAO |
| --- | --- |
| 510 |	SUP-MED - Medições - Liberações - Abatimento - Excluir |
| 509 |	SUP-MED - Medições - Liberações - Abatimento - Visualizar |
| 2250 |	SUP-MED - Medições - Liberações - Título - Excluir |

## ACESSO SUP-MED  Medições (Suporte Backoffice e Automação BOT ONSAC)

| ID | AÇAO |
| --- | --- |
| 1647 |	SUP-MED - Contratos - Aprovação Jurídica - Consultar |
| 2378 |	SUP-MED - Contratos - Autorizações - Consultar |
| 2397 |	SUP-MED - Contratos - Autorizações - Itens - Apropriação - Consultar |
| 2386 |	SUP-MED - Contratos - Autorizações - Itens - Consultar |
| 2398 |	SUP-MED - Contratos - Autorizações - Itens - Cotações - Consultar |
| 2390 |	SUP-MED - Contratos - Autorizações - Itens - Histórico - Consultar |
| 3076 |	SUP-MED - Contratos - Autorizações - Itens - Preços - Consultar |
| 2387 |	SUP-MED - Contratos - Autorizações - Itens - Totalização - Consultar |
| 2317 |	SUP-MED - Contratos - Cadastros - Aditivos - Consultar |
| 49 |	SUP-MED - Contratos - Cadastros - Complementos - Padrão - Consultar |
| 1295 |	SUP-MED - Contratos - Cadastros - Consultar |
| 1508 |	SUP-MED - Contratos - Cadastros - Impostos - Consultar |
| 2281 |	SUP-MED - Contratos - Cadastros - Itens - Itens do Contrato - Cotação - Consultar |
| 2305 |	SUP-MED - Contratos - Cadastros - Itens - Itens do Contrato - Orçamento - Consultar (Insumos) |
| 2314 |	SUP-MED - Contratos - Cadastros - Itens - Itens do Contrato - Outras planilhas de contratos - Consultar |
| 1757 |	SUP-MED - Contratos - Cadastros - Itens - Itens do Contrato - Solicitação - Consultar |
| 233 |	SUP-MED - Contratos - Cadastros - Itens - Itens do Contrato - Solicitação Serviço - Consultar |
| 3157 |	SUP-MED - Contratos - Cadastros - Títulos Vinculados - Obras - Títulos - Consultar |
| 1260 |	SUP-MED - Contratos - Tipos de Complementos - Consultar |
| 1276 |	SUP-MED - Contratos - Tipos de Contratos - Consultar |

## ACESSO SUP-MED  Contratos e Medições (Suporte Backoffice e Automação BOT ONSAC)

| ID | AÇAO |
| --- | --- |
| 4223 |	SUP-MED - Contratos e Medições - Cadastros - Caução - Salvar |
| 4228 |	SUP-MED - Contratos e Medições - Cadastros - Descontos - Salvar |
| 4226 |	SUP-MED - Contratos e Medições - Cadastros - Impostos - Salvar |
| 4213 |	SUP-MED - Contratos e Medições - Cadastros - Itens - Consultar totalização |
| 4211 |	SUP-MED - Contratos e Medições - Cadastros - Itens - Salvar |
| 4216 |	SUP-MED - Contratos e Medições - Cadastros - Itens - Salvar Avaliação |
| 9002 |	SUP-MED - Contratos e Medições - Cadastros - Sinal - Salvar |
| 4221 |	SUP-MED - Contratos e Medições - Cadastros - Índices - Salvar |
| 4235 |	SUP-MED - Contratos e Medições - Contratos - Situações de Contratos - Consultar |


## ACESSO SUP-MED  Medições (Suporte Backoffice e Automação BOT ONSAC)

| ID | AÇAO |
| --- | --- |
| 4208 |	SUP-MED - Medições - Autorizações - Consultar |
| 3893 |	SUP-MED - Medições - Cadastros - Anexos - Abrir |
| 3894 |	SUP-MED - Medições - Cadastros - Anexos - Salvar |
| 1836 |	SUP-MED - Medições - Cadastros - Cadastrar |
| 1835 |	SUP-MED - Medições - Cadastros - Consultar |
| 4230 |	SUP-MED - Medições - Cadastros - Descontos - Excluir |
| 1837 |	SUP-MED - Medições - Cadastros - Editar |
| 1858 |	SUP-MED - Medições - Cadastros - Excluir |
| 1852 |	SUP-MED - Medições - Cadastros - Salvar |
| 2263 |	SUP-MED - Medições - Liberações - Anexos - Editar |
| 2264 |	SUP-MED - Medições - Liberações - Anexos - Salvar |
| 32 |	SUP-MED - Medições - Liberações - Avaliação - Cadastrar |
| 33 |	SUP-MED - Medições - Liberações - Avaliação - Salvar |
| 1961 |	SUP-MED - Medições - Liberações - Consultar |
| 2366 |	SUP-MED - Medições - Liberações - Excluir |
| 2365 |	SUP-MED - Medições - Liberações - Finalizar |
| 2253 |	SUP-MED - Medições - Liberações - Seleção de Títulos - Consultar |
| 2254 |	SUP-MED - Medições - Liberações - Seleção de Títulos - Salvar |
| 3082 |	SUP-MED - Medições - Liberações - Seleção de Títulos Vinculados - Consultar |
| 3083 |	SUP-MED - Medições - Liberações - Seleção de Títulos Vinculados - Salvar |
| 2247 |	SUP-MED - Medições - Liberações - Título - Cadastrar |
| 3300 |	SUP-MED - Medições - Liberações - Título - Cadastro do Título - Apropriação de Obra - Consultar |
| 3301 |	SUP-MED - Medições - Liberações - Título - Cadastro do Título - Apropriação de Obra - Salvar |
| 3298 |	SUP-MED - Medições - Liberações - Título - Cadastro do Título - Apropriação por Depto - Consultar |
| 3299 |	SUP-MED - Medições - Liberações - Título - Cadastro do Título - Apropriação por Depto - Salvar |
| 3294 |	SUP-MED - Medições - Liberações - Título - Cadastro do Título - Consulta de Parcelas - Consultar |
| 3293 |	SUP-MED - Medições - Liberações - Título - Cadastro do Título - Excluir |
| 3292 |	SUP-MED - Medições - Liberações - Título - Cadastro do Título - Salvar |
| 3290 |	SUP-MED - Medições - Liberações - Título - Cadastro do título - Editar |
| 2251 |	SUP-MED - Medições - Liberações - Título - Impostos - Alterar |
| 2252 |	SUP-MED - Medições - Liberações - Título - Impostos - Salvar |
| 2246 |	SUP-MED - Medições - Liberações - Título - Salvar |
| 3910 |	SUP-MED - Medições - Liberações de Múltiplas Medições - Consultar |
| 3911 |	SUP-MED - Medições - Liberações de Múltiplas Medições - Liberação - Cadastrar |
| 3912 |	SUP-MED - Medições - Liberações de Múltiplas Medições - Liberação - Salvar   |

## ACESSO SUP-MED  Solicitações de Serviços (Suporte Backoffice e Automação BOT ONSAC)

| ID | AÇAO |
| --- | --- |
| 323 |	SUP-MED - Solicitações de Serviços - Alocações de Planilhas - Consultar |
| 299 |	SUP-MED - Solicitações de Serviços - Autorizações - Consultar |
| 269 |	SUP-MED - Solicitações de Serviços - Cadastros - Consultar |
| 292 |	SUP-MED - Solicitações de Serviços - Cadastros - Obras e Unid. Construtivas - Orçamento - Consultar |
| 295 |	SUP-MED - Solicitações de Serviços - Cancelamentos de Saldos - Consultar |

