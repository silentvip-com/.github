# silentVIP

Corporate travel run by people you can name, for companies of about 100 to 1,000 employees: options with the full price and policy status, approvals, entity billing and reporting, and no supplier commissions.

[Website](https://www.silentvip.com) · [silentVIP for Good](https://silentvip.org) · [Apps](https://www.silentvip.com/apps) · [Portfolio project board](https://github.com/orgs/silentvip-com/projects/1) <!-- TODO(confirm): final title of the portfolio project -->

## What we build

| Product | What it is | Where |
|---|---|---|
| silentVIP | Managed corporate travel: the public website, client portal (policy, approvals, finance, reporting, traveler safety), app API, and the iPhone, iPad, Apple Watch, Android and Wear OS client apps | [www.silentvip.com](https://www.silentvip.com) · [Google Play](https://play.google.com/store/apps/details?id=com.silentvip.clientapp) · repo `silentvip-com` |
| silentVIP Advisor | The companion app for silentVIP's travel advisors: client accounts, request queue, quoting and itineraries, bookings, travel-day operations (iPhone, iPad, Mac, Apple Watch, Android) | [Google Play](https://play.google.com/store/apps/details?id=com.silentvip.advisorapp) · repo `silentvip-advisor` |
| Hamptons by silentVIP | A luxury guide to the East End of Long Island for iPhone, iPad, Apple Watch and Android, and a front door to silentVIP trip planning | repo `hamptons` |
| silentVIP for Good | silentVIP's social impact program: nonprofit, volunteer and education travel. Website and the charity travel app (iPhone, iPad, Android) | [silentvip.org](https://silentvip.org) · repos `silentvip-org`, `silentvip-for-good` |
| silentVIP Discover | The next public experience: an editorial site with interactive product demonstrations | repo `silentvip-discover` |
| Hotels MCP | Hotel rate and corporate code checker (Hyatt, Marriott, Hilton, IHG) as a remote MCP server | `https://mcp.silentvip.com` · repo `hotels` |

Most repositories are private.

## How we work

- **Issues use forms.** New issues start from an issue form — Bug, Feature, Task, Epic or Initiative — which sets the org issue type and the `needs-triage` label. Repositories may add their own forms on top of these defaults.
- **One hierarchy.** Initiative (a portfolio outcome over a quarter or more) > Epic (a shippable body of work) > Feature, Task or Bug, linked as sub-issues. Real blockers are recorded as issue dependencies.
- **Project boards.** Each product has a project named `silentVIP · <Product>` with Status (Backlog, Ready, In progress, In review, Done), Priority (P0–P3), Size (XS–XL) and two-week iterations. The portfolio board rolls them up.
- **Pull requests close issues.** Every PR links its issue with `Closes #n` and follows the [pull request template](https://github.com/silentvip-com/.github/blob/main/.github/pull_request_template.md). Merging to a default branch deploys, so PRs are reviewed before merge.
- **Labels are shared.** `needs-triage`, `needs-info`, `blocked`, `security`, `accessibility`, `performance`, `documentation`, `design`, `dependencies`, plus `platform:*` and repository-specific `area:*` labels.

## Contact

- General: [www.silentvip.com](https://www.silentvip.com) · support@silentvip.com
- Urgent help with a trip that's underway: [www.silentvip.com/travel-support](https://www.silentvip.com/travel-support)
- Security: see the [security policy](https://github.com/silentvip-com/.github/blob/main/SECURITY.md); please do not open public issues for vulnerabilities.

Proprietary — © silentVIP LLC. All rights reserved.
