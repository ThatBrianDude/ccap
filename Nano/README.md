# CCAP - Nano Specific Protocols

The POST /ccap/address endpoint will only CREATE addresses in regards to Nano, it will not UPDATE. The reason being that Nano addresses do not change for the same account like Bitcoin or many other currencies, so there is no reason to open up the potential attack vector.

If a server wants to add UPDATE functionality it must be through some other method, and can include further security options like 2FA, captchas, or whitelisted IP addresses.