# Note Taking App

This app is a simple note taking app. This is the MongoDB API version

## Development

To run locally, run a local MongoDB db instance or provide a `MONGODB_CONNECTION_STRING` in the environment. `dotenv` is also instrumented in the Node.js app if you prefer that.

Then run these two commands in separate terminals

```bash
npm run start
npm run start:client
```

## Production

Make sure the `MONGODB_CONNECTION_STRING` is present in the environment. Then run these commands:

```bash
npm run build
npm run start
```

The Node.js app will serve the built files itself if you build them.
