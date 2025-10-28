# Configuração de DNS no Cloudflare

No site do Cloudflare:

1. Selecione o seu domínio
2. Navegue até **DNS** > **Records** > **DNS management for domain**
3. Clique em **Add records**
4. Preencha os campos:
   - **Tipo**: CNAME
   - **Name**: subdomain.
   - **Target**: ex: www.example.com
   - **Proxy**: Disabled

> **OBS**: Não esqueça do ponto no campo nome, so escolher o nome do subdomain e correr para o abraço 
