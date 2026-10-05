<!-- tyhp-readme:start -->
# tyhpdef/spatie-ignition

Tyhp type definitions for `spatie/ignition` `1.16.0`.

```bash
composer require --dev tyhpdef/spatie-ignition:1.16.0
```

This is a metapackage. Composer also installs `tyhpdef/spatie-ignition-impl` (type files).
Require **this** name, not `tyhpdef/spatie-ignition-impl`.

See https://tyhplang.com.

## Maintain `spatie/ignition`? Ship the types yourself

If you are a Packagist maintainer of `spatie/ignition`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/spatie-ignition-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `spatie/ignition` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/spatie-ignition": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `spatie/ignition` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `spatie/ignition` with a real constraint,
   `"replace": { "tyhpdef/spatie-ignition": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `spatie/ignition` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/spatie-ignition` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
