# Revision history for schematic

## 0.6.0.0 -- 2020-02-04

Added compatability with aeson-1.4.3.0. Since version 1.4.3 the module `Data.Aeson` started exporting `JSONPath`, which was conflicting with our own `JSONPath`. Furthermore, started using `JSONPathElement` from `aeson` instead of `DemotedPathSegment`.

## 0.5.0.0 -- 2019-02-20

GHC 8.6, json generation by schema definition, validation bug fixes, better
parsing error messages.

## 0.4.3.0 -- 2018-07-12

GHC 8.4 support, dropping support for older GHC versions

## 0.4.2.0

Support ghc-8.4 and drop support for older versions

## 0.4.1.0 -- 2017-11-05

Convenience isomorphisms: txt, num, opt, bln etc

## 0.4.1.0 -- 2017-11-01

flens and fget now use type application syntax

## 0.4.0.0 -- 2017-10-17

Object building DSL, more convenience helpers, MCons simplified with Tagged

## 0.3.2.0 -- 2017-10-02

Fixed FIndex bug, added bunch of convenience isomorphism, re-exports.

## 0.3.1.0 -- 2017-09-28

Add UUID and ISO8601 helpers, json schema constraint export, fsubset lens
combinator.

## 0.3.0.0 -- 2017-09-28

Updated to GHC 8.2.1 and singletons 2.3.1

## 0.2.1.0 -- 2017-09-26

Add decodeAndValidateVersionedWithPureMList, fix tests

## 0.2.0.0 -- 2017-09-26

Migratable is deprecated, migrations are now possible in an arbitrary monad.

## 0.1.5.0 -- 2017-08-22

Lens compatibility for typed json objects.

## 0.1.0.0  -- YYYY-mm-dd

* First version. Released on an unsuspecting world.
