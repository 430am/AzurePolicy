# AzurePolicy

to add policies via Azure CLI use the following format:

`az policy definition create --name 'Audit Storage Soft Delete' --rules ./AuditSoftDelete/azurepolicy.rules.json --params ./AuditSoftDelete/azurepolicy.paramaters.json --subscription <id or name>`
