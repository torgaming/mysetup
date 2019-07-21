In the past I knew how to use a graphical gpg program in Whonix, but now all this knowledge is practically gone, because it was so long ago and not documented or linked to in a dependable way.

This exists as a resource for anybody who's using a recent version of Whonix and for them to feel welcome and find the tools to join the web of trust(not the "fake" or "pretend wot" ones that got little or no cryptography technology as a basis for the web-of-trust system)

1. https://www.whonix.org/wiki/Whonix_Signing_Key#Web_of_Trust
2. https://www.whonix.org/wiki/OpenPGP#The_OpenPGP_Web_of_Trust

Starting off with gpg we may realize that we don't have any keys at all, we might start off empty unless some keys have been downloaded. As I start off in my version of Whonix I got no keys so I start with adrelanos key:

http://dds6qkxpwdeubwucdiaord2xgbbeyds25rbsgr73tbfpqpt4a6vjwsyd.onion/patrick.asc

Store all keys(public keys) in ~/Downloads/keys/
* cd ~/Downloads/keys/
- if there's no such directory/directories create it/them then cd into it like shown above

- let's download patrick's key: 
* wget dds6qkxpwdeubwucdiaord2xgbbeyds25rbsgr73tbfpqpt4a6vjwsyd.onion/patrick.asc
- Done.

* gpg --import patrick.asc
- part of the message is this
-- gpg: key 0x8D66066A2EEACCDA: 86 signatures not checked due to missing keys
-- gpg: key 0x8D66066A2EEACCDA: public key "Patrick Schleizer <adrelanos@riseup.net>" imported
- two obvious options:
1. Learn more about the 86 signatures which may include 86 or less keys belonging to other people/entities, but not gonna be covered by this README.md.
2. Not recommended option: email adrelanos@riseup.net while using the key to encrypt the message and wait for a reply. The reason I don't recommend this option is because you are not relying on only yourself to learn more, but I could suggest this option in addition to continuing with other options.

These files are going to help(located in the same directory):
- gpgweboftrust.txt - after importing patrick.asc key, more options to join the web of trust and to verify it




