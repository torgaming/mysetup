In the past I knew how to use a graphical gpg program in Whonix, but now all this knowledge is practically gone, because it was so long ago and not documented or linked to in a dependable way.

This exists as a resource for anybody who's using Whonix 14 and for them to feel welcome and find the tools to join the web of trust(not the "fake" or "pretend wot" ones that got little or no cryptography technology as a basis for the web-of-trust system)

1. https://www.whonix.org/wiki/Whonix_Signing_Key#Web_of_Trust
2. https://www.whonix.org/wiki/OpenPGP#The_OpenPGP_Web_of_Trust

Starting off with gpg we may realize that we don't have any keys at all, we might start off empty unless you have downloaded some keys. As I start off in Whonix 14 I got no keys so I install an old debian keyring

sudo apt-get update && sudo apt-get install debian-keyring

