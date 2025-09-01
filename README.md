![badge-labs](https://user-images.githubusercontent.com/327285/230928932-7c75f8ed-e57b-41db-9fb7-a292a13a1e58.svg)

# InterchangeKit

InterchangeKit is building a memory-safe XML toolkit for use in native binary applications. The first interface exposed for applications will be the libxml2 interface as specified in ISO/IEC 23360-1 (the Linux Standard Base spec).

InterchangeKit does not currently ship any artefacts. Please see the roadmap items below and the open issues for where to get involved in building the first release.

## Roadmap

1. The first activity for the project is to collect collaborators. If you are interested in contributing to the project, feel it could be of use to you, or just want to watch how the project progresses, join our #interchange-kit channel on the FINOS Slack
1. To determine the scope for initial release, build a list of symbols used by open source projects which currently depend on libxml2. 
1. Analyze the collected data on symbol use to determine the minimal scope for a first release.

## Contributing

**All commits** must be signed with a DCO signature to avoid being flagged by the DCO Bot. This means that your commit log message must contain a line that looks like the following one, with your actual name and email address:

```
Signed-off-by: John Doe <john.doe@example.com>
```

Adding the `-s` flag to your `git commit` will add that line automatically. You can also add it manually as part of your commit log message or add it afterwards with `git commit --amend -s`.

See [CONTRIBUTING.md](./CONTRIBUTING.md) for more information

### Helpful DCO Resources
- [Git Tools - Signing Your Work](https://git-scm.com/book/en/v2/Git-Tools-Signing-Your-Work)
- [Signing commits
](https://docs.github.com/en/github/authenticating-to-github/signing-commits)

## License

Copyright 2025 Percona

Distributed under the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

SPDX-License-Identifier: [Apache-2.0](https://spdx.org/licenses/Apache-2.0)
