## variables

#### Variables are a way to store information that you can re-use later.

#### With Sass, you can store information in variables, like:

#### With Sass, you can store information in variables, like:

#### strings

#### numbers

#### colors

#### booleans

#### lists

### nulls

#### Sass uses the $ symbol, followed by a name, to declare variables:

## import

#### Just like CSS, Sass also supports the @import directive.

#### The @import directive allows you to include the content of one file in another.

#### The CSS @import directive has a major drawback due to performance issues; it creates an extra HTTP request each time you call it. However, the Sass @import directive includes the file in the CSS; so no extra HTTP call is required at runtime!

## Mixin

##### The @mixin directive lets you create CSS code that is to be reused throughout the website.

###### The @include directive is created to let you use (include) the mixin.

## extend

##### The @extend directive lets you share a set of CSS properties from one selector to another.

###### The @extend directive is useful if you have almost identically styled elements that only differ in some small details.
