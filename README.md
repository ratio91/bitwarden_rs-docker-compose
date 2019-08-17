# bitwarden_rs-docker-compose
a sample configuration of `bitwarden_rs` I use daily  

## prerequisites  

VM with `docker` and `docker-compose` installed  
a DNS entry for the domain you want to use (I use vault.`<domain>` hosted at Cloudflare)  
`traefik` up and running (a reverse-proxy)
instruction    

## configure   
fill in your details in the `sample.env` file   
rename `sample.env` to `.env`
(the SMTP and yubikey instructions are optional, you can remove them from the docker-compose file if you want)  

## run  
`docker-compose up -d`

## use

see https://github.com/dani-garcia/bitwarden_rs/wiki
