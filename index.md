# SUMMARY

```mermaid
erDiagram
    CUSTOMER ||-- ORDER
    CUSTOMER {
        string name
        string custNumber
        string sector
    }
    ORDER ||-- LINE-ITEM
    ORDER {
        int orderNumber
        string deliveryAddress
    }
    LINE-ITEM {
        string productCode
        int quantity
        float pricePerUnit
    }
```
