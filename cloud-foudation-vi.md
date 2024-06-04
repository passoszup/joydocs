=# Admin guide - Cloud Foudation v1

# Status

inprogress

# Changelog

| Version | Date       | Changes |
|---------|------------|----------|
| v1.0    | 04/06/2024 | Initial creation of the Cloud Resource Explorer admin guide |

# Getting Started

API foundation is a set of services that allow you to manage organizations and govern groups of AWS user accounts.
Enable accounts to centrally provision services and policies using native management and governance services like AWS Organization and AWS Control Tower. And for automation services, Lambda and API gateway services. 

For the source code and more detailed documentation, visit the [cloud-services-foudation infra-controlplane](https://github.com/stack-spot/cloud-services-foundation-infra-controlplane).

# Administrative tasks

Para executar esta api é nescessário acesso a console com privilegios ao organization e control tower aws. 

## Listing Available Services

To list the managed services supported by CRE, use the following endpoint:
```

```
This endpoint returns a list of services that can be managed by CRE.

## Linking a Managed Service to a Stackspot Account

# FAQ

## Como posso solicitar a criação de uma conta?
You can 

## Como posso saber se minha conta esta criada?

# Troubleshooting

## Error Codes

|              Error Code             |              Description            |            Possible Cause           |            Solution                 |
|-------------------------------------|-------------------------------------|-------------------------------------|-------------------------------------|
| CLOUD_FOUDATION_NOT_FOUND_ERROR | Don't possibile deploy account, becouse accout resource invalid | The Stackspot account is not linked to the resource |
| CLOUD_FOUDATION_NOT_FOUND_ERROR | The application could not access the AWS account |
