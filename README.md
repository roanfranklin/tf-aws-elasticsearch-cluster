# tf-aws-elasticsearch-cluster
AWS Cluster ElasticSearch - VPC

Execute os comando abaixo para provisionar:

```bash
terraform init
terraform plan
terraform apply
```

## Informações

### Region

Norte da Virginha ( us-east-1 )

### ElasticSearch

Versão: 7.7
Tipo de instância: r5.large.elasticsearch
Qtd. de instâncias: 3
Domínio: demo-elk-domain

### Ingress

Acesso somente por VPC.