imedge/node-provided-libs
=========================

This library is a proxy stating to provide all libs provided by an IMEdge Node
installation. To refresh those dependenies, please:

* raise the `imedge/node` version in `composer.json`
* remove the `replace` section
* run `composer refresh-provided-libs`

In case there are any changes, please release a new version  of this library.
