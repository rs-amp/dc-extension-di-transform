# DI Image Transformation UI Extension

This UI extension lets you create an image transformation to attach to an image in DI, including crops, rotation and image effects.
Check out `schema.json` for the content schema to use with this extension. Note that it is very likely to change at this point.

You're probably better off looking at a feature branch, check those out in the branches list.

## TODO
- POI summary, more than just one hotspot.
- Work out what to do about cropping rotated images. (may need DI change to support this (pprotate?? make protate apply before pcrop?), if not we can just disable POI for rotated crops, or disable crop. up to the user)
- Preset crops with fixed aspect. Pixel level crop size control.
- More transformations (blur, unsharp), discussion about "scale" now that we have full crop control.
- "Metadata" tab that lets you see printouts of all the transformations.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests (wip)

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests (wip)

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).