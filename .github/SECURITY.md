# Security Policy
*Security Policy revision 1.0.1*

We take security and privacy extremely seriously. It has been a top priority for us since the before launch of GamesROB's parent bot, Rescue Bot was even open to Staff members.
With that said, we want to give people a way to communicate issues to us in a professional manor, and we may even offer rewards to those who do.

## Our approach to security issues
- We will not take action against those disclosing issues¹
- Even inaccurate or invalid² issues will be responded to as fast as possible. First with acknowledgement then with investigation and (if applicable) resolution.
- We will (to the best of our ability) share *safe information³* with you on how and when the issue will be resolved.
- Dependant on how severe the issue was and other factors, we may choose to reward you for reporting the vulnerability. This widely varies depending on the issue, but it may include something like a Discord Nitro gift or 'cash' via a platform like PayPal.

## Reporting a Vulnerability

You can report vulnerabilities to security( a t }gamesrob{ d o t )com, just make sure you follow and agree to these guidelines:
1. Your email should not contain details about the vulnerability or what it affects in the subject, only in the content of the email itself.
2. Please replace any personally sensitive details or information about you or anyone else with `[redacted]`.
3. Do not disclose the vulnerability itself to anyone, not even @GamesROB/gamesrob-owners without using the email above to communicate about vulnerabilities, regardless of the severity.
4. Do not tell anyone that you have found or disclosed a vulnerability in any way.
5. If you do not specify whether you would like to be credited with discovering this vulnerability, we will assume you'd like to be kept anonymous.
6. We may publicly disclose any vulnerabilities in any form we would like. This includes complete disclosure or partial. (While respecting privacy and anonymity if applicable).
7. The only versions relevant to us are those that are ones in a production, public testing, or newer.

## Non-vulnerabilities
There are some things that while they could be considered vulnerabilities, they are not applicable to this program and are potentially unavoidable (those listed below already have had mitigation strategies put in place). A rough (incomplete) list goes as follows:
- Denial of Service attacks
- Vulnerabilities that are caused by a third party (for example, a bug with Java that Oracle needs to fix).
- Vulnerabilities that only negatively affect:
  - users on non-[stable](https://discord.com/download) versions of Discord (such as [PTB](https://ptb.discord.com/api/downloads/distributions/app/installers/latest?channel=ptb&platform=win&arch=x86), [Canary](https://canary.discord.com/api/downloads/distributions/app/installers/latest?channel=canary&platform=win&arch=x86),
  [Development](https://canary.discord.com/api/downloads/distributions/app/installers/latest?channel=development&platform=win&arch=x86), or [staging](https://staging.discord.co) branch versions), these issues should be reported to the [Discord Security Bug Bounty](https://discord.com/security) program.
  - users using unofficial client modifications (such as [BetterDiscord](https://bd.zerebos.com/#tos))
  - users using [Automated user accounts (self-bots)](https://support.discord.com/hc/articles/115002192352).
  - users violating any other portion of the [Discord Guidelines](https://discord.com/guidelines), [Discord Terms of Service](https://discord.com/terms), or [Discord Developer Terms of Service](https://discord.com/developers/docs/legal))
- Targetted attacks (for example, an attack that involves first gaining access to one of the @GamesROB/gamesrob-owners' devices)
- Attacks involving literal fraud (for example, sim-swapping or impersonating the @GamesROB/gamesrob-owners while contacting the provider for a service we use)

*¹Assuming that the issue was disclosed without malicious intent or previous malicious use by said discloser. This exception is to prevent someone from abusing a security vulnerability and then reporting it to discard responsibilty and obtain immunity through this program.*
*²Invalid issues are issues that we have deemed to not be issues. An example of this would be if someone thought something intentional was a security issue.*
*³Safe information is information that at the current time we do not consider too private or detremental to avoid revealing. An example of potentially safe information would be a package version, an example of likely **un**safe information would be a password.*
