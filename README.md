Simple way to install standard web-app for reading of XHprof reports.

# Install

1. Download and unzip.
2. Run `composer install`.
3. Setup your web-server to response content of vendor/lox/xhprof/xhprof_html directory as root of a domain. You can put `nginx-server.example.conf` to `/etc/nginx/sites-enabled/01-xdebug-web.conf` if you use nginx (check comments in it), then restart it by `service nginx reload`.
