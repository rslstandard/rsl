# Really Simple Syndication (RSL)

**Really Simple Licensing (RSL)** is an open, XML-based standard that enables publishers and platforms to define **machine-readable licensing and usage terms** for digital assets on the web. RSL builds on the ideas of the RSS syndication format and the Robots Exclusion Protocol to provide an interoperable way for websites, creators, crawlers, and agents to declare how their content must be accessed, processed, or compensated.

RSL defines:
- A core **XML vocabulary** for describing license and usage terms (`rsl` namespace).
- Integrations with existing discovery mechanisms such as `robots.txt`, RSS feeds, HTML `<link>` elements, and HTTP headers.
- Standard network protocols for **license acquisition and enforcement**, including:
  - **Open License Protocol (OLP)**: an OAuth 2.0 extension for acquiring and validating RSL licenses.
  - **Crawler Authorization Protocol (CAP)**: an HTTP authorization scheme for licensed crawlers.
  - **Encrypted Media Standard (EMS)**: a format for securely encrypting and licensing digital assets.

RSL enables content owners, platforms, crawlers, and agents to:
- Define machine-readable compensation and usage rules.  
- Automate license discovery, acquisition and payment.  
- Protect proprietary or paywalled content.  
- Promote transparency and compliance across the open web.

The specification is [maintained](https://rslstandard.org/about) by the **RSL Technical Steering Committee** and is currently in `draft`.

Learn more at [rslstandard.org](https://rslstandard.org).
