# Usage

```javascript
// import the ip-giz
const ipGiz = require('ip-giz)
```

## IP4 Validity

```javascript
ipGiz.isValid('192.168.1.1')
// result: true

ipGiz.isValid('192.169.1.256')
result: false
```

## Increment

```javascript
ipGiz.increment('192.168.1.1')
// result: 192.168.1.2
```

## Iterate

```javascript
ipGiz.iterate('192.168.1.1', '192.168.10.1', (ip) => {
  // do something with the ip here
  console.log(ip)
})
```
