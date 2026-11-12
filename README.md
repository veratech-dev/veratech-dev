# Vijay Jonnakuti · VERA Technologies

**Forward deployed data engineer and data & AI platform architect, Newport Beach, CA**

[LinkedIn](https://www.linkedin.com/in/jvjmohan) · [www.veratech.dev](https://www.veratech.dev)

20 years of building data platforms inside the customer's business, 13 of them embedded with a global asset
manager's risk and analytics teams. VERA Technologies is my digital product and AI studio, where I design, build
and ship products end to end.

Most of the work here is in private repositories. The contribution graph on this profile is real activity; this
page says what it is.

## What I'm building

| Project | What it is | Stack | Commits |
| --- | --- | --- | --- |
| **social-ops** | A command-line tool that publishes one piece of media to 9 social platforms (Facebook, Instagram, Threads, TikTok, YouTube, LinkedIn, X, Pinterest, Bluesky) and collects the stats afterwards. Talks to each platform's REST API directly, with no vendor SDKs. | Python 3.13, Typer, Pydantic v2, httpx, ffmpeg | 168 |
| **[offersnear.me](https://www.offersnear.me)** | A location-aware deals platform with privacy-preserving geolocation and a pipeline that pulls from 15+ deal vendors. | TypeScript, Swift, Terraform, serverless AWS | 152 |
| **[veratech.dev](https://www.veratech.dev)** | The studio's website. | Astro | 39 |
| **[kudo.kids](https://www.kudo.kids)** | A cross-platform mobile and web app, live on the App Store, designed, built and shipped end to end on a serverless backend. | React Native / Expo, AWS Lambda, DynamoDB, CloudFront | |

More projects and case studies: [www.veratech.dev](https://www.veratech.dev)

## Commit activity

As of November 12, 2026:

| | |
| --- | --- |
| Commits across private repositories since August 2026 | 480+ |
| Private repositories with active work | 4 (three above, one client project) |
| social-ops | 168 commits, 840+ offline unit tests, about 28,500 lines of Python, CI on every push |
| offersnear.me | 152 commits, 28 pull requests |

## How I build

- **Fail closed.** Anything that cannot be verified does not ship. social-ops records a pending row before any call
  that can create a post, so a crash never produces a duplicate.
- **Configuration over code.** A new client, pipeline or platform should be a config file, not a project.
- **Tests gate everything, including AI-written code.**
- **Small running costs.** Serverless by default; nothing runs when nobody is using it.

## Work with me

Code walkthroughs of the private repositories are available on request. Reach me on
[LinkedIn](https://www.linkedin.com/in/jvjmohan) or through [www.veratech.dev](https://www.veratech.dev).
