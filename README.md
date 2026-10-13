# Production GitOps Kubernetes Manifests

Environment-specific Kubernetes deployment definitions for automated GitOps promotion.

## Branching Strategy
- `staging`: Automated candidate builds and pre-production validation.
- `main`: Production-verified cluster manifests deployed via Cloud Build.
