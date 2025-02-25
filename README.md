Project Support
===

If you or your company enjoy using this project, please consider supporting my work and joining my discord. 💖

[![Become a GitHub Sponsor](https://img.shields.io/badge/Sponsor-171515.svg?logo=github&logoColor=white&style=for-the-badge "Become a GitHub Sponsor")](https://github.com/sponsors/manifestinteractive)
[![Become a Patreon Sponsor](https://img.shields.io/badge/Sponsor-FF424D.svg?logo=patreon&logoColor=white&style=for-the-badge "Become a Patreon Sponsor")](https://patreon.com/peter_schmalfeldt)
[![Donate via PayPal](https://img.shields.io/badge/Donate-169BD7.svg?logo=paypal&logoColor=white&style=for-the-badge "Donate via PayPal")](https://www.paypal.me/manifestinteractive)
[![Join Discord Community](https://img.shields.io/badge/Community-5865F2.svg?logo=discord&logoColor=white&style=for-the-badge "Join Discord Community")](https://discord.gg/JVKYHCKvrs)

------

![Logo](https://sfccdevops.s3.amazonaws.com/logo-128.png "Logo")

SFCC Developers Core - SFCC Cartridge
===

> A Salesforce Commerce Cloud (Demandware) Cartridge for Developers.

## Cartridges

- [X] **[Dev Tools](./cartridges/sfcc_dev_tools/)** - Developer Tools for Debugging your Storefront

> **:warning: NOTICE:** The author of the **Dev Console** has requested their cartridge be relocated to their personal GitHub account for future development. You can locate this cartridge at its **[New Home](https://github.com/z1haze/sfcc_dev_console)**.

Installation
---

[![Download](https://img.shields.io/badge/Download-blue.svg?logo=github&style=for-the-badge)](https://github.com/sfccdevops/sfcc_developers_core/releases/latest)

1. Unzip and Rename the folder to `sfcc_developers_core`
2. Move `sfcc_developers_core` into the root of your SFCC Project
3. Add `sfcc_developers_core` to project or global `.gitignore`
4. Add `sfcc_dev_tools` to Business Manager Storefront `Cartridges` Path
5. Review Usage Instructions in each Cartridges README.md

Contributing
---

> Interested in making this tool better?  Fork this Repository and we'll gladly accept Pull Requests.

#### Developer Setup:

```bash
git clone https://github.com/sfccdevops/sfcc_developers_core.git
cd sfcc_developers_core
npm install
npm run dev # one time build for development
npm run watch # watch for changes and build for development
npm run build # one time build for production
```

Once you have something you would like to share, check out our Contribution Guide.

[![Contribution Guide](https://img.shields.io/badge/Contribution_Guide-EEEEEE.svg?logo=github&logoColor=black&style=for-the-badge)](https://github.com/sfccdevops/sfcc_developers_core/blob/develop/.github/CONTRIBUTING.md)

About the Author
---

> [Peter Schmalfeldt](https://peterschmalfeldt.com/) is a Certified Senior Salesforce Commerce Cloud Developer with over 20 years of experience building eCommerce websites, providing everything you need to design, develop & deploy eCommerce applications for Web, Mobile & Desktop platforms.

Disclaimer
---

> The trademarks and product names of Salesforce®, including the mark Salesforce®, are the property of Salesforce.com. SFCC DevOps is not affiliated with Salesforce.com, nor does Salesforce.com sponsor or endorse the SFCC DevOps products or website. The use of the Salesforce® trademark on this project does not indicate an endorsement, recommendation, or business relationship between Salesforce.com and SFCC DevOps.
