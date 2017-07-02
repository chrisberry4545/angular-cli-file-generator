# Angular CLI file generator

Generates required files for a class for use in an angular app.

## Usage

To run the app

    - angular-gen {className} -t {angularType}

Replace {className} with the name of the file you want to create, using dashes between words e.g my-home-page.

Replace {angularType} with the angular type the class will be e.g:

    component
    service

## Output format

Outputs the required files for the relevent class type in a folder with the given className.

E.g
    - angular-gen my-home-page -t component

Will create a new folder my-home-page, which contains 5 files
    my-home-page.component.scss
    my-home-page.component.spec.ts
    my-home-page.component.template.pug
    my-home-page.component.ts
    my-home-page.module.ts

These will be fully populated with the basics they'll need.
