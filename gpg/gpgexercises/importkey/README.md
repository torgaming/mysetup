This directory is for exercises based around the gpg --import example.asc command.

- A PGP key starts with "-----BEGIN PGP PUBLIC KEY BLOCK-----" and ends with "-----END PGP PUBLIC KEY BLOCK-----".
- You copy the entirety of that text and everything in between so a real PGP key could look like this:

-----BEGIN PGP PUBLIC KEY BLOCK-----
This is a fake key. You can try to put it into a file and attempt to
gpg --import key.asc it but I assume it's gonna give some sort of error
-----END PGP PUBLIC KEY BLOCK-----
