# Opsec guidelines for protocols building in and around Berachain

<h1>Devices</h1>
- Use a dedicated device per task e.g. linux notebook for pushing commits, another one for signing multisig txs, another one to ssh into validator (stay away from Windows)<p></p>
- Monitor devices, set up alerts for odd behavior<p></p>
- Airgap critical devices whenever not in use<p></p>
- Keep software updated at all times<p></p>

<h1>Two Factor Authentication</h1>
- SMS is the worst, Google Auth (without backup) is slightly better, Yubikey is the best<p></p>
- 2FA codes generated on Yubikeys stay on the device, Google 2FA can be phished from you and then automated via necrobrowser (all ur sessions are taken over in seconds)

<h1>Social Engineering</h1>
- No reporter from Cointelegraph will reach out via Discord and a dodgy Russian link. If you do so and lose your server, ur community should hold u accountable for gross negligence<p></p>
- Disable all phone calls and DMs from non contacts on Telegram<p></p>
- Be wary of recruitment scams<p></p>
- Do not hire North Korean engineers (say 'fuck kim jong un' works 90% of the time)<p></p>
- DO NOT download videoconferencing software

<h1>Discord</h1>
    - Roles given on 'need to know' basis e.g. mention everyone/all/here<p></p>
    - Server owner is transferred to a cold Discord account living on an old phone you're not using<p></p>
    - 2FA (explained above)<p></p>
    - Don't use Discord's custom invite feature, those can expire when boosts fall off and scammers will take over the link. Instead use a subdomain in your own DNS.

<h1>Hardware wallets</h1>
    - Order hardware wallets to a PO box (Ledger notoriously loses your address to Russian hackers)<p></p>
    - Get 1 of each popular Vendor to mitigate against firmware exploit, hardware issues, loss<p></p>
    - Read what you sign (if blind signing, do it from a wallet with non lethal amount)<p></p>

<h1>Honeypot</h1>
    - On each device used for work, store one hot wallet with ~200$ of ETH, the seed phrase locally and in your personal cloud. Set up Sentry alert for when funds move. Funds move = Malware, wipe everything at once

<h1>DNS</h1>
If you do decent volume, chances are 99% ur DNS will be exploited. These are either insider jobs and/or social engineering scams:
An attacker will convince ur DNS host to reroute ur domain to a fake frontend that connects to a drainer. No 2fa/password complexity will save u from this<p></p>
Prepare a document:
    - Where are DNS nameservers hosted?
    - Who is the admin of the account?
    - How do I reach support?
Drill your team in the process, because it is very likely to happen

DNS fallbacks:
    - Set up a decentralized frontend on your favorite decentralized storage host. It's slow, but it can be utilized during a takeover.
    - Have comms ready to go out to not interact with your dapp

<h1>Twitter</h1>
    - Similar to DNS, it is likely your Twitter account will be compromised with drainer links shared due to insider jobs.
Prepare a document:
    - Who has access to Twitter account?
    - How do I get in touch with Twitter support?
    - Do you know anyone at Twitter support?
Drill your team in the process, because it is very likely to happen

<h1>Smart Contract Exploit</h1>
    - Get in touch with the audit firm that audited your contracts
    - Reach out to Seal911 https://github.com/security-alliance/seal-911#members
    - Have comms ready to go out to not interact with your dapp







