# Slot reference for category: business.saas

The FreeWebStore platform AI rewrites your template per small business by
filling `data-fws-slot` attributes. The slots below are the *conventional*
set for **business.saas** — using them gives the platform AI deterministic
anchors, so customization is predictable.

Templates *without* slot markers still work — the AI infers structure from
the HTML — but marked templates are more reliable and easier to QA.

## Universal slots (all categories)

| Slot | Element type | What goes there |
|------|--------------|-----------------|
| `business.name` | text | Legal or display name of the business |
| `business.tagline` | text | One-line pitch, shown in the hero |
| `about.body` | rich text | 2-4 sentence about-the-business paragraph |
| `contact.address` | text | Street address |
| `contact.phone` | text | Phone number, formatted |
| `contact.email` | text | Public email |
| `contact.hours` | text or list | Opening hours |
| `fws.byline` | reserved | DO NOT EDIT — the platform writes the designer credit here |

## Dashboard-specific slots used by this template

| Slot | Where |
|------|-------|
| `dashboard.greeting` | Topbar page heading |
| `dashboard.range` | Date-range selector label |
| `stat.1.value` … `stat.4.value` | KPI card values |
| `stat.1.label` … `stat.4.label` | KPI card labels |
| `stat.1.delta` … `stat.4.delta` | KPI delta badges |
| `analytics.title` | Revenue chart panel title |
| `analytics.subtitle` | Revenue chart panel subtitle |
| `customers.title` | Data table panel title |
| `activity.title` | Activity feed panel title |
| `activity.1.text` … `activity.5.text` | Activity feed items |

See the per-category SLOT-SCHEMAS reference in the platform docs for the
full list.
