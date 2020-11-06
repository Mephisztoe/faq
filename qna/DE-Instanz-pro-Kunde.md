## Question
Muss ich die fiskaltrust.Middleware für jeden Standort (Outlet) in einer eigenen CashBox im Portal anlegen?

## Metadata tags
lang-de, market-de, middleware, PosCreator, PosDealer

## Answer
Ja unbedingt. Für die rechtskonforme Verwendung ist es notwendig, dass **jeder Standort** (Outlet) von **jeder rechtlichen Einheit** (Unternehmen des PosOperators) zumindest eine eigene CashBox der fiskaltrust.Middleware verwendet. **Jede für einen Standort konfigurierte Instanz darf daher beim richtigen KassenBetreiber (PosOperator) nur einmal** eingesetzt werden. Es können jedoch mehrere Kassen-Terminals an diesem Standort diese Instanz verwenden. Info zu den möglichen [Rollout-Szenarien sind hier zu finden](https://docs.fiskaltrust.cloud/doc/productdescription-de-doc/for-posdealers/02-pre-sales/rollout-scenarios.html). 
Um den Rollout für viele Kunden mit grundsätzlich gleicher Konfiguration zu vereinfachen, können Vorlagen (Templates) im fiskaltrust.Portal angelegt werden, die als Basis dienen.
https://docs.fiskaltrust.cloud/doc/productdescription-de-doc/for-posdealers/02-pre-sales/automatisierter-rollout.html 
