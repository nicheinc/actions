# Actions (deprecated)

**This repo is deprecated and will be renamed to `nicheinc/actions-archived`
and archived.** All of its workflows have been ported to dedicated,
independently released repos:

| Old workflow (this repo) | Replacement |
| --- | --- |
| `bump-versions.yaml` | [`nicheinc/actions-bump-versions`](https://github.com/nicheinc/actions-bump-versions)`@v1` |
| `prod_cdn_sync.yaml` | [`nicheinc/actions-prod-cdn-sync`](https://github.com/nicheinc/actions-prod-cdn-sync)`@v1` |
| `push-helm-charts.yaml` | [`nicheinc/actions-push-helm-charts`](https://github.com/nicheinc/actions-push-helm-charts)`@v1` |
| `build-test-ship.yaml` (removed earlier) | [`nicheinc/actions-go-ci`](https://github.com/nicheinc/actions-go-ci) |

Update any `uses: nicheinc/actions/.github/workflows/*.yaml@ref` reference to
point at the matching repo above. Do not add new workflows here — create a
separate `nicheinc/actions-<purpose>` repo instead.

This repo contains [GitHub Actions](https://docs.github.com/en/actions)
workflows/actions shared across our organization. This repo is designed
only for internal use but must be public due to current limitations on [reusable
workflows](https://docs.github.com/en/actions/using-workflows/reusing-workflows#access-to-reusable-workflows).
