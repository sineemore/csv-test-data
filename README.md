csv-test-data
=============

A collection of small CSV files and corresponding JSON representation to help in developing and testing [RFC 4180][1] compliant parsers.

### Naming convention

- `bad-` files contain invalid CSV, these files don't have corresponding JSON representation
- `bad-header-` files contain invalid CSV with header
- `header-` files contain valid CSV with header
- All other files contain valid CSV without header

All files named `bad-header-` and `header-` are expected to be parsed with header `foo,bar,baz`.

All valid CSV files have corresponding JSON file.

[1]: https://tools.ietf.org/html/rfc4180