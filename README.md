# Sarab brand site

One-page English parent brand page for Sarab (night black + oasis green).

## Live

- GitHub Pages: https://koldoishere.github.io/sarab-site/
- Custom domain (after DNS): https://sarab.me · https://www.sarab.me

## Custom domain: sarab.me

Repo has a `CNAME` file set to `sarab.me`. In GitHub Pages settings the custom domain should match.

### DNS at the registrar (Namecheap / Student Pack)

**Apex `sarab.me`** — A records:

| Type | Host | Value |
|------|------|-------|
| A | `@` | `185.199.108.153` |
| A | `@` | `185.199.109.153` |
| A | `@` | `185.199.110.153` |
| A | `@` | `185.199.111.153` |

Optional IPv6 AAAA for apex:

| Type | Host | Value |
|------|------|-------|
| AAAA | `@` | `2606:50c0:8000::153` |
| AAAA | `@` | `2606:50c0:8001::153` |
| AAAA | `@` | `2606:50c0:8002::153` |
| AAAA | `@` | `2606:50c0:8003::153` |

**`www.sarab.me`** — CNAME:

| Type | Host | Value |
|------|------|-------|
| CNAME | `www` | `koldoishere.github.io` |

After DNS propagates, enable “Enforce HTTPS” in repo Settings → Pages.
