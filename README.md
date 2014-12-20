# Gentoo+`crossdev` Wercker box [![wercker status](https://app.wercker.com/status/f2a2e1e43d297a4c10716306a26d2527/s "wercker status")](https://app.wercker.com/project/bykey/f2a2e1e43d297a4c10716306a26d2527)

A Wercker box that contains a Gentoo chroot with `crossdev` installed.

## But why‽

To be used as a base image for other wercker boxes containing crossdev toolchains.

See [`wercker-box-gentoo`][1] for a detailed explanation.

## `crossdev` version

The current `crossdev` version is **20141030**. If there is a newer version
available [in Portage][2], just send me a pull request and I'll merge it.

[0]: https://app.wercker.com/#applications/5495c90c07fa3ea41500d357/tab/details
[1]: https://github.com/attilaolah/wercker-box-gentoo
[2]: http://packages.gentoo.org/package/sys-devel/crossdev
