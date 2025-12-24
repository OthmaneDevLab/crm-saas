=========== Architecture Overview====

====>Backend
- Laravel (API only)
- RESTful APIs
- Sanctum Authentication

====> Database
- MySQL
- Single DB multi-tenant via company_id

====> Multi-Tenancy
- Each table contains company_id
- Global scopes for isolation

====> Versioning
- API versioned under /api/v1
