# SASS Mixins
Custom SASS Mixins, with updated prefixes based on [Can I Use](http://caniuse.com/) .

## Table of Content

#### Animations
> Usage: `@include animation(name 5s linear 2s infinite alternate);`

#### Appearance
> Usage: `@include appearance(none);`

#### CSS Arrows
> Usage: `@include arrow($direction, $width, $height, $color);`

#### Backface Visibility
> Usage: `@include backface-visibility(none);`

#### Background Size
> Usage: `@include background-size($x $y);`

#### Columns
> Usage: `@include columns(2 50%);`

#### Filter
> Usage: `@include filter(blur(5px));`

#### Flex
> Usage: `@include flexbox;` or `@include inline-flex;`

#### Font
> Usage: `@include font('Lato Bold', lato-bold, '7h48gd3bd', 300, italic);`

#### Gradient
> Usage: `@include linear-gradient(#31B7D7, #EDAC7D);`

#### Keyframes
> Usage: ```@include keyframes(name) {...}```

#### Media Queries
> Usage: `@include breakpoint(1024) {...}` or `@include screen('mobile'){...}`

#### Placeholder
> Usage: `@include placeholder {...}`

#### REM Unit
> Usage: `@include size(32);`

#### Transforms
> Usage: `@include transform(rotate(45));` or `@include rotate(45);`

#### Truncate
> Usage: `@include truncate(200px);`

#### User Select
> Usage: `@include user-select(none);`

#### Vertical Align
> Usage: `@include vertical-align(50%);`


## Contributing

1. Fork it!
2. [b]Create[/b] your feature branch: `git checkout -b my-new-feature`
3. [b]Commit[/b] your changes: `git commit -m 'Add some feature'`
4. [b]Push[/b] to the branch: `git push origin my-new-feature`
5. [b]Submit[/b] a pull request!