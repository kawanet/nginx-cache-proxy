# nginx-cache-proxy

Nginx configuration as a HTTP proxy server with strong cache enabled

## Usage

```sh
./etc/init.d/nginx-cache-proxy start
curl -v -i --proxy http://127.0.0.1:3128/ http://www.google.com/  
```

## Installation

```sh
git clone https://github.com/kawanet/nginx-cache-proxy.git
sudo
ln -s /path/to/nginx-cache-proxy/etc/init.d/nginx-cache-proxy /etc/rc.d/init.d/
chkconfig --add nginx-cache-proxy
service nginx-cache-proxy start
```

## License

MIT

## Author

@kawanet

## Repository

https://github.com/kawanet/nginx-cache-proxy
