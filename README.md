# Opsec guidelines for protocols building in and around Berachain

<h1>Devices</h1>
- Use a dedicated device per task e.g. linux notebook for pushing commits, another one for signing multisig txs, another one to ssh into validator (stay away from Windows)<p></p>
- Monitor devices, set up alerts for odd behavior

<h1>Two Factor Authentication</h1>
- SMS is the worst, Google Auth (without backup) is slightly better, Yubikey is the best<p></p>
- 2FA codes generated on Yubikeys stay on the device, Google 2FA can be phished from you and then automated via necrobrowser (all ur sessions are taken over in seconds)

<h1>Social Engineering</h1>
- No reporter from Cointelegraph will reach out via Discord and a dodgy Russian link. If you do so and lose your server, ur community should hold u accountable for gross negligence<p></p>
- Disable all phone calls and DMs from non contacts on Telegram<p></p>
- Be wary of recruitment scams<p></p>
- DO NOT download videoconferencing software<p></p>

<h1>Discord</h1>
  This should be an entire section on its own:
    - Roles given on 'need to know' basis e.g. mention everyone/all/here<p></p>
    - Server owner is transferred to a cold Discord account living on an old phone you're not using<p></p>
    - 2FA (explained above)<p></p>
    - Don't use Discord's custom invite feature, those can expire when boosts fall off and scammers will take over the link. Instead use a subdomain in your own DNS.

<h1>Hardware wallets</h1>
    - Order hardware wallets to a PO box (Ledger notoriously loses your address to Russian hackers)<p></p>
    - Get 1 of each popular Vendor to mitigate against firmware exploit, hardware issues, loss<p></p>
    - Read what you sign

<h1>Honeypot</h1>
    - On each device used for work, store one hot wallet with ~200$ of ETH, the seed phrase locally and in your personal cloud. Set up Sentry alert for when funds move. Funds move = Malware, wipe everything at once





