Strogoff

*****

A components based approach to mail templates.

*****

The idea was conceived because of [lit-html](https://github.com/Polymer/lit-html) but I found that it was not easy to use it without [jsdom](https://github.com/jsdom/jsdom) or a headless browser like [puppeteer](https://github.com/GoogleChrome/puppeteer). There are a few related projects out there, I used them as inspiration and I am using the existing templates as starting point, the list in the order in which I discover the projects is:
- [Hermes](https://github.com/wildbit/mailmason)
- [mailgen](https://github.com/eladnava/mailgen)
- [Postmark Transactional Email Templates](https://github.com/wildbit/postmark-templates)
- [MailMason](https://github.com/wildbit/mailmason)
- [EmailOctopus Templates](https://github.com/threeheartsdigital/emailoctopus-templates)
- [Email Templates](https://github.com/niftylettuce/email-templates)
- [Email Blueprints](https://github.com/mailchimp/email-blueprints)

After some thinking I came up with this approach, I hope the email design and populate process to be as declarative as possible and as easy as possible.

The main features are:
- ✔ Component based.
- ✔ Webpack based.
- ✔ Include some reflection.
- ⌛ Declarative  and functional.
- ⌛ It is for creating emails, not the sending them.
- ✔ TOML based configuration.
- ❌ Helper functions like sets and collections.
- ❌ I18n.
- ⌛ It is exported to a plain self-contained and ready to send HTML file.
- ⌛ In-memory development server with watch.
- ⌛ Separation of concern in a multi-stage template process, first layout then data, with delayed execution for data.
- ❌ Template families (different related layouts) and varieties (same layouts with different data/purpose).

*****

This software is protected by an [MIT License](LICENSE).

From 🇲🇽 with ♥
