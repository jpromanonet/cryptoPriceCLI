# Coindex CLI

CLI escrito en Node JS para revisar precios de criptomonedas

Registra tu API key at https://nomics.com

## Uso

```
npm install

npm link
```

## Comandos

```
# Ayuda & Comandos
coindex -h

# Version
coindex -V

# Comandos para la API Key
coindex key set
coindex key show
coindex key remove

# Comandos para revisar los precios.
coindex check price

# Revisar monedas especificas (Por defecto: BTN,ETH,XRP)
coindex check --coin=BTC,ETH

# Elegir la moneda (Por defecto: USD)
coindex check --cur=EUR
```

### Version

0.0.1

### Licencia

MIT