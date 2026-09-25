# Swagra Support

Welcome to the official support repository for **Swagra**.

Swagra is a Chrome extension for exploring, testing, comparing, and mocking OpenAPI and Swagger APIs directly in your browser.

- **Explore:** browse endpoints and schemas, and send live requests with "Try it out"
- **API Client:** collections, environments and variables, history, cookies, and automatic token refresh. Supports HTTP, GraphQL, WebSocket, Server-Sent Events, and Socket.IO
- **API Diff:** compare two specs to see what changed
- **Mock Studio:** generate mock data from schemas
- **Backup:** export your whole workspace to a file and import it again later

This repository is the central place for:

- Bug reports
- Feature requests
- Questions and support
- Documentation and FAQs
- Release announcements

---

## Reporting a Bug

Before creating an issue:

1. Make sure you are using the latest version of Swagra.
2. Search existing issues to avoid duplicates.
3. Include enough details so the problem can be reproduced.

### Please include

- Swagra version
- Chrome version
- Operating system
- Steps to reproduce
- Expected behavior
- Actual behavior
- Screenshots or screen recordings if applicable

---

## Requesting a Feature

Have an idea that would make Swagra better?

Create a new issue and include:

- A clear description of the feature
- Why it would be useful
- Example use cases
- Mockups or screenshots (optional)

---

## Frequently Asked Questions

### What API specifications are supported?

Swagra currently supports:

- OpenAPI 3.x
- Swagger 2.0

### Can I import local files?

Yes.

You can import:

- JSON files
- YAML files
- Remote URLs
- Pasted specification content

You can also bring in existing requests from Postman collections, cURL commands, or HAR files.

### Does Swagra collect my API data?

No.

Swagra runs entirely in your browser and has no backend. Your specs, collections, environments, and settings are stored only on your device. Network requests go only to addresses you choose, such as a spec URL you import or an API you send a request to.

Please refer to the [Privacy Policy](PRIVACY.MD) for more information.

### Why does Swagra need access to all sites?

Swagra is an API client, and the APIs you call can be on any host. Host access lets it send the requests you start to that API without being blocked by CORS. Swagra never injects scripts into web pages or reads your browsing data.

---

## Need Help?

If you're experiencing an issue or have questions:

1. Search existing issues.
2. Open a new issue if your problem hasn't been reported.
3. Include as much detail as possible.

We aim to make Swagra the fastest and most enjoyable way to work with OpenAPI and Swagger APIs directly from the browser.

Thank you for using Swagra ❤️

---

## Useful Links

- [Documentation](https://swagra.vercel.app/#/docs)
- [Privacy Policy](PRIVACY.MD)
- [Report an issue](https://github.com/shahid-shafi/swagra-issues/issues/new)
