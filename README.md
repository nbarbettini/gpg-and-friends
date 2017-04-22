# Signed commit playground

Do you have Git set up to sign your commits with GPG?

Want to try it out? This is the place! :+1:

You can see the Verified (signed) commits in the [commit log](https://github.com/nbarbettini/gpg-and-friends/commits/master). Your signed commits will show up as Verified if you share your public key with Github.

To view the signatures locally, run:

```
git verify-commit <commit hash>
```

To verify that the commits are signed by the person they say they are, you'll need to import that person's public key into your local keyring. To import mine, for example,

```
curl https://keybase.io/nbarbettini/pgp_keys.asc | gpg --import
```

This works because I've stored my public keys on [Keybase](https://keybase.io).

## Guestbook

Edit this file and add your name below. Sign the commit and send me a PR! :smile:

* Nate was here :sunglasses: - https://keybase.io/nbarbettini
* Micah was here :skull: - https://keybase.io/afitnerd
