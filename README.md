# ipfs-uploader
This is a simple node helper script to upload files to [IPFS](https://ipfs.io) using the [Infura](https://infura.io) API.

## How to use

1. Install dependencies with ``npm install``
2. Update the ``config.js`` file with your [Infura](https://infura.io) project id and secret
3. Add your file(s) to the ``upload`` folder
4. Run ``node upload.js``

## Dependencies 
- [ipfs-http-client](https://github.com/ipfs/js-ipfs/tree/master/packages/ipfs-http-client)