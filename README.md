# Tron Address Utilities

It is responsible for encoding, verifying and computing checksums for
Tron addresses and computing special addresses, such as those
enerated by and for contracts under various situations.

For more information, see the [documentation](https://docs.ethers.io/v5/api/utils/address/).

## Importing

Most users will prefer to use the [umbrella package](https://www.npmjs.com/package/ethers),
but for those with more specific needs, individual components can be imported.

```javascript
const {
  getAddress,
  isAddress,

  getIcapAddress,

  getContractAddress,
  getCreate2Address
} = require('@tronproject/address');
```

## License

MIT License
