# Cloudflare R2

Cloudflare R2 is S3-compatible object storage with zero egress fees. It provides both an S3-compatible REST API and a Cloudflare API for managing buckets, objects, and storage policies at global scale. R2 eliminates the costly egress bandwidth fees typical of other cloud storage providers while maintaining compatibility with existing S3 tooling and SDKs.

## APIs

- **S3-Compatible API** — Full S3-compatible object storage API at `https://<ACCOUNT_ID>.r2.cloudflarestorage.com`
- **Cloudflare API** — Account management API for R2 resources at `https://api.cloudflare.com/client/v4`

## Resources

- [Website](https://www.cloudflare.com/developer-platform/products/r2/)
- [Documentation](https://developers.cloudflare.com/r2/)
- [S3 API Reference](https://developers.cloudflare.com/r2/api/s3/api/)
- [Pricing](https://developers.cloudflare.com/r2/pricing/)
- [Platform Limits](https://developers.cloudflare.com/r2/platform/limits/)
- [Status Page](https://www.cloudflarestatus.com/)
- [Blog](https://blog.cloudflare.com/tag/cloudflare-r2/)
- [GitHub](https://github.com/cloudflare)
- [OpenAPI Schema](https://github.com/cloudflare/api-schemas)
- [LinkedIn](https://www.linkedin.com/company/cloudflare)
- [X / Twitter](https://x.com/cloudflare)

## Artifacts

| Artifact | Path |
|----------|------|
| APIs.json | [apis.yml](apis.yml) |
| Plans & Pricing | [plans/cloudflare-r2-plans-pricing.yml](plans/cloudflare-r2-plans-pricing.yml) |
| Rate Limits | [rate-limits/cloudflare-r2-rate-limits.yml](rate-limits/cloudflare-r2-rate-limits.yml) |
| FinOps | [finops/cloudflare-r2-finops.yml](finops/cloudflare-r2-finops.yml) |

## Maintainer

Kin Lane — kin@apievangelist.com
