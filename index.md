# SUMMARY

```mermaid
erDiagram
    COMPANY ||--|{ CATALOGUE : places
    COMPANY {
        string name
        string custNumber
        string sector
    }
    CATALOGUE ||--|{ PRODUCT : places
    CATALOGUE {
        string name
        string custNumber
        string sector
    }
    COMPANY ||--|{ PRODUCT : contains
    PRODUCT {
        int orderNumber
        string deliveryAddress
    
    }
```
