# Hashicorp Vault

## Add configurations in vault

### UP server
```$bash
vault server --dev --dev-root-token-id="00000000-0000-0000-0000-000000000000"
```
### Add secret in vault
```$bash
vault kv put secret/booking-microservice @booking-microservice.json
vault kv put secret/product-microservice @product-microservice.json
vault kv put secret/stock-microservice @stock-microservice.json
``` 
