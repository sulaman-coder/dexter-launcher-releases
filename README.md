# Dexter Client

Dexter Client is an independently maintained Minecraft Java launcher and client focused on performance and quality-of-life features. It is not an official Minecraft product and is not affiliated with Mojang Studios or Microsoft.

## Download

[Dexter Client 1.4.3](https://github.com/sulaman-coder/dexter-launcher-releases/releases/tag/v1.4.3) is the current Windows x64 premium-only AppID review candidate. Choose the installer for an installed application, or extract the complete portable ZIP. Java 25 and JavaFX are included. Seven matching client JARs, checksums and validation information accompany the release.

**Minecraft Services access is pending.** Earlier authorized sign-ins completed Microsoft OAuth, Xbox Live and XSTS, then Minecraft Services returned HTTP 403. The dedicated Microsoft window has been tested for page loading and cancellation. Full premium login, live ownership/profile validation and token refresh are not yet verified. An approval request is not an approval grant; publisher verification is a separate process.

## Accounts and gameplay

The current public build requires a Microsoft account and verified Minecraft Java ownership before gameplay, including on servers that do not authenticate players. It does not offer username-only offline gameplay. Historical offline testing is kept separately and privately, without the reviewed public application ID.

Sign-in opens Microsoft's own HTTPS pages in a dedicated application window using authorization-code PKCE, rather than the previous device-code prompt. Credentials belong on Microsoft's page. The launcher uses Dexter's own registered public application; no borrowed launcher application ID or client secret is shipped.

## Updates

Installed Dexter applications check this repository and can download verified updates and offer Update & restart. Stable releases use version tags such as v1.4.3 and include GitHub SHA-256 asset digests. Portable applications are replaced manually. Draft, prerelease and updatetest- releases are excluded from the stable channel.

Read each release's VALIDATION.md for the observed download, installation and relaunch results. Historical results do not prove a newer release's installation. Old preview launchers are historical projects and are not proof of compatibility with this client.

## Distribution and support

This repository distributes binaries, required license notices, checksums, user instructions and compact validation information. Dexter implementation source and fork patches are maintained privately and are not uploaded here. Original and third-party components retain their existing copyrights and licenses; required notices remain included.

Optional backend services and private addons are not included or configured. No live store, paid membership, social service or Discord reward is claimed. No user accounts, worlds, tokens, private test tools or signing material belong in this repository.

Community and support: [Dexter Discord](https://discord.gg/dexterai).
