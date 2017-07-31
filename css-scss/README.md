# CSS & SCSS Code Style

There is nothing worse than maintaining another developers stylesheets who have no standards or organization. Our goal is to create consistency in style, architecture, and methodology.

## Style

Instead of re-inventing the wheel, we piggy back on the hard work over at AirBnB and use their style guide. It falls in line with what we would have produced anyway.

[AirBnB CSS](https://github.com/airbnb/css)

## Methodology

We understand that the *hardest* part of designing any sort of system is actually naming things. With that being said, we strive to adhere to the [BEM](http://getbem.com/naming/) `Block--Element__Modifier` approach to our SCSS.

## Linting

Linting your code is not only recommended, it should be a requirement. There really isn't a good reason to not lint, but if you think of one please submit a pull request and I'll be sure to mark it closed without actually reading it.

We rely on the npm module [sass-lint](https://www.npmjs.com/package/sass-lint) to do the processing. At Jump, this is bundled automatically into our projects using our [project-baseplate](https://github.com/JUMP-Agency/project-baseplate).
