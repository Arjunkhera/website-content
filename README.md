# website-content

Published posts from `arjunkhera.com`, as plain markdown.

Nothing here is written by hand. The publication service commits one
file at every publish, as `content/<slug>/v<n>.md`, with the version's
front matter at the top. A version file is never rewritten, for the
same reason the versions table refuses UPDATE: a published version is
permanent.

This repository exists so the engine and the content separate cleanly.
The instance holds a deploy key for this repository and no key for
`Arjunkhera/website`, so the public-facing machine can never write the
branch that holds the crew's agent files, the publisher skill, or
`.mcp.json`. See D-10 and AC-15 of
`docs/design-docs/publishing-interface.md` in that repository.

`master` refuses a force-push and refuses deletion, so an instance that
was taken cannot erase the history.

## If the host is gone

Every published post is here, in git, with its whole version history.
That is the point.
