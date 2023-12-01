# AWS command to remove Rout53 zone from CLI
```bash
aws route53 list-resource-record-sets --hosted-zone-id $(aws route53 list-hosted-zones
 --query "HostedZones[?Name=='${DOMAIN_NAME}.']|[0].Id" --output text) --output json > route53_backup.json
```
