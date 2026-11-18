# Dexter Client

Dexter Client is an independently maintained Minecraft Java launcher and client focused on performance and quality-of-life features. It is not an official Minecraft product and is not affiliated with Mojang Studios or Microsoft.

## Download

[Dexter Client 1.4.4](https://github.com/sulaman-coder/dexter-launcher-releases/releases/tag/v1.4.4) is the current Windows x64 release. Choose the installer, or extract the complete portable ZIP. Java 25 and JavaFX are included. Seven matching client JARs, checksums, required notices and validation information accompany the release.

## Accounts

Open the account menu → Add account, then choose **Microsoft account** or **Offline account**. Offline accounts use a saved username for single-player and servers configured to accept offline identities. They do not grant premium access or work on servers requiring authenticated identities. Username-only failures do not bypass Microsoft account verification.

Microsoft sign-in opens Microsoft's genuine HTTPS form in a dedicated window using authorization-code PKCE, with the custom Minecraft background. No device-code prompt or client secret is shipped. Dexter uses its own registered public application ID. Close the window with X to cancel.

**Minecraft Services access is unconfirmed.** Earlier authorized sign-ins completed Microsoft OAuth, Xbox Live and XSTS, then Minecraft Services returned HTTP 403. Full premium ownership/profile retrieval, refresh and authenticated gameplay remain unverified. Loading and closing the sign-in page is not a completed login. Publisher verification is a separate process.

The earlier AppID application described a premium-only public candidate. This release adds public offline accounts at the owner's request. It does not satisfy the review form's ownership-before-all-gameplay requirement, and no approval covering this changed scope is claimed.

## Updates

Installed Dexter applications check this repository for stable releases, download assets verified against GitHub SHA-256 digests, and offer Update & restart. Profiles receive their updated matching client on the next launch. Portable copies are replaced manually. Drafts, prereleases and update-test releases are excluded from the stable channel.

Read each release's VALIDATION.md and validation ZIP for its actual checks and limitations. Historical update results do not establish that a newer version installed successfully.

## Distribution and support

This repository contains distribution information and releases with binaries, notices, checksums and compact validation. Implementation source and patches remain private. Repository separation and an installer-only download layout remain deferred. Third-party font/library notices are included with the packages.

Optional backend services and private addons are not deployed or configured. No live store, paid membership, social service or Discord reward is claimed. Accounts, worlds, tokens, private testing tools and signing material are not release assets.

Community and support: [Dexter Discord](https://discord.gg/dexterai).
