## Kinsta CloudFlare CDN Tester
#### This tool scrapes a URL to gather the local static assets files such as images, CSS and JS. And returns the relevant headers and the status code

### Usage
```
Usage of ./kcfcache_linux.bin:
  -asset string
        The type of the assets (default "all")
        Choices: ['css', 'js', 'images', 'all']
  -url string
        The site URL
```

### Examples
```
./kcfcache_linux.bin --url=https://site.tld
./kcfcache_linux.bin --url=https://site.tld --asset=css
./kcfcache_linux.bin --url=https://site.tld --asset=js
./kcfcache_linux.bin --url=https://site.tld --asset=images
```
