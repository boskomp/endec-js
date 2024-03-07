## Installation

You can install this package via npm:

```
npm install endec-js
```

## Usage

```
const { encryptData, decryptData } = require('endec-js');

const plainText = 'Hello, world!';
const key = 'yoursecretkey';

// Encrypt message
const encrypted = encryptData(plainText, key);
console.log('Encrypted:', encrypted);

// Decrypt message
const decrypted = decryptData(encrypted, key);
console.log('Decrypted:', decrypted);
```
