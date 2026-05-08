# Grafana Dashboards

Collection of Grafana dashboards for monitoring different services and platforms.

## Available Dashboards

| Dashboard | Description | Tags |
|-----------|-------------|------|
| [Azure Function App](./azure-function-app/) | Failures & performance monitoring via Application Insights | `azure` `function-app` |

## Requirements

- Grafana 10+
- The required datasource plugin installed and configured for each dashboard

## How to import a dashboard

1. Open Grafana → Dashboards → Import
2. Upload the `dashboard.json` file from the desired folder
3. Follow the setup instructions in the folder's `README.md`

## Repository structure

Each folder contains a self-contained dashboard with:

```
<dashboard-name>/
├── dashboard.json   ← Grafana dashboard definition
└── README.md        ← Setup instructions and panel descriptions
```

## Contributing

1. Create a new folder with a descriptive name
2. Add the `dashboard.json` exported from Grafana
3. Add a `README.md` following the existing structure
4. Add a new entry to the table above
