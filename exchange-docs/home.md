# Insurance Claims API v2

Enterprise-grade insurance claims management API with:
- **3 Databases**: MySQL (Claims), PostgreSQL (Audit), SQL Server (Documents)
- **Azure File Share**: PDF document storage and retrieval
- **Email Notifications**: SMTP-based claim status alerts
- **HTTP Webhooks**: External notification service integration
- **Comprehensive Audit Trail**: Every action logged to PostgreSQL
- **Multi-environment**: dev / sit / uat / preprod / prod configs

## Connectors Used
- HTTP (Listener + Request)
- Database (MySQL, PostgreSQL, SQL Server)
- File (Azure File Share)
- Email (SMTP)
- Object Store (Caching)
- APIkit (RAML Router)
- Batch (Bulk operations)

## API Endpoints (20+)
- Policies: CRUD + pagination + soft-delete
- Claims: File, approve/reject, filter by status
- Documents: Upload/download PDFs from Azure File Share
- Dashboard: Multi-database aggregated statistics
- Reports: Monthly claims and policy reports
- Audit: Queryable audit trail
- Health: Checks all 3 databases + file share connectivity
