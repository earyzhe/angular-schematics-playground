# Getting Started With Schematics


We use the command for convenience to build and execute a Schematic "    "execute": "npm run build && schematics .:page --dry-run=false"


This repository is a basic Schematic implementation that serves as a starting point to create and publish Schematics to NPM.


To see some examples of Angular schematics install @schematics/angular and check in node_modules
npm i @schematics/angular


For a great example on how to use Schematics see this page: https://github.com/BottleRocketStudios/ng-momentum/blob/master/src/scaffold/index.ts#L217-L219 

## Create
To create a new Schematic collection run outside a schematic folder
```bash
schematics blank --name=hello-world
```

To add a new Schematic to an existing collection run inside a schematic folder the same command
```bash
schematics blank --name=hello-world
```


### Testing

To test locally, install `@angular-devkit/schematics-cli` globally and use the `schematics` command line tool. That tool acts the same as the `generate` command of the Angular CLI, but also has a debug mode.

Check the documentation with
```bash
schematics --help
```

### Unit Testing

`npm run test` will run the unit tests, using Jasmine as a runner and test framework.

### Publishing

To publish, simply do:

```bash
npm run build
npm publish
```

That's it!
 