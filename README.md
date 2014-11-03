What is Kings Stones?
==============

An alternative cryptocurrency disrupting the already rather disrupting crypto market.

Technical Information

+ ~28477200 coins (Kingstons current population 23,731 muliplied by the average costs of rent for a one room apt plus utilities 1,200USD)
+ 8 coins rewarded per block, halving every 4 years (Current minimum wage is 7.25USD assuming that Kings Stones are worth 1.00USD miners will recieve 8 coins per hour)
+ 60 minutes block times
+ difficulty retargeting using a time-warp resistant implementation of KGW

Notable differences from Bitcoin
-----------------------------

+ replacement of ECDSA with Schnorr signing
+ use of secp256r1 curve over secp256k1
+ requirement for public key when verifying transactions

Modifications to the RPC API
+ verifymessage <publickey> <signature> <message>
+ makekeypair [hex-encoded prefix]
+ dumppubkey <maxcoinaddress>

Additional technical details can be found in the [Wiki](https://github.com/LinuxPhreak/kings-stones/wiki/_pages).

Forked from Maxcoin reference wallet 0.8.5 and Blakecoin

License
------

Kings Stones is released under the terms of the MIT license. See `COPYING` for more
information or see http://opensource.org/licenses/MIT.
