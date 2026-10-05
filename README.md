# Agent skills from Stays Up

Two read-only skills for your coding agent. Neither one sends anything on your
behalf, and neither changes a thing it looks at.

## staysup-enquiry

Something is quietly wrong and you want a second pair of eyes on it. The skill
asks you one question in your own words, reads the system to work out the
technical detail, and hands you the enquiry ready to go. You press send.

```bash
npx skills add B1aZer/skills -s staysup-enquiry
```

## silent-failure-check

Check a pipeline, or the infrastructure under it, for the failures that never
raise an error: dropped events, rows counted twice, numbers that drifted, tables
that stopped, records on the wrong id, backups nobody has restored, health checks
passing on a degraded service. Every finding comes with the query that found it.

```bash
npx skills add B1aZer/skills -s silent-failure-check
```

Both at once: `npx skills add B1aZer/skills`

Built by [Stays Up](https://staysup.io).
