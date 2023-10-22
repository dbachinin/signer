## 1.10.1 (2023-10-22)

- Add custom prefix for SignedInfo

## 1.10.1 (2023-10-20)

- Add custom prefix for SignedInfo

## 1.10.0 (2021-10-22)

- Ensure compatibility with Nokogiri 1.12.4+ (#31, @flavorjones)
- fix #26: add xml-exc-c14n Transform when :enveloped option is true. (#27, @kunxi)

## 1.9.0 (2019-04-16)

- Refactor digest!() method for better extensibility, add GOST-R 34.10/11-2012 algorithms, fix digest node ID reference, cleanup (#22, @netcitylife)

## 1.8.0 (2018-11-14)

- Add parameter to customize canonicalize algorithm (#19, @pistachiology)
- Add references node type on digest (for xades-bes signing properties) (#19, @pistachiology)
- change issuer x509 content to be more standard way (#19, @pistachiology)

## 1.7.0 (2018-11-06)

- Add wss option for XML only signing (#18, @pistachiology)
- Add support for SHA512 Digest
- Rename id for SHA256 Digest

## 1.6.0 (2017-09-14)

- X509 in SecurityTokenReference node (#17, @tiagocasanovapt)

## 1.5.1 (2017-03-23)

- Allow to set up custom xmldsig namespace prefix for Signature node (#14, @Envek)

## 1.5.0 (2017-01-23)

- Add posibility to disable noblanks method in Signer initialization (#16, @bpietraga)
- Minimum ruby version is now 2.1

## 1.4.3 (2015-10-28)

- Fixed Issuer Name node (#8, @tiagocasanovapt)

## 1.4.2 (2014-11-30)

- Fixed behaviour on XMLs that already contains nested signatures somewhere

## 1.4.1 (2014-09-09)

- Changed method of getting GOST R 34.11-94 digest algorithm to more short and generic (and working in Ubuntu 14.04 and other OS)

## 1.4.0 (2014-06-24)

- Support signing and digesting with inclusive namespaces (#5, @Envek)

## 1.3.1 (2014-06-24)

- Fix namespace issue for SecurityTokenReference tag (#4, #@Envek)

## 1.3.0 (2014-06-16)

- Allow to sign with other digest algorithms - SHA1, SHA256, and GOST R 34.11-94 (#3, @Envek)

## 1.2.1 (2014-05-14)

- Fix canonicalization: should be without comments (#2, @Envek)

## 1.2.0 (2014-05-06)

- Id and attribute namespace preserving when digesting the nodes (#1, @Envek)

## 1.1.1 (2013-04-03)

- Allow to sign using enveloped-signature

## 1.1.0 (2012-06-21)

- Allow to sign XML documents without SOAP

## 1.0.0 (2012-05-03)

- Allow to sign SOAP documents
