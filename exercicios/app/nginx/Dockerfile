	# Setar a imagem do nginx
FROM nginx

	# Autor/Mantenedor
MAINTAINER Devops do Samba

	# Copiar configurações customizadas do diretório atual
COPY nginx.conf /etc/nginx/nginx.conf

COPY certificado/certificado.crt  /etc/ssl/certificado.crt
COPY certificado/certificado.key  /etc/ssl/certificado.key
