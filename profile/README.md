<p align="center">
  <img src="https://webdecoy.com/logo.png" alt="WebDecoy duck mascot" width="100">
</p>

<h1 align="center">See the bots. Choose the response.</h1>

<p align="center">
  Bot detection, protection and AI traffic visibility for websites, apps and stores.
</p>

<p align="center">
  <a href="https://apps.shopify.com/webdecoy-bot-protection?utm_source=github&utm_medium=org_profile&utm_campaign=platform_install_discovery&utm_content=shopify">Install on Shopify</a> &middot;
  <a href="https://wordpress.org/plugins/webdecoy/">Install on WordPress</a> &middot;
  <a href="https://docs.webdecoy.com/">Developer docs</a> &middot;
  <a href="https://webdecoy.com/?utm_source=github&utm_medium=org_profile&utm_campaign=platform_install_discovery">Website</a>
</p>

## Start with your platform

| Your site | What you can do | Start here |
|---|---|---|
| **Shopify** | Inspect bot signals and decoy interactions, review correlated order evidence, and investigate observed AI crawlers and referrals inside Shopify admin. | [Install the app](https://apps.shopify.com/webdecoy-bot-protection?utm_source=github&utm_medium=org_profile&utm_campaign=platform_install_discovery&utm_content=shopify_table) · [Watch the setup walkthrough](https://youtu.be/AI8HBwW6mRY) |
| **WordPress / WooCommerce** | Run local bot detection and protection in wp-admin. The standalone plugin needs no account or API key; cloud connection is optional. | [Install the free plugin](https://wordpress.org/plugins/webdecoy/) · [Watch a canary test](https://youtu.be/y6eErUY1Vsc) |
| **Node.js apps** | Add middleware with local tripwires, rate limits and IP rules. Connect platform checks when your application needs them. | [SDK and examples](https://github.com/WebDecoy/node) · [Express example](https://github.com/WebDecoy/node/tree/main/examples/express-basic) |
| **Sites behind an edge platform** | Collect request evidence where a browser tag cannot see it, then apply the response supported by your integration. | [Choose an integration](https://webdecoy.com/integrations/?utm_source=github&utm_medium=org_profile&utm_campaign=platform_install_discovery&utm_content=edge) |

### Shopify: install, enable, verify

1. Install [WebDecoy from the Shopify App Store](https://apps.shopify.com/webdecoy-bot-protection?utm_source=github&utm_medium=org_profile&utm_campaign=platform_install_discovery&utm_content=shopify_steps).
2. In the theme editor, enable **WebDecoy Bot Detection** under **App embeds** and save.
3. Open **Setup & health**, create a labeled test, visit its storefront link, and confirm delivery.

[Follow the full setup guide](https://docs.webdecoy.com/installation/shopify/) or [watch the walkthrough](https://youtu.be/AI8HBwW6mRY). If the store is password protected, unlock it in your own browser and reopen the test link. Check storefront and checkout-pixel delivery separately.

Order review needs a matching session and detection. Features vary by plan and settings; cancellation requires a Shopify Flow workflow you configure and enable.

## Open-source projects

| Project | Use it for |
|---|---|
| [FCaptcha](https://github.com/WebDecoy/FCaptcha) | Self-hosted CAPTCHA for detecting browser automation, including AI agents. Inspect the code, try the demo, and run your own verifier. |
| [Node SDK](https://github.com/WebDecoy/node) | Bot-detection middleware, runnable integration examples and application response controls. |
| [WordPress plugin](https://github.com/WebDecoy/wordpress-plugin) | Local WordPress and WooCommerce detection and protection, with an optional WebDecoy Cloud connection. |
| [GEOMCP](https://github.com/WebDecoy/geomcp) | GEO and SEO audits from an MCP client, with evidence for findings and before/after verification. |

FCaptcha and GEOMCP are separate tools. You can use them independently of WebDecoy Cloud.

## See the evidence

- [Shopify setup and order review](https://youtu.be/AI8HBwW6mRY): development-store walkthrough with labeled test activity and seeded example orders.
- [WordPress detection test](https://youtu.be/y6eErUY1Vsc): a controlled canary request and the resulting wp-admin detection log.
- [AI crawlers versus AI referrals](https://youtu.be/nFJYOJ2ABFU): distinguish observed crawling from identifiable visits sent by AI assistants.

These demonstrations show specific workflows, not production detection accuracy. Coverage depends on the sensor: a browser tag cannot observe every crawler that skips JavaScript, and missing referral information remains unattributed.

## Build with us

Explore the project READMEs for installation, examples, licenses and contribution guides. Reproducible issues, integration feedback and pull requests are welcome.
