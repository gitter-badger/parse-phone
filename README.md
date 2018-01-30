# parse-phone
phone parser for country dialing code parsing from full string

## Get Started
```
const phoneStr = "+86188888888"
const phoneParser = require('parse-phone')
const recipient = phoneParser(phoneStr)

{ success: true,
  dialCode: '+86',
  full: '+86188888888',
  phone: '188888888' }

```
