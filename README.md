<p align="center">
  <a href="https://github.com/Mindbaz/awesome-opensource-email/">
    <img src="https://github.com/Mindbaz/awesome-email/blob/main/assets/icone.png" alt="Awesome Opensource Email">
  </a>
</p>

# awesome-opensource-email with stars

Awesome Opensource Email Resources

A curated list of resources on Email tools, server, framework, technology...

## Sponsors

<p align="center">
  <a href="https://www.sweego.io/" target="_blank">
    <img src="https://www.sweego.io/wp-content/uploads/2023/12/logo_sweego.svg" alt="Sweego Logo" width="300">
  <br>Sweego is a multichannel notification platform for developers
  </a>
</p>
<br>
<p align="center">
  <a href="https://www.sweego.io/" target="_blank">
    <img src="https://www.mindbaz.com/wp-content/uploads/2024/02/mindbaz-bleu.png" alt="Mindbaz Logo" width="300">
  <br>Mindbaz is an email marketing service provider
  </a>
</p>

## Table of Contents

* [Sending](#sending)
  * [SMTP Server](#smtp-server)
  * [Email Testing Application](#email-testing-application)
  * [IMAP/POP Server](#imappop-server)
  * [JMAP Server & others](#jmap-server--others)
  * [Complete Email Server](#complete-email-server)
  * [SPAM Filtering](#spam-filtering)
  * [Inbox API](#inbox-api)
  * [Forwarding](#forwarding)
  * [SMTP Testing](#smtp-testing)
  * [Inbound](#inbound)
* [Deliverability](#deliverability)
  * [Email Verification](#email-verification)
  * [Reputation](#reputation)
* [Email Platform](#email-platform)
  * [Marketing Platform](#marketing-platform)
  * [Newsletter Platform](#newsletter-platform)
  * [Email API](#email-api)
* [Code](#code)
  * [Framework](#framework)
  * [Templating](#templating)
  * [Library](#library)
  * [Other](#other)
* [Editing](#editing)
  * [Email Builder & Visual Editing Component](#email-builder--visual-editing-component)
* [Email Solution](#email-solution)
  * [Groupware / Webmail](#groupware--webmail)
  * [CLI](#cli)
* [Security](#security)
  * [Security Check](#security-check)
  * [DMARC](#dmarc)
  * [Privacy](#privacy)
* [Disposable emails domain list](#disposable-emails-domain-list)
* [Other](#other)

## Sending

### SMTP Server

* [Postal](https://github.com/postalserver/postal) ⭐ 16,727 | 🐛 90 | 🌐 Ruby | 📅 2026-08-05 - A fully featured open source mail delivery platform for incoming & outgoing e-mail
* [Maddy](https://github.com/foxcpp/maddy) ⭐ 6,063 | 🐛 140 | 🌐 Go | 📅 2026-07-24 -  Composable all-in-one mail server - `GPLv3`, `Go`
* [Cuttlefish](https://github.com/mlandauer/cuttlefish) ⭐ 1,623 | 🐛 150 | 🌐 Ruby | 📅 2024-06-27 - Transactional email server with a lovely web interface - `AGPLv3`, `Ruby`
* [James](https://github.com/apache/james-project) ⭐ 1,037 | 🐛 9 | 🌐 Java | 📅 2026-08-10 - James stands for Java Apache Mail Enterprise Server! - `Apache License Version 2.0`, `Java`
* [Chasquid](https://github.com/albertito/chasquid) ⭐ 977 | 🐛 9 | 🌐 Go | 📅 2026-06-07 - SMTP (email) server with a focus on simplicity, security, and ease of operation - `Ruby`
* [Zone-MTA](https://github.com/zone-eu/zone-mta) ⭐ 668 | 🐛 51 | 🌐 JavaScript | 📅 2026-07-20 - Modern outbound MTA cross platform and extendable server application - `Nodejs`
* [SMTPRelay](https://github.com/decke/smtprelay) ⭐ 630 | 🐛 6 | 🌐 Go | 📅 2026-08-10 -  Simple Golang SMTP relay/proxy server - `MIT`, `Go`
* [KumoMTA](https://github.com/KumoCorp/kumomta) ⭐ 514 | 🐛 83 | 🌐 Rust | 📅 2026-08-10 - The first Open-Source high-performance MTA developed from the ground-up for high-volume email sending environments. - `Rust`, `Lua`
* [MailWhale](https://github.com/muety/mailwhale) ⚠️ Archived - A bring-your-own-SMTP-server mail relay with REST API and web UI
* [DragonFly](https://github.com/corecode/dma) ⭐ 263 | 🐛 43 | 🌐 C | 📅 2026-05-29 - A small MTA for home and office use - `Linux`, `UNIX`, `BSD`, `C`
* [Postfix](http://www.postfix.org/) - The most famous email server - `IPL-1.0`, `C`
* [Haraka](https://haraka.github.io/) - A modern, high performance, flexible SMTP server - `Nodejs`
* [hMailServer](https://www.hmailserver.com/) - A user friendly IMAP, SMTP and POP3 server with admin GUI and spam protection. - `Windows`, `AGPLv3`, `C++`
* [EmailRelay](https://emailrelay.sourceforge.net/) - A small SMTP and POP3 server that is easy to configure - `Windows`, `Linux`, `OpenWrt`, `GPLv3`, `C++`

### Email Testing Application

* [Maildev](https://github.com/maildev/maildev) ⭐ 5,982 | 🐛 60 | 🌐 TypeScript | 📅 2026-08-12 -  mailbox SMTP Server + Web Interface for viewing and testing emails during development.
* [SMTP4dev](https://github.com/rnwood/smtp4dev) ⭐ 3,943 | 🐛 29 | 🌐 C# | 📅 2026-08-11 - the fake smtp email server for development and testing
* [Inbucket](https://github.com/inbucket/inbucket) ⭐ 2,245 | 🐛 37 | 🌐 Go | 📅 2026-04-02 - Disposable webmail server (similar to Mailinator) with built in SMTP, POP3, RESTful servers; no DB required.
* [Opentrashmail](https://github.com/HaschekSolutions/opentrashmail) ⭐ 920 | 🐛 15 | 🌐 PHP | 📅 2025-08-28 - Selfhosted trashmail solution - Receive Emails via Web UI, JSON API and RSS feed
* [Blackhole](https://github.com/kura/blackhole) ⭐ 61 | 🐛 3 | 🌐 Python | 📅 2022-10-28 -  Blackhole is an MTA written on top of asyncio, utilising async and await statements that dumps all mail it receives to /dev/null.
* [TestMSG](https://github.com/yaroslaff/testmsg) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2026-01-21 - Generate RFC-compliant e-mail messages for sending over SMTP. DKIM signed (optionally). - `MIT`, `Python`

### IMAP/POP Server

* [Dovecot](https://github.com/dovecot/core) ⭐ 1,235 | 🐛 14 | 🌐 C | 📅 2026-08-12 -  Dovecot mail server
* [James](https://github.com/apache/james-project) ⭐ 1,037 | 🐛 9 | 🌐 Java | 📅 2026-08-10 - James stands for Java Apache Mail Enterprise Server! - `Apache License Version 2.0`, `Java`
* [Cyrus](https://github.com/cyrusimap/cyrus-imapd) ⭐ 642 | 🐛 357 | 🌐 C | 📅 2026-08-12 - Cyrus IMAP is an email, contacts and calendar server
* [Wildduck](https://wildduck.email/) -  Modern mail server software for IMAP and POP3. Modern being scalable, Unicode-first, and API-controlled

### JMAP Server & others

* [JMAP](https://github.com/jmapio/jmap) ⭐ 1,363 | 🐛 13 | 🌐 Makefile | 📅 2026-07-17 -  JSON Meta Application Protocol Specification (JMAP) Specification
* [James](https://github.com/apache/james-project) ⭐ 1,037 | 🐛 9 | 🌐 Java | 📅 2026-08-10 - James stands for Java Apache Mail Enterprise Server! - `Apache License Version 2.0`, `Java`
* [Gomap](https://github.com/cwinters8/gomap) ⭐ 4 | 🐛 5 | 🌐 Go | 📅 2026-06-04 -  Go module for interfacing with JMAP servers

### Complete Email Server

* [Docker Mailserver](https://github.com/docker-mailserver/docker-mailserver) ⭐ 18,697 | 🐛 111 | 🌐 Shell | 📅 2026-08-03 -  Production-ready fullstack but simple mail server (SMTP, IMAP, LDAP, Antispam, Antivirus, etc.) running inside a container.  - `MIT`
* [Mailinabox](https://github.com/mail-in-a-box/mailinabox) ⭐ 15,387 | 🐛 612 | 🌐 Python | 📅 2026-05-24 - Mail-in-a-Box helps individuals take back control of their email by defining a one-click, easy-to-deploy SMTP+everything else server: a mail server in a box.
* [Stalwart](https://github.com/stalwartlabs/mail-server) ⭐ 14,126 | 🐛 73 | 🌐 Rust | 📅 2026-08-12 -  Secure & Modern All-in-One Mail Server (IMAP, JMAP, POP3, SMTP) - `GNU AGPLv3` & `Stalwart Enterprise License 1.0 (SELv1) Agreement`, `Rust`
* [Mailu](https://github.com/Mailu/Mailu) ⭐ 7,454 | 🐛 125 | 🌐 Python | 📅 2026-08-12 -  Insular email distribution - mail server as Docker images
* [Mox](https://github.com/mjl-/mox) ⭐ 5,780 | 🐛 200 | 🌐 Go | 📅 2026-08-10 -  modern full-featured open source secure mail server for low-maintenance self-hosted email - `MIT`, `Go`
* [Forward Email](https://github.com/forwardemail/forwardemail.net) ⭐ 1,659 | 🐛 62 | 🌐 JavaScript | 📅 2026-08-13 - All-in-one 100% open-source mail server alternative to Gmail/Mailchimp/Sendgrid (IMAP, POP3, SMTP, CalDAV) - `BUSL-1.1` & `MPL-2.0`, `JavaScript`
* [Zimbra Open Source Edition](https://github.com/Zimbra/zm-build) ⭐ 240 | 🐛 14 | 🌐 Perl | 📅 2026-08-06 - A full featured email service.
* [Excision-Mail](https://github.com/Excision-Mail/Excision-Mail) ⭐ 160 | 🐛 11 | 🌐 Jinja | 📅 2022-10-30 -  Fullstack, security focused, personal mail server based on OpenSMTPD for OpenBSD `ISC License`
* [Erooster Email Server](https://github.com/erooster-mail/erooster) ⭐ 62 | 🐛 30 | 🌐 Rust | 📅 2026-08-10 -  A mail suite written in rust meant to be easy to use.
* [iRedMail](https://iredmail.org/) - Open Source Mail Server Solution
* [Modoboa](https://modoboa.org/en/) - Modoboa brings together Open Source's finest in a single interface.

### SPAM Filtering

* [Rspamd](https://github.com/rspamd/rspamd) ⭐ 2,510 | 🐛 294 | 🌐 C | 📅 2026-08-10 - Advanced spam filtering system and email processing framework.
* [Spamscope](https://github.com/SpamScope/spamscope) ⭐ 311 | 🐛 1 | 🌐 Python | 📅 2025-08-06 -  Fast Advanced Spam Analysis Tool.
* [AgentJ](https://github.com/Probesys/agentj) ⭐ 33 | 🐛 66 | 🌐 PHP | 📅 2026-08-12 -  AgentJ is a free software anti-spam solution with human authentication and admin panel - `AGPL`, `PHP`
* [Guardian](https://github.com/Mailuminati/Guardian) ⭐ 17 | 🐛 6 | 🌐 Go | 📅 2026-03-12 -  Fast and privacy-preserving email threat detection with shared intelligence.
* [ASSP](https://sourceforge.net/p/assp/wiki/Main_Page/) - The Anti-Spam SMTP Proxy (ASSP).
* [Spamassassin](https://spamassassin.apache.org/) - Open Source anti-spam platform - `Apache License Version 2.0`, `Perl`, `C`
* [Proxmox Mail Gateway](https://www.proxmox.com/en/proxmox-mail-gateway/overview) - Full-featured, open-source mail proxy and protects your mail server from spam, viruses, trojans, and phishing emails - `GNU AGPLv3`

### Inbox API

### Forwarding

* [Anonaddy](https://github.com/anonaddy/anonaddy) ⭐ 4,797 | 🐛 62 | 🌐 PHP | 📅 2026-07-30 -  Anonymous email forwarding

### SMTP Testing

* [MailHog](https://github.com/mailhog/MailHog) ⭐ 16,117 | 🐛 255 | 🌐 Go | 📅 2024-02-13 - Web and API based SMTP testing  - `MIT`, `Go`
* [MailPit](https://github.com/axllent/mailpit) ⭐ 10,098 | 🐛 0 | 🌐 Go | 📅 2026-08-11 - An email and SMTP testing tool with API for developers  - `MIT`, `Go`
* [MailCrab](https://github.com/tweedegolf/mailcrab) ⭐ 989 | 🐛 2 | 🌐 Rust | 📅 2026-08-02 - Email test server for development, written in Rust - `Apache License`, `Rust`
* [Robin](https://github.com/mimecast/robin) ⭐ 18 | 🐛 6 | 🌐 Java | 📅 2025-10-10 -  Debug and development tool for MTA architects! Robin is a highly configurable SMTP client for testing and debugging SMTP servers. - `Java`, `Apache License 2.0`
* [MailCatcher](https://mailcatcher.me/) - Catches mail and serves it via a webui  - `MIT`, `Ruby`

### Inbound - Mail Parser

* [Mail-Parser](https://github.com/SpamScope/mail-parser) ⭐ 454 | 🐛 0 | 🌐 Python | 📅 2026-08-12 -  A tool that parses emails by enhancing the Python standard library, extracting all details into a comprehensive object. `Apache License 2.0`, `Python`
* [Libratom](https://github.com/libratom/libratom) ⭐ 127 | 🐛 7 | 🌐 Python | 📅 2026-01-31 -  Python library and supporting utilities to parse and process PST and mbox email sources  - `MIT`, `Python`
* [Inbound SMTP to Webhook](https://github.com/sendbetter/inbound-email) ⭐ 74 | 🐛 0 | 🌐 JavaScript | 📅 2025-10-09 - Receive email and sent parsed content/headers to webhook, attachments to S3.

## Deliverability

### Email Verification

* [EmailValidator](https://github.com/egulias/EmailValidator) ⭐ 11,636 | 🐛 37 | 🌐 PHP | 📅 2025-03-20 - PHP Email address validator
* [Mailchecker](https://github.com/FGRibreau/mailchecker) ⭐ 1,901 | 🐛 4 | 🌐 PHP | 📅 2026-08-04 - Cross-language email validation. Backed by a database of over 55 000 throwable email domains.
* [Email-Verifier](https://github.com/AfterShip/email-verifier) ⭐ 1,594 | 🐛 34 | 🌐 Go | 📅 2026-02-26 - A Go library for email verification without sending any emails.  - `MIT`, `Go`
* [python-email-validator](https://github.com/JoshData/python-email-validator) ⭐ 1,431 | 🐛 16 | 🌐 Python | 📅 2026-06-26 -  A robust email syntax and deliverability validation library for Python.  `The Unlicense`, `Python`
* [Truemail](https://github.com/truemail-rb/truemail) ⭐ 1,271 | 🐛 2 | 🌐 Ruby | 📅 2024-04-23 - Configurable framework agnostic plain Ruby email validator/verifier. Verify email via Regex, DNS, SMTP and even more. Be sure that email address valid and exists.  - `MIT`, `Ruby`
* [email-validator-js](https://github.com/devmehq/email-validator-js) ⚠️ Archived -  Verify email address checking MX records, and SMTP connection, check for disposable email addresses and free email providers. - `MIT`, `Typescript`
* [validate-email](https://github.com/centminmod/validate-emails) ⭐ 96 | 🐛 3 | 📅 2026-06-24 -  Self-hosted email verification script to clean up bad invalid email address lists. Supports various commercial email verification provider APIs all in one script - `PHP`
* [CustomerOS MailSherpa](https://github.com/customeros/mailsherpa) ⭐ 25 | 🐛 1 | 🌐 Go | 📅 2025-03-10 - A CLI for verifying email address deliverability over SMTP without sending an email. - `AGPL-3.0`, `Go`
* [Selfsend - email-sanitizer-api](https://github.com/SelfSend/email-sanitizer-api) ⭐ 5 | 🐛 35 | 🌐 Rust | 📅 2025-08-19 - A high-performance and secure REST/GraphQL API built with Rust, MongoDB & Redis for cleaning email subscriber lists. Maintains sender reputation by validating, deduplicating, and pruning inactive emails.  - `MIT`, `Rust`
* [Reacher](https://github.com/reacherhq) - Check if an email exists without sending any email. - `Dual Licence Commercial/AGPL`, `Rust`

### Reputation

* [Google Postmaster Datas](https://github.com/Mindbaz/python-gpostmaster-domains-datas) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2026-08-06 - Downloads and flattends datas from Google Postmaster Tools (GPT)
* [Python Hetrixtools Blacklist](https://github.com/Mindbaz/python-hetrixtools-blacklist) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2023-03-06 - Tool to retrieve @hetrixtools data from their API and store them in flat file or in a database

## Email Platform

### Marketing Platform

* [Mautic](https://github.com/mautic/mautic) ⭐ 10,322 | 🐛 187 | 🌐 PHP | 📅 2026-08-12 - Open Source Marketing Automation Software
* [Plunk](https://github.com/useplunk/plunk) ⭐ 5,363 | 🐛 40 | 🌐 TypeScript | 📅 2026-08-10 - Open-Source Email Platform - `GNU Affero General Public License v3.0`, `typescript`
* [Sendportal](https://github.com/mettle/sendportal) ⭐ 2,154 | 🐛 52 | 🌐 PHP | 📅 2024-04-19 - Open-source self-hosted email marketing. Manage your own newsletters at a fraction of the cost.

### Newsletter Platform

* [Listmonk](https://github.com/knadh/listmonk) ⭐ 22,766 | 🐛 113 | 🌐 Go | 📅 2026-08-12 - High performance, self-hosted, newsletter and mailing list manager with a modern dashboard. Single binary app.
* [Mailtrain](https://github.com/Mailtrain-org/mailtrain) ⭐ 5,744 | 🐛 115 | 🌐 JavaScript | 📅 2025-10-05 -  Self hosted newsletter app
* [Keila](https://github.com/pentacent/keila) ⭐ 2,183 | 🐛 76 | 🌐 Elixir | 📅 2026-08-01 - Keila is an Open Source alternative to newsletter tools like Mailchimp or Sendinblue.
* [Notifuse](https://github.com/Notifuse/notifuse) ⭐ 2,044 | 🐛 6 | 🌐 Go | 📅 2026-08-12 - Notifuse is an open-source & modern emailing platform - `GNU Affero General Public License v3.0`, `go`, `typescript`
* [phplist3](https://github.com/phpList/phplist3) ⭐ 865 | 🐛 87 | 🌐 PHP | 📅 2026-08-12 - Fully functional Open Source email marketing manager for creating, sending, integrating, and analysing email campaigns and newsletters.
* [RSS2Newsletter](https://github.com/ElliotKillick/rss2newsletter) ⭐ 278 | 🐛 6 | 🌐 Python | 📅 2024-08-17 - Convert RSS/Atom feed to email newsletters - `GNU Affero General Public License v3.0`, `Python`
* [MailCarrier](https://github.com/mailcarrierapp/mailcarrier) ⭐ 165 | 🐛 2 | 🌐 PHP | 📅 2026-07-16 - Mailing platform with templates and logs included. - `MIT`, `php`, `Laravel`

### Email API

* [Hyvor](https://github.com/hyvor/) - `GNU AGPLv3`, `php`, `symfony`, `go`, `SvelteKit`, `Postgresql`

## Code

### Framework

* [MJML](https://github.com/mjmlio/mjml) ⭐ 18,197 | 🐛 67 | 🌐 JavaScript | 📅 2026-08-12 - Framework to make responsive-email easy
* [Maizzle](https://github.com/maizzle/framework) ⭐ 1,598 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-10 -  HTML email development framework

### Templating

* [Foundation for Emails 2](https://github.com/foundation/foundation-emails) ⭐ 7,792 | 🐛 3 | 🌐 HTML | 📅 2026-03-13 -  Quickly create responsive HTML emails that work on any device and client. Even Outlook. - `MIT`, `HTML`
* [Cerberus](https://github.com/TedGoas/Cerberus) ⭐ 5,130 | 🐛 13 | 🌐 HTML | 📅 2024-07-16 -  A few simple, but solid patterns for responsive HTML email templates and newsletters. Even in Outlook and Gmail.
* [Hermes](https://github.com/matcornic/hermes) ⭐ 3,024 | 🐛 22 | 🌐 Go | 📅 2025-04-04 -  Golang package that generates clean, responsive HTML e-mails for sending transactional mail
* [Maud](https://github.com/lambda-fairy/maud) ⭐ 2,621 | 🐛 64 | 🌐 Rust | 📅 2026-05-25 - Compile-time HTML templates for Rust  - `MIT`, `Apache License`, `Rust`
* [Inky](https://github.com/foundation/inky) ⭐ 703 | 🐛 1 | 🌐 Rust | 📅 2026-07-14 - Convert a simple HTML syntax into tables compatible with Foundation for Emails.
* [HEML](https://heml.io/) -  HEML is an open source markup language for building responsive email.

### Library

* [PHPMailer](https://github.com/PHPMailer/PHPMailer) ⭐ 22,282 | 🐛 38 | 🌐 PHP | 📅 2026-08-06 -  The classic email sending library for PHP
* [MailKit](https://github.com/jstedfast/MailKit) ⭐ 6,838 | 🐛 11 | 🌐 C# | 📅 2026-06-12 -  A cross-platform .NET library for IMAP, POP3, and SMTP.
* [lettre](https://github.com/lettre/lettre) ⭐ 2,250 | 🐛 81 | 🌐 Rust | 📅 2026-08-03 - a mailer library for Rust - `MIT`, `Rust`
* [go-smtp](https://github.com/emersion/go-smtp) ⭐ 2,039 | 🐛 32 | 🌐 Go | 📅 2026-08-09 - An SMTP client & server library written in Go - `MIT`, `Go`
* [MimeKit](https://github.com/jstedfast/MimeKit) ⭐ 1,998 | 🐛 15 | 🌐 C# | 📅 2026-08-03 -  A .NET MIME creation and parser library with support for S/MIME, PGP, DKIM, TNEF and Unix mbox spools.
* [Anymail](https://github.com/anymail/django-anymail/) ⭐ 1,895 | 🐛 16 | 🌐 Python | 📅 2026-07-30 - Django email backends and webhooks for multiple ESP - `BSD 3-Clause`, `Python`
* [Swoosh](https://github.com/swoosh/swoosh) ⭐ 1,522 | 🐛 17 | 🌐 Elixir | 📅 2026-08-07 -  Compose, deliver and test your emails easily in Elixir - `MIT`, `Elixir`
* [go-mail](https://github.com/wneessen/go-mail) ⭐ 1,465 | 🐛 12 | 🌐 Go | 📅 2026-07-22 - Easy to use, yet comprehensive library for sending mails with Go - `MIT`, `Go`
* [Nette Mail](https://github.com/nette/mail) ⭐ 494 | 🐛 0 | 🌐 PHP | 📅 2026-07-28 - Handy email creation and transfer library for PHP with both text and MIME-compliant support.
* [Stampie](https://github.com/Stampie/Stampie) ⚠️ Archived - Library for using online Email providers for PHP
* [Play-Mailer](https://github.com/playframework/play-mailer) ⭐ 252 | 🐛 22 | 🌐 Scala | 📅 2026-08-08 - Play mailer plugin for Scala
* [mailparse](https://github.com/staktrace/mailparse) ⭐ 226 | 🐛 2 | 🌐 Rust | 📅 2026-07-27 - Rust library to parse mail files - `BSD Zero Clause`, `Rust`
* [go-msgauth](https://github.com/emersion/go-msgauth) ⭐ 225 | 🐛 23 | 🌐 Go | 📅 2025-04-20 -  🔏 A Go library and tools for DKIM, DMARC and Authentication-Results  - `MIT`, `Go`
* [ballerina-email](https://github.com/ballerina-platform/module-ballerina-email) ⭐ 115 | 🐛 4 | 🌐 Java | 📅 2026-07-19 - Easy to use, yet comprehensive library for sending mails with Ballerina - `Apache 2.0`, `Ballerina`
* [Sisimai](https://libsisimai.org/) - Mail Analyzing Interface: A library to parse RFC5322 bounce emails and generating structured data as JSON from parsed results. For Perl, Go & Ruby
* [Nodemailer](https://nodemailer.com/) - A Node.js library

### Other

* [Vue-Email](https://github.com/vue-email/vue-email) ⭐ 1,085 | 🐛 26 | 🌐 TypeScript | 📅 2026-04-10 - Write email templates with vue  - `MIT`, `Typescript`
* [Premail](https://github.com/peterbe/premailer/) ⭐ 1,084 | 🐛 73 | 🌐 Python | 📅 2023-12-16 -  Turns CSS blocks into style attributes `BSD 3-Clause`, `Python`
* [Can I email](https://github.com/hteumeuleu/caniemail) ⭐ 935 | 🐛 96 | 🌐 HTML | 📅 2026-08-10 - Can I email… Support tables for HTML and CSS in emails.
* [Email CSS Resets](https://github.com/JayOram/email-css-resets/tree/main) ⭐ 106 | 🐛 3 | 🌐 CSS | 📅 2026-02-05 - List of email CSS normalise/resets.
* [HowToTarget.email](https://github.com/customerio/howtotarget) ⭐ 54 | 🐛 8 | 🌐 SCSS | 📅 2026-04-29 - How to target email clients for email development.
* [Emailens Engine](https://github.com/emailens/engine) ⭐ 9 | 🐛 0 | 🌐 TypeScript | 📅 2026-07-30 - Lint HTML emails against 250+ CSS properties across 15 email clients: compatibility scoring, dark mode simulation, accessibility and spam checks - `MIT`, `Typescript`

## Editing

### Email Builder & Visual Editing Component

* [GrapesJS](https://github.com/artf/grapesjs) ⭐ 26,121 | 🐛 34 | 🌐 TypeScript | 📅 2026-08-11 - Free and Open source Web Builder Framework. Next generation tool for building templates without coding
* [React Email Editor](https://github.com/unlayer/react-email-editor) ⭐ 5,197 | 🐛 240 | 🌐 TypeScript | 📅 2026-08-12 -  Drag-n-Drop Email Editor Component for React.js
* [maily.to](https://github.com/arikchakma/maily.to) ⭐ 3,884 | 🐛 5 | 🌐 TypeScript | 📅 2026-07-21 -  Craft beautiful emails effortlessly with Maily, the powerful email editor that ensures impeccable communication across all major clients. - `MIT`, `Typescript`
* [Easy Email](https://github.com/zalify/easy-email) ⭐ 2,826 | 🐛 30 | 🌐 TypeScript | 📅 2026-06-25 -  DnD Email Editor based on React.js and MJML.
* [Drag-and-Drop-Email-Designer](https://github.com/SendWithSES/Drag-and-Drop-Email-Designer) ⭐ 2,183 | 🐛 2 | 🌐 TypeScript | 📅 2026-06-08 - Drag and drop HTML email designer - `MIT`, `Typescript`
* [Mosaico](https://github.com/voidlabs/mosaico) ⭐ 1,780 | 🐛 22 | 🌐 HTML | 📅 2025-08-22 - Responsive Email Template Editor
* [email-builder-js](https://github.com/usewaypoint/email-builder-js) ⭐ 1,732 | 🐛 51 | 🌐 TypeScript | 📅 2026-02-09 -  A free and open-source block-based email template builder - `MIT`, `Typescript`
* [emailmd](https://github.com/unmta/emailmd) ⭐ 1,301 | 🐛 1 | 🌐 TypeScript | 📅 2026-07-26 -  Render markdown into email-safe HTML  - `MIT`, `Typescript`
* [Vue Email Editor](https://github.com/unlayer/vue-email-editor) ⭐ 665 | 🐛 70 | 🌐 Vue | 📅 2026-03-27 -  Drag-n-Drop Email Editor Component for Vue.js
* [MySigMail Card](https://github.com/mysigmail/card) ⭐ 415 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-07 - An open source html email template builder with drag & drop editor
* [LePatron](https://github.com/Badsender-com/LePatron.email) ⭐ 90 | 🐛 26 | 🌐 JavaScript | 📅 2026-08-09 -  LePatron is an opensource email builder allowing to industrialize your email template production. Build tailor made email templates and make them available to your non-technical users.
* [Paperbits emails](https://github.com/paperbits/paperbits-emails) ⭐ 71 | 🐛 2 | 🌐 TypeScript | 📅 2025-10-08 - Paperbits editors and generators for email templates.
* [mdx-to-email](https://github.com/getvero/mdx-to-email) ⭐ 6 | 🐛 2 | 🌐 JavaScript | 📅 2026-06-30 -  Convert MDX files to HTML emails, fast!  - `MIT`, `Javascript`
* [email-builder-wysiwyg](https://github.com/stefanraath3/email-builder-wysiwyg) ⭐ 5 | 🐛 1 | 🌐 TypeScript | 📅 2025-12-13 - A Resend Template-style WYSIWYG email editor with Notion-like editing that generates email-safe React Email templates.  - `Typescript`

## Email Solution

### Groupware / Webmail

* [Tutanota](https://github.com/tutao/tutanota) ⭐ 7,849 | 🐛 960 | 🌐 TypeScript | 📅 2026-08-12 - Tutanota is an email service with a strong focus on security and privacy that lets you encrypt emails, contacts and calendar entries on all your devices.
* [Roundcube](https://github.com/roundcube/roundcubemail) ⭐ 7,117 | 🐛 473 | 🌐 PHP | 📅 2026-08-12 -  The Roundcube Webmail suite - `GPLv3`, `PHP`
* [Cypht](https://github.com/cypht-org/cypht) ⭐ 1,677 | 🐛 137 | 🌐 PHP | 📅 2026-08-11 -  Cypht: Lightweight Open Source webmail written in PHP and JavaScript - `GNU Lesser General Public License v2.1`, `PHP`, `Javascript`
* [Egroupware](https://github.com/EGroupware/egroupware) ⭐ 295 | 🐛 20 | 🌐 PHP | 📅 2026-08-12 - Web based groupware server written in PHP - `GPLv2`, `PHP`
* [Bluemind](https://www.bluemind.net/en/) - Collaborative messaging solution
* [Mailcow](https://mailcow.email/) - The mailserver suite with the 'moo' – 🐮 + 🐋 = 💕

### CLI

* [Himalaya](https://github.com/soywod/himalaya) ⭐ 7,013 | 🐛 13 | 🌐 Rust | 📅 2026-08-11 - CLI to manager email - `MIT`, `Rust`

## Security

### Security Check

* [E-Mail Header Analyzer](https://github.com/cyberdefenders/email-header-analyzer) ⭐ 699 | 🐛 21 | 🌐 HTML | 📅 2023-04-11 - E-Mail Header Analyzer
* [Trustymail](https://github.com/cisagov/trustymail) ⭐ 224 | 🐛 22 | 🌐 Python | 📅 2026-08-05 -  Scan domains and return data based on trustworthy email best practices
* [Mailgoose](https://github.com/CERT-Polska/mailgoose) ⭐ 207 | 🐛 8 | 🌐 Python | 📅 2026-08-06 -  A web application that allows the users to check whether their SPF, DMARC and DKIM configuration is set up correctly. - `BSD 3-Clause "New" or "Revised" License`, `Python`
* [Domain Security Scanner](https://github.com/GlobalCyberAlliance/domain-security-scanner) ⭐ 177 | 🐛 1 | 🌐 Go | 📅 2026-07-15 -  Scan domains and receive advice based on their BIMI, DKIM, DMARC, and SPF records - `Apache License version 2.0`, `Go`
* [mxcheck](https://github.com/steffenfritz/mxcheck) ⭐ 145 | 🐛 0 | 🌐 Go | 📅 2026-07-17 -  mxcheck is an info and security scanner for e-mail servers. `GPL v-3`, `Go`
* [mailsec-check](https://github.com/foxcpp/mailsec-check) ⭐ 68 | 🐛 0 | 🌐 Go | 📅 2024-01-20 -  Another utility to analyze state of deployment of security-related email protocols.
* [Spamhaus-Intelligence-API-CLI](https://github.com/Mindbaz/Spamhaus-Intelligence-API-CLI) ⭐ 1 | 🐛 0 | 🌐 Python | 📅 2025-06-25 -  CLI to query Spamhaus Intelligence API `GPL v-3`, `Python`

### DMARC

* [parsedmarc](https://github.com/domainaware/parsedmarc) ⭐ 1,277 | 🐛 5 | 🌐 Python | 📅 2026-08-10 -  A Python package and CLI for parsing aggregate and forensic DMARC reports  - `Apache License version 2.0`, `Python`
* [checkdmarc](https://github.com/domainaware/checkdmarc) ⭐ 318 | 🐛 0 | 🌐 Python | 📅 2026-07-28 -  A parser for SPF and DMARC DNS records - `Apache License version 2.0`, `Python`
* [DmarcSrg](https://github.com/liuch/dmarc-srg) ⭐ 298 | 🐛 39 | 🌐 PHP | 📅 2026-07-16 -  A php parser, viewer and summary report generator for incoming DMARC reports.
* [dmarc-report-converter](https://github.com/tierpod/dmarc-report-converter) ⭐ 278 | 🐛 11 | 🌐 Go | 📅 2024-06-17 - Convert DMARC report files from xml to human-readable formats
* [Open DMARC Analyzer](https://github.com/userjack6880/Open-DMARC-Analyzer) ⭐ 272 | 🐛 14 | 🌐 PHP | 📅 2024-06-17 -  Open DMARC Analyzer is an Open Source DMARC Report Analyzer to be used with DMARC reports that have been parsed by John Levine's rrdmarc script or techsneeze's dmarcts-report-parser.
* [dmarcts-report-parser](https://github.com/techsneeze/dmarcts-report-parser) ⭐ 244 | 🐛 16 | 🌐 Perl | 📅 2023-08-19 -  A Perl based tool to parse DMARC reports from an IMAP mailbox or from the filesystem, and insert the information into a database. ( Formerly known as imap-dmarcts ) - `GNU GPL v3`, `Perl`
* [Viesti-Reports](https://github.com/antedebaas/Viesti-Reports) ⭐ 116 | 🐛 25 | 🌐 PHP | 📅 2025-11-12 - DMARC & SMTP-TLS Reports processor and visualizer and BIMI file hoster - `GPL v2`, `PHP`

### Privacy

* [SimpleLogin](https://github.com/simple-login/app) ⭐ 6,908 | 🐛 252 | 🌐 Python | 📅 2026-08-11 - Protect your online identity with email alias

### Disposable emails domain list

* [disposable-email-domains](https://github.com/disposable-email-domains/disposable-email-domains) ⭐ 5,422 | 🐛 45 | 🌐 Python | 📅 2026-08-13 - a list of disposable and temporary email address domains - `Public Domain`, `Python`
* [disposable](https://github.com/disposable/disposable) ⭐ 1,425 | 🐛 63 | 🌐 Python | 📅 2026-08-09 -  A list of disposable/temporary email address domains - `MIT`, `Python`
* [disposable-email-domain-list](https://github.com/groundcat/disposable-email-domain-list) ⭐ 107 | 🐛 0 | 🌐 Python | 📅 2026-08-10 -  A list of disposable email domains, cleaned and validated by scanning MX records. - `MIT`, `Python`
* [disposable-email-domains (another one)](https://github.com/amieiro/disposable-email-domains) ⭐ 90 | 🐛 0 | 🌐 PHP | 📅 2026-08-13 -  Disposable email domain lists, used in disposable email services, generated every quarter of an hour, in txt and JSON format. - `MIT`, `PHP`
* [email\_data](https://github.com/fnando/email_data) ⭐ 33 | 🐛 3 | 🌐 Ruby | 📅 2026-08-09 -  This project is a compilation of datasets related to emails. Includes disposable emails, disposable domains, and free email services.  - `MIT`, `Ruby`
* [disposable-email-domains (another one too)](https://github.com/kslr/disposable-email-domains) ⭐ 30 | 🐛 3 | 🌐 Shell | 📅 2026-08-13 -  Anti-cheating, temporary (disposable/throwaway) email list - `MIT`, `Javascript`
* [disposable-email-domains (Verifly)](https://github.com/james-sib/disposable-email-domains) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-08-12 -  Daily-refreshed master list of \~162,000 disposable/temporary email domains, plus role-account local-parts and verified dead-MX domains, in txt and JSON. - `MIT`, `Python`

## Other

* [Imapsync](https://github.com/imapsync/imapsync) ⭐ 4,123 | 🐛 191 | 🌐 Shell | 📅 2026-07-23 -  Imapsync is an IMAP transfers tool. The purpose of imapsync is to migrate IMAP accounts or to backup IMAP accounts. IMAP is one of the three current standard protocols to access mailboxes, the two others are POP3 and HTTP with webmails, webmails are often tied to an IMAP server. Upstream website is   - `No Public License`, `Shell`
* [Email-Expiration-Manager](https://github.com/Mindbaz/Email-Expiration-Manager) ⭐ 6 | 🐛 1 | 🌐 JavaScript | 📅 2026-04-07 - Thunderbird extension for managing emails with expiration dates  - `GPL v-3`, `Javascript`

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
