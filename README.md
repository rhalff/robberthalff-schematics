# RobbertHalff Schematics

### Testing

To test locally, install `@angular-devkit/schematics` globally and use the `schematics` command line tool. That tool acts the same as the `generate` command of the Angular CLI, but also has a debug mode.

Check the documentation with
```bash
schematics --help
```

### Unit Testing

`yarn test` will run the unit tests, using Jasmine as a runner and test framework.

### Publishing

To publish:

```bash
yarn build
yarn publish
```
