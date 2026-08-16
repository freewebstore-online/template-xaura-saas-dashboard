# xaura-dashboard

A FreeWebStore template for **business.saas** by **@Aa11rn**.

# Xaura SaaS Dashboard

A polished, single-page SaaS dashboard template that extends the Xaura design
language from a corporate marketing site into a structured product interface.
Built with plain HTML + CSS + vanilla JS — no framework or backend required.

## Features

- Responsive dashboard layout (desktop / tablet / mobile)
- Fixed sidebar navigation with active states and a mobile drawer
- Topbar with global search, notifications dropdown, and profile menu
- KPI stat cards with delta badges and inline sparklines
- SVG analytics charts: revenue area chart (7D / 30D / 90D / 12M tabs) with
  hover tooltips, plus a traffic-source donut chart
- Customer data table with search, status filter pills, sortable columns,
  and pagination
- Activity feed timeline
- Realistic interaction states: loading skeletons, empty state, and error
  state with retry — previewable via the built-in "Demo states" switcher
- Night mode toggle (persisted preference)
- Toast notifications for user actions
- Fully slot-annotated (`data-fws-slot`) for FreeWebStore content editing

## Included Files

```
xaura-dashboard/
├── index.html            # Main template page
├── package.json          # Node dependency file (FWS CLI)
├── template.config.json  # FWS template metadata
├── tailwind.config.js    # Tailwind design tokens reference
├── preview.png           # Template preview image (add your own)
└── README.md             # This file
```

## Customization

All editable content regions are marked with `data-fws-slot` attributes. Edit
these directly in the HTML or via the FreeWebStore editor after publishing.
See `slots.md` for the slot reference used by this template.

## Publishing

```sh
npx @freewebstore/cli doctor     # local validation
npx @freewebstore/cli login      # one-time GitHub App install
npx @freewebstore/cli publish    # upload + create repo + queue for review
```

## License

MIT (auto-set by `fws init`). FreeWebStore requires MIT for community
templates — see CONTRIBUTING.md in the platform docs for the why.
MIT — see `template.config.json` for details.
