# Changelog

## 6.1.0-beta.3 - 2021-04-02

- Added a configuration option named `use_follower_reads_for_type_introspection`.
  If true, it improves the speed of type introspection by allowing potentially stale
  type metadata to be read. Defaults to false.

## 6.1.0-beta.2 - 2021-03-06

- Improved connection performance by refactoring an introspection
  that loads types.
- Changed version numbers to semver.

## 6.1.0beta1

- Initial support for Rails 6.1.
- Support for spatial functionality.
