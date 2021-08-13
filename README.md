# NgxImageengine Workspace

If you're looking for the `@imageengine/angular` package readme, you can find it on the [projects folder](projects/ngx-imageengine/README.md).

## Contents / Projects
This workspace only contains, as of now, the ngx-imageengine component.
To publish that project it needs to be built first.
You can run `npm run publish` that does it in a single command, or manually with the following steps.

## Build

Run `ng build` from the workspace root directory to build the projects. The build artifacts will be stored in the `dist/` directory.
(remember to bump the version of the desired project on the project's `package.json` before building a new version)

## Publish
After building the project(s) the builds will be stored in `dist/`. To publish to NPM navigate to the project folder (e.g: `cd dist/ngx-imageengine`) and from there do `npm publish --access public`.

## Running unit tests

The test should be run from the project(s) folder themselves and not from the root workspace (e.g: `cd dist/ngx-imageengine` followed by `npm run test`)
