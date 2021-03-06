# 3.2.0 - 2015-03-31

- Added: JS defined variables are now resolved too ([#22](https://github.com/postcss/postcss-custom-properties/issues/22))

# 3.1.0 - 2015-03-16

- Added: variables defined in JS are now automatically prefixed with `--`
  ([0691784](https://github.com/postcss/postcss-custom-properties/commit/0691784ed2218d7e6b16da8c4df03e2ca0c4798c))

# 3.0.1 - 2015-02-06

- Fixed: logs now have filename back ([#19](https://github.com/postcss/postcss-custom-properties/issues/19))

# 3.0.0 - 2015-01-20

- Changed: upgrade to postcss 4 ([#18](https://github.com/postcss/postcss-custom-properties/pull/18))
- Removed: some code that seems to be useless ([16ff3c2](https://github.com/postcss/postcss-custom-properties/commit/16ff3c22fe0563a1283411d7866791966fff4c58))

# 2.1.1 - 2014-12-02

- Fixed: issue when multiples undefined custom properties are referenced ([#16](https://github.com/postcss/postcss-custom-properties/issues/16))

# 2.1.0 - 2014-11-25

- Added: enhanced exceptions & messages

# 2.0.0 - 2014-11-12

- Changed: upgrade to postcss 3

# 1.0.2 - 2014-11-04

- Fixed: more clear message for warning about custom prop used in non top-level :root

# 1.0.1 - 2014-11-03

- Fixed: warning about custom prop used in non :root

# 1.0.0 - 2014-11-02

- Added: warning when a custom prop is used in another place than :root
- Added: handle !important

# 0.4.0 - 2014-09-30

- Added: JS-defined properties override CSS-defined

# 0.3.1 - 2014-08-27

- Added: nested custom properties usages are now correctly resolved
- Changed: undefined var doesn't throw error anymore (just a console warning) & are kept as is in the output

# 0.3.0 - 2014-08-26

- Changed: fallback now are always added by default ([see why](http://www.w3.org/TR/css-variables/#invalid-variables))
- Changed: `map` option renamed to `variables`

# 0.2.0 - 2014-08-22

- Added: `map` option
- Changed: GNU style error message

# 0.1.0 - 2014-08-01

✨ First release based on [rework-vars](https://github.com/reworkcss/rework-vars) v3.1.1
