# Aquaculture Fisheries Operations Suite

Wave:
- Portfolio next-20 completion batch

Source candidates represented:
- `AIAquacultureFisheriesOperationsAssistant`
- `AIAquacultureFisheriesOperationsOperations`
- `AIAquacultureFisheriesOperationsAnalytics`
- `AIAquacultureFisheriesOperationsWorkflow`

This suite is a runnable merged app with one login, one dashboard, one feature-first sidebar, PostgreSQL-backed records/documents/notifications/audit, role behavior, and smoke coverage.

## Local Run

```bash
cd /Users/erolakarsu/projects/merged/aquaculture-fisheries-operations-suite
./start.sh
```

Local URL:
- `http://127.0.0.1:5670`

Seeded users:
- `admin@aquaculture-fisheries-operations.local / admin123`
- `manager@aquaculture-fisheries-operations.local / manager123`
- `analyst@aquaculture-fisheries-operations.local / analyst123`

## Validation

```bash
cd /Users/erolakarsu/projects/merged/aquaculture-fisheries-operations-suite/frontend
npm run typecheck
SMOKE_BASE_URL=http://127.0.0.1:5670 npm run smoke
```
