# Remote Working PSIRT Information

The novel coronavirus COVID-19 has led to many countries around the world mandating that citizens practice social distancing and stay at home. This has led to a huge surge in remote working. Organisations are rapidly adopting new technology solutions that allow users to access company resources and participate in remote meetings.

IT and Security Teams may not be familiar with the security arrangements, or where to keep up to date on security updates, for these new solutions.

This page aggregates a list of the most popular solutions in the following categories:

 - [Video Conferencing (VC)](#video-conferencing-vc)
 - [Virtual Private Network (VPN)](#virtual-private-network-vpn)
 - [Remote Access Gateway (RAG)](#remote-access-gateway-rag)

For each vendor there are links to:

 - Vendor-provided guidance and tips for securely configuring their software
 - Support sites where security advisories and updates can be found
 - Any notification options to have this information delivered to you automatically

### How you can help

_Please see the **Contributing** section below._


## Video Conferencing (VC)

Vendor | Configuration | Security Advisories | Notification Options
--- | --- | --- | ---
Bluejeans | [Security options for BlueJeans Meetings](https://www.bluejeans.com/blog/secure-video-conferencing-protecting-your-home-office-meetings) | [Bluejeans Security Advisories](https://www.bluejeans.com/trust-center/advisories) | (Unknown)
Cisco Webex | [Cisco Webex Best Practices for Secure Meetings](https://help.webex.com/en-us/v5rgi1/Cisco-Webex-Best-Practices-for-Secure-Meetings-Site-Administration) | [Cisco Webex Security Advisories, Responses and Notices](https://www.cisco.com/c/en/us/support/conferencing/webex-meeting-center/products-security-advisories-list.html) | (Unknown)
Google | [GSuite Security Center](https://gsuite.google.com/products/admin/security-center/) (Enterprise customers) | (Unknown) | (Unknown)
GoToMeeting | [GoToMeeting Web Conferencing Security (PDF)](https://logmeincdn.azureedge.net/gotomeetingmedia/-/media/pdfs/gotomeeting-security-white-paper-286395.pdf)] | [GoToMeeting Release Notes](https://community.logmein.com/t5/GoToMeeting-News/bg-p/GoToMeeting-Release-Notes/label-name/release%20notes) | Click 'Subscribe' from Release Notes
Microsoft Teams | [Security and compliance in Microsoft Teams](https://docs.microsoft.com/en-us/microsoftteams/security-compliance-overview) | [Security Update Guide](https://portal.msrc.microsoft.com/en-us/security-guidance) (Teams is not listed as a product) | [Microsoft Technical Security Notifications](https://www.microsoft.com/en-us/msrc/technical-security-notifications)
Slack | [Slack Security tips to protect your workspace](https://slack.com/intl/en-gb/help/articles/115004155306-Security-tips-to-protect-your-workspace) | [Slack updates and changes](https://slack.com/intl/en-gb/help/articles/115004846068-Slack-updates-and-changes) | (Unknown)
Zoom | [Security in Zoom](https://zoom.us/security) | [Zoom Help Centre - Security](https://support.zoom.us/hc/en-us/sections/201728933-Security) | Click 'Follow' on right-hand side


## Virtual Private Network (VPN)

Vendor | Configuration | Security Advisories | Notification Options
--- | --- | --- | ---
Check Point | [CheckPoint Remote Access VPN Administration Guide](https://sc1.checkpoint.com/documents/R80.10/WebAdminGuides/EN/CP_R80.10_RemoteAccessVPN_AdminGuide/html_frameset.htm) | [Check Point Advisories](https://www.checkpoint.com/advisories/) | [Subscribe](https://www.checkpoint.com/security-advisories-subscription/)
Cisco | [Cisco AnyConnect Configuration Guide](https://www.cisco.com/c/en/us/support/security/anyconnect-secure-mobility-client/products-installation-and-configuration-guides-list.html) | [Cisco Security Advisories](https://tools.cisco.com/security/center/publicationListing.x) | [Subscribe](https://tools.cisco.com/security/center/navigation.x?i=122) [RSS](https://tools.cisco.com/security/center/rss.x?i=44) [API](https://developer.cisco.com/psirt/)
F5 Networks | (Unknown) | [AskF5 New & Updated Articles](https://support.f5.com/csp/new-updated-articles) (needs manual filter for ‘Security Advisory under Document Type) | [Subscribe](https://interact.f5.com/F5-Preference-Center.html)
Fortinet | [FortiGate / FortiOS Tele-Working Guides](https://docs.fortinet.com/teleworking) | [FortiGuard PSIRT Advisories](https://fortiguard.com/psirt) | [RSS](https://fortiguard.com/rss-feeds)
Palo Alto Networks | (Unknown) | [Palo Alto Networks Security Advisories](https://security.paloaltonetworks.com) | [Subscribe](https://support.paloaltonetworks.com/SupportAccount/Preferences) [RSS](https://security.paloaltonetworks.com/rss.xml)
Pulse Secure | [Pulse Connect Secure: Security configuration best practices](https://kb.pulsesecure.net/articles/Pulse_Secure_Article/KB29805) | [Pulse Secure Security Advisories](https://kb.pulsesecure.net/?atype=sa) | [RSS](https://kb.pulsesecure.net/pkb_RSS?q=Pulse_Security_Advisories__kav;10)
WatchGuard | (Unknown) | [WatchGuard Security Portal](https://www.watchguard.com/wgrd-support/security-portal/overview) | (Unknown)


## Remote Access Gateway (RAG)

Vendor | Configuration | Security Advisories | Notification Options
--- | --- | --- | ---
Akamai | (Unknown) | [Akamai Release Notes](https://learn.akamai.com/en-us/release_notes_10/) | (Unknown)
Citrix | [Citrix Virtual Apps and Desktop: Security considerations and best practices](https://docs.citrix.com/en-us/citrix-virtual-apps-desktops/secure/best-practices.html) | [Citrix Trust Center](https://www.citrix.com/about/trust-center/) | (Unknown)
ZScaler | [Step-by-Step Configuration Guide for ZIA](https://help.zscaler.com/zia/step-step-configuration-guide-zia) | [Zscaler Trust Security Advisories](https://trust.zscaler.com/security-advisories) | [RSS](https://trust.zscaler.com/blog-feed)


## Contributing

Items marked _**(Unknown)**_ need further research! You can help contribute to this list and make it easier for administrators to find and securely configure remote working solutions.

If you'd like to make a suggestion, or correct something, then [raise an issue](https://github.com/cydea/remote-working-psirt/issues).

**Pull requests are also very welcome!** Though to aid review, please:

- Submit one PR per section you are updating
- Add new vendors in alphabetical order
- Keep the table format: VENDOR | CONFIGURATION | ADVISORY | NOTIFICATION
- Only link to vendor, or national technical authority (e.g. NCSC, NIST, etc) resources

## License

This resource is [freely available under the Creative Commons Zero License (CC.0)](https://github.com/rto/remote-working-psirt/blob/master/LICENSE), so please use, share, modify and improve it!
