# Sideway Bug Bounty Disclosure Program

Effective: September 17, 2016

The software security research community makes the web a better, safer place and we support
their bug-hunting efforts with a bounty program.

To report a vulnerability, please email us at [support@sideway.com](mailto:support@sideway.com).

## Qualifying Vulnerabilities

The following domains and apps are within the scope of the program:

- sideway.com
- www.sideway.com
- api.sideway.com
- login.sideway.com
- embed.sideway.com
- sidewayembed.com
- sdwy.it

To be eligible, you must demonstrate a security compromise on any of these domains using a
reproducible exploit, including the following:

- Cross-site scripting exploitsd.
- Cross-site request forgery exploits.
- Authentication or authorization flaws.
- Official Sideway mobile apps or API flaws.
- Server-side code execution bugs.
- Injection flaws.
- Significant security misconfigurations.

These vulnerabilities do not qualify for the bounty program:

- Self-XSS.
- Login/logout CSRF.
- CSRF configuration issue without exploitable proof of concept.
- Missing security headers which do not lead directly to a vulnerability.
- Vulnerabilities in third party components use by Sideway, depending on severity and
  exploitability. For instance, we try to keep up to date with node.js versions but not
  all security issues impact Sideway's configuration.
- Bugs that require unlikely user interaction or phishing.
- Rate Limit on emails sent during sign-up, sign-in, and change email confirmations.
- Previous email login links not invalidated in the event multiple login links are requested.

## Rules for You

- Don't make the bug public before it has been fixed.
- Don't attempt to gain access to another user's account or data. Use your own test accounts
  for cross-account testing.
- Don't perform any attack that could harm the reliability or integrity of our services or data.
  DDoS or spam attacks are not allowed.
- Do not impact other users with your testing, this includes testing for vulnerabilities in
  accounts you do not own. We may suspend your Sideway account and ban your IP address if you do so.
- Don't use scanners or automated tools to find vulnerabilities. They're noisy and we may suspend
  your Sideway account and ban your IP address.
- Never attempt non-technical attacks such as social engineering, phishing, or physical attacks
  against our employees, users, or infrastructure.
- The more thorough the proof-of-concept, the higher the chance a payout will be awarded.
- When in doubt, email us at [support@sideway.com](mailto:support@sideway.com).

## Rules for Us

- We will respond as quickly as possible to your submission.
- We will keep you updated as we work to fix the bug you submitted.
- We will not take legal action against you if you play by the rules and act in good faith.

## Rewards

Based on severity of the bug and completeness of the submission, which we will decide at our sole
discretion, we offer the following rewards:
- Remote code execution: $1000
- Unrestricted access to file systems or databases: $500
- Bugs leaking or bypassing significant security controls: $250
- Execute code on the client, including XSS: $100
- Open redirect (excluding the sidewayembed.com domain): $100
- Other valid security vulnerabilities: up to $100

## Legal things and final notes

We don't work with vulnerability brokers. The purpose of this program is to fix bugs, not benefit
third parties.

Any individual residing in a country that is on a United States restricted export control list,
or any individual on a United States state or federal criminal wanted list or restricted export
control list, is not eligible to participate.

We will make the final decision on bug eligibility and value. Don't treat this program like a game
or business plan. The program exists entirely at our discretion and may be canceled at any time.
Thanks in advance for helping us out.
