 * Download [OpenSSL 1.0.2h](https://www.openssl.org/source/openssl-1.0.2h.tar.gz)
 * Download the latest [NSS certificate list](https://hg.mozilla.org/mozilla-central/raw-file/default/security/nss/lib/ckfw/builtins/certdata.txt)
 * Download the latest [mk-ca-bundle.pl](https://raw.githubusercontent.com/curl/curl/master/lib/mk-ca-bundle.pl) and make the following changes:
	* Remove `use LWP::UserAgent`
