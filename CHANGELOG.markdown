0.15.1
------
* Nathan van Doorn fixed a number of embarassing bugs in the `Enum` instances.

0.15
----
* `instance IsList NonEmpty`

0.14
----
* Allow for manual removal of dependencies to support advanced sandbox users who explicitly want to avoid compiling certain dependencies
  they know they aren't using.

  We will fix bugs caused by any combination of these package flags, but the API of the package should be considered the default build
  configuration with all of the package dependency flags enabled.

* Will now build as full-fledged `Safe` Haskell if you configure with -f-hashable.

* Added some missing `Generic`/`Generic`/`Hashable` instances

0.13.0.1
--------
* `Generic` support requires `ghc-prim` on GHC 7.4.

0.13
----
* Added instances for 'Generic', 'Foldable', 'Traversable', 'Enum', 'Functor', 'Hashable', 'Applicative', 'Monad' and 'MonadFix'

0.12.2
------
* Vastly widened the dependency bound on `text` and `bytestring`.

0.12.1
-------
* Updated to support the new version of `text`.
* Added `transpose`, `sortBy` and `sortWith`.

0.12
----
* Added an instance for `Const r`.
* Added `some1`

0.11
----
* Added the missing instance for `HashSet`.

0.10
----
* Added support for `unordered-containers`, `bytestring` and `text`.

0.9.2
-----
* Added a `DefaultSignature` for `(<>)` in terms of `mappend`.


0.9.1
-----
* Added `timesN`.

0.9
---
* Moved `Numeric.Natural` to a separate `nats` package.
