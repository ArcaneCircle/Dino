# Dino

[Chrome's Dinosaur](https://source.chromium.org/chromium/chromium/src/+/main:components/neterror/resources/offline.js) game ported to WebXDC.

## Developing

### Installing Dependencies

After cloning this repo, install dependecies:

```
pnpm i
```

### Testing the app in the browser

To test your work in your browser (with hot reloading!) while developing:

```
pnpm dev-mini
# Alternatively to test in a more advanced WebXDC emulator:
pnpm dev
```

### Building

To package the WebXDC file:

```
pnpm build
```

The resulting optimized `.xdc` file is saved in `dist-xdc/` folder.

### Releasing

To automatically build and create a new GitHub release with the `.xdc` file:

```
git tag -a v1.0.1
git push origin v1.0.1
```
