# crrem-skills

CRREM v2.05 decarbonization pathway analysis for Claude Code / opencode.

## Install

### Claude Code
```bash
claude plugin marketplace add soapboxbuild/crrem-skills
claude plugin install crrem-skills
```

### opencode
```json
{
  "plugins": ["soapboxbuild/crrem-skills"]
}
```

## Skills

| Skill | Description |
|-------|-------------|
| `crrem` | CRREM stranding risk, carbon pathway compliance, ESG benchmarking |

## Data Source

Pathway data from [soapboxbuild/crrem-data](https://github.com/soapboxbuild/crrem-data) — CRREM v2.05, accessed via GitHub raw URLs. No MCP server required.

## License

Apache 2.0
