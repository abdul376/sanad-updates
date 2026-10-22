# Sanad updates

Signed update packages for Sanad by PAQN (https://paqn.network).

Each release holds an update package signed with PAQN's Ed25519 key. The app
verifies the signature with the public key it ships with and refuses anything
that does not match. The `latest` release carries `latest.json`, the only file
the app requests when it checks for updates. No user data is ever sent.
