# Mix buttons #

> SASS Mixins for generate beautiful buttons

## Installation ##

* **bower**: `bower install mix-buttons`

## Usage ##

```
@import "mix-buttons";

.my-button {

  @include mix-button(
    $custom-font-color, /* default is #fff */
    $custom-background-color, /* default is #8cd1a8 */
    $custom-border-radius, /* default is 2px */
    $custom-font-weight, /* default is 600 */
    $custom-text-transform, /* default is capitalize */
    $boolean-is-button-ghost /* default is false */
  );

}
```

## Contributing ##

1. Fork it
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

---

#### [preview and doc](https://nandomoreirame.github.io/mix-buttons)

<a href="https://github.nandomoreira.me/mix-buttons">
  <img src="/doc/mix-buttons.jpg" alt="Mix buttons">
</a>

---

## License ##

It is free under the [open-source MIT license](/LICENSE).

Enjoy :yum:

by [nandomoreira.me](https://nandomoreira.me)
