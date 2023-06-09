# teashirt
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://hongnonghao.github.io/teashirt/index.html$1 [R,L]
