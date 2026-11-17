# IPSupport Scoop bucket

[Scoop](https://scoop.sh) manifests for IPSupport's Windows apps.

```
scoop bucket add ipsupport https://github.com/ipsupport-llc/scoop-bucket
scoop install ipsupport/llmtray
scoop update llmtray        # quit LLMTray first
scoop install ipsupport/ipsupport-code
```

| App | |
|---|---|
| `llmtray` | [LLMTray for Windows](https://github.com/ipsupport-llc/llmtray-windows): local AI runtime, the portable build. Follows the newest release, betas included. |
| `ipsupport-code` | [ipsupport-code](https://github.com/ipsupport-llc/ipsupport-code): local coding agent, also as `ipco`. Stable releases only. |

The manifests are updated by each app's release workflow; don't edit them by hand.
