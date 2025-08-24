# CHANGELOG

> Package changelog.

<section class="release" id="unreleased">

## Unreleased (2025-08-24)

<section class="features">

### Features

-   [`35f5f7a`](https://github.com/stdlib-js/stdlib/commit/35f5f7a596e36f3faca5977838ee681df521139c) - add `math/base/special/binomcoeff` [(#7000)](https://github.com/stdlib-js/stdlib/pull/7000)

</section>

<!-- /.features -->

<section class="breaking-changes">

### BREAKING CHANGES

-   [`72d37f3`](https://github.com/stdlib-js/stdlib/commit/72d37f32cd8f38d0a073abe5180969af294dc975): update signature to accept floats

    -   User code should behave similarly in the primary case of providing integer-valued input values. However, no longer will real-values truncate. Now, real-valued inputs will result in `NaN`, which is, arguably, better behavior, as real-to-integer truncation can be a source of silent bugs.

</section>

<!-- /.breaking-changes -->

<section class="commits">

### Commits

<details>

-   [`72d37f3`](https://github.com/stdlib-js/stdlib/commit/72d37f32cd8f38d0a073abe5180969af294dc975) - **refactor:** modify C implementation to accept `float` values instead of `int32` in `math/base/special/binomcoeff` [(#7946)](https://github.com/stdlib-js/stdlib/pull/7946) _(by Gunj Joshi, Athan Reines)_
-   [`6b79837`](https://github.com/stdlib-js/stdlib/commit/6b7983771d584610fb460be6d521a98976e4da5e) - **bench:** fix C target in Makefile _(by Karan Anand)_
-   [`999cdb2`](https://github.com/stdlib-js/stdlib/commit/999cdb245ef44457920ac1fdc0d0e4dc67862e75) - **test:** remove non-number inputs from `NaN` test cases _(by Karan Anand)_
-   [`dc36e99`](https://github.com/stdlib-js/stdlib/commit/dc36e99948cf35b754e3038323926ba8a0f50d04) - **refactor:** remove redundant `f32` conversions _(by Karan Anand)_
-   [`26cd960`](https://github.com/stdlib-js/stdlib/commit/26cd96031731d66badef65b3c7160491d7b12ba6) - **bench:** move PRNG out of loop and update Makefiles _(by Karan Anand)_
-   [`35f5f7a`](https://github.com/stdlib-js/stdlib/commit/35f5f7a596e36f3faca5977838ee681df521139c) - **feat:** add `math/base/special/binomcoeff` [(#7000)](https://github.com/stdlib-js/stdlib/pull/7000) _(by Karan Anand, stdlib-bot)_

</details>

</section>

<!-- /.commits -->

<section class="contributors">

### Contributors

A total of 3 people contributed to this release. Thank you to the following contributors:

-   Athan Reines
-   Gunj Joshi
-   Karan Anand

</section>

<!-- /.contributors -->

</section>

<!-- /.release -->

