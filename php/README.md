# PHP Code Style

What can we say about PHP...it owes its existence to WordPress. Sure, cool MVC frameworks exist and are in wide use, but we aren't sure it would still be thriving if it weren't for WordPress. We (or should I say, "I") could be wrong though...this is coming from someone who still thinks Jurassic Park is a historical drama despite being debunked repeatedly as such.

## Style

We follow what we consider to be the industry standard of [PSR-2](http://www.php-fig.org/psr/psr-2/)

### Commenting Suggestions
When using a regular expression comment a brief explanation (using PHPDoc styling) of what it matches above it's usage. See below for an example.
```
/**
 *  Matches on  "City With Spaces, KY 55555-3333"
 *
 *  The last four zip code digits are optional. Example, 
 *  the following string will produce a truthy value:
 *    "Louisville, KY 40299" => true
 *    "Louisville, KY 40299-1111" => true
 *    "Louisville, KY" => false
 */
```

## Linting

Linting your code is not only recommended, it should be a requirement. There really isn't a good reason to not lint, but if you think of one please submit a pull request and I'll be sure to mark it closed without actually reading it.

We rely on the npm module [phpcs](https://github.com/squizlabs/PHP_CodeSniffer) to do the processing.

