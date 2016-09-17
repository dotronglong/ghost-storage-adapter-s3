# Ghost storage adapter S3

An AWS S3 storage adapter for Ghost 0.10+

## Installation

```
npm install ghost-storage-adapter-s3
mkdir -p ./content/storage
cp -r ./node_modules/ghost-storage-adapter-s3 ./content/storage/s3
```

## Configuration

```
storage: {
  active: 's3',
  s3: {
    accessKeyId: 'YOUR_ACCESS_KEY_ID',
    bucket: 'YOUR_BUCKET_NAME',
    region: 'YOUR_REGION_SLUG',
    secretAccessKey: 'YOUR_SECRET_ACCESS_KEY',
    assetHost: 'OPTIONAL_CDN_URL'
  },
},
```

## Support

This library has been tested with Ghost 0.10 and 0.11.

## License

[ISC](./LICENSE.md).
