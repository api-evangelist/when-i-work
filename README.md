# When I Work (when-i-work)

When I Work is an employee scheduling and workforce management platform serving over 200,000 workplaces in industries including restaurants, retail, healthcare, construction, and hospitality. The platform provides a REST API for managing shifts, schedules, users, time clock records, attendance, and team communication. API access is available exclusively on the Premium plan and uses token-based authentication with a private developer key. When I Work also supports webhooks for real-time event-driven integrations.

**APIs.json:** https://raw.githubusercontent.com/api-evangelist/when-i-work/refs/heads/main/apis.yml

**Naftiko:** https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=when-i-work-api-evangelist&utm_content=repo

## Tags

- Employee Scheduling
- Workforce Management
- Time Tracking
- Time Clock
- Shift Management
- Attendance
- Team Messaging
- Hourly Workers
- Labor Forecasting
- HR

## APIs

### When I Work API

REST API for managing employee scheduling, shifts, time clock records, attendance, users, locations, positions, tasks, and team communication within the When I Work platform.

- **Documentation:** https://apidocs.wheniwork.com/external/index.html
- **Base URL:** https://api.wheniwork.com/2
- **Authentication:** Token-based (developer key + credentials exchanged for bearer token)

**Resources:** Shifts, Schedules (Locations), Users, Positions, Sites, Tasks, Tags, Time Clock, Forecasting

## Plans / Rate Limits / FinOps

| File | Description |
|------|-------------|
| [plans/when-i-work-plans-pricing.yml](plans/when-i-work-plans-pricing.yml) | Essentials ($2.50), Pro ($5.00), Premium ($8.00) per user/month — API access on Premium only |
| [rate-limits/when-i-work-rate-limits.yml](rate-limits/when-i-work-rate-limits.yml) | No published numeric limits; tokens expire after 7 days; webhooks recommended over polling |
| [finops/when-i-work-finops.yml](finops/when-i-work-finops.yml) | FOCUS-aligned cost model: per-seat billing, primary cost driver is active user count |

## Timestamps

- **Created:** 2026-06-12
- **Modified:** 2026-06-12

## Common Properties

| Type | URL |
|------|-----|
| Website | https://wheniwork.com |
| Documentation | https://apidocs.wheniwork.com/external/index.html |
| GitHub Organization | https://github.com/wheniwork |
| LinkedIn | https://www.linkedin.com/company/wheniwork |
| Blog | https://wheniwork.com/blog |
| Pricing | https://wheniwork.com/pricing |
| Status Page | https://status.wheniwork.com |
| X / Twitter | https://x.com/wheniwork |

## Maintainers

**Kin Lane** — kin@apievangelist.com
