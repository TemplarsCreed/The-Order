#配置文件，更好域名端口
echo -e "http://toyoo.ml {
 root /usr/local/caddy/www/aria2
 timeouts none
 gzip
 filemanager /Download /usr/local/caddy/www/aria2/Download {
  database /usr/local/caddy/filemanager.db
 }
}" > /usr/local/caddy/Caddyfile
