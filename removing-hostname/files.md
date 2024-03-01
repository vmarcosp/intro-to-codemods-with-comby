```typescript
// Hostname no meio
this.identityClient.login({ accountName, hostname, data })
// Hostname at the end
this.checkoutClient.addItem({ accountName, anotherOne, hostname })
// Hostname no inicio
this.catalogClient.findById({ hostname, accountName id })
// Hostname apenas
this.catalogClient.findById({ hostname })
// Atribuindo um valor ao hostname
this.catalogClient.findById({ data, hostname: ctx.req.value, accountName })
```
