# Admin Guide - Cloud Foundation API

# Changelog

| Version | Date       | Changes                                      |
|---------|------------|----------------------------------------------|
| v1.1    | 20/06/2024 | Initial creation of the admin guide document |

# Getting Started

The Cloud Foundation API provides a robust interface for managing and orchestrating cloud infrastructure resources. This administration guide will help you understand how to configure, manage, and troubleshoot the API.

## Prerequisites

- StackSpot account with administrator permissions.
- Access to the API repository: [stackspot-cs-controlplane-docs](https://github.com/stack-spot/stackspot-cs-controlplane-docs) e [stackspot-cs-infra-controlplanenewrepo](https://github.com/stack-spot/stackspot-cs-infra-controlplanenewrepo).

# Getting Help

If you encounter problems or have questions, follow these steps for help:

1. Consult the official StackSpot documentation.
2. Check the frequently asked questions (FAQ) below.
3. Contact StackSpot technical support via the support portal or email.

# Process Group

To keep related processes together, use a routine group. This helps organize and manage processes efficiently.

## Process Section

### Processo de Criação de Recurso

1. **Authentication**: Ensure you are authenticated to the API.
2. **Request Submission**: Send a POST request to the `/create-resource` endpoint with the required parameters.
3. **Status Check**: Check the request status using the `/status` endpoint.

```markdown
POST /create-resource
{
  "resourceType": "VM",
  "configuration": {
    "cpu": 4,
    "memory": "16GB"
  }
}
```

## FAQ

1. How can I create a new resource?
* Use the `/create-resource` endpoint with the necessary parameters.
2. How can I check the status of a resource?
* Use the `/status` endpoint with the resource ID.

## Troubleshooting

# Known Issues

Erro 1001: Invalid input
Descrição: Entrada inválida fornecida.
Causa Possível: Dados incorretos no formato de entrada.
Solução: Verifique o formato de entrada e tente novamente.

# APIs

Full API documentation, including administration endpoints, can be found [here](https://github.com/stack-spot/stackspot-cs-controlplane-docs).

# Error Codes

Error Code	Description	Possible Cause	Solution

| Error Code | Description |   Possible Cause   |         Solution       |
|------------|-------------|--------------------|------------------------|
|   2002     | Auth failure| Invalid credentials| Verify your credentials|		

# Appendix

For more detailed and in-depth information, see the following resources:

* [Documentação Oficial da StackSpot](https://docs.stackspot.com/) 
* [Repositório de Exemplos](https://github.com/stack-spot/stackspot-cs-controlplane-docs)
* [Repositório de Infraestrutura](https://github.com/stack-spot/stackspot-cs-infra-controlplanenewrepo)
