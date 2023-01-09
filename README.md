RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://joeyyang1226.github.io/tscoding/index.html$1 [R,L]
