## primeiro passo: o dns tipo `A` para redirecionar para o netlify com ipv4:`75.2.60.5`
- campo Name `@` ou `@` mais o nome do subdomínio
- obs: selecione o tipo `A`
- campo IPv4 address `75.2.60.5`s
- no campo Proxy status `disable`
- restante deixa como esta
- click em save promto
## passo dois: configurar o `www.domain.com` para redirecionar para o dominio
- campo Name `www`
- obs: selecione o tipo `CNAME`
- campo Target `domain.netlify.app`
- no campo Proxy status `disable`
- restante deixa como esta
- click em save promto
