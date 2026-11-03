# Easy Isometric

Easy Isometric is a pipe isometric drawing app for iPad and iPhone. Create drawings, calculate dimensions, and share a drawing with its bill of materials as a PDF.

- [Get Easy Isometric on the App Store](https://apps.apple.com/us/app/easy-isometric-pipe-iso-app/id1463534058)
- [Visit the website](https://www.easyisometric.com/)
- [What's new](https://www.easyisometric.com/whats-new/)
- [Read the changelog](CHANGELOG.md)
- [Contact support](https://www.easyisometric.com/#contact)
- [Terms and privacy](https://www.easyisometric.com/terms-and-conditions/)

This repository contains public product information and release notes.

## Release notes

`CHANGELOG.md` is the shared source for this repository and the website's What's New page. The website builds the page from a verified revision of that file. It does not keep a separate copy of the notes in its source repository.

Entries distinguish App Store releases, internal TestFlight previews, website updates, and work in development. A preview entry does not mean that a feature is available in the App Store app.

## Update the changelog

1. Edit `CHANGELOG.md`. Put the newest entry first. Use short sentences that describe what changes for the customer.
2. Confirm the version, release date, and availability. Do not give unreleased work an App Store release date.
3. Merge the reviewed notes here.
4. In the website checkout, run `npm run update:changelog --prefix website`. This records the public commit and its content checksum.
5. Review and publish the website change through its existing release process.

Keep customer information, credentials, and internal test records out of this repository. Use the support link for account or subscription questions.
