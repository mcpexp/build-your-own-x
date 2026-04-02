# Branching Policy: Adopting 'main' as Default Branch

## Overview

This document advocates for transitioning the default branch name from `master` to `main`. This change aligns with industry trends and promotes inclusive language in software development.

## Industry Trends

- **GitHub's Initiative**: In 2020, GitHub changed the default branch name for new repositories from `master` to `main`. This move was part of a broader effort to use inclusive terminology.
- **Git's Support**: Git itself has introduced configuration options to set the default initial branch name (via `init.defaultBranch`).
- **Adoption by Major Projects**: Many prominent open-source projects (e.g., Linux kernel, Kubernetes, React) have migrated to `main` or other neutral terms.
- **Community Standards**: Industry best practices now encourage using `main` to foster an inclusive environment and avoid non-inclusive historical connotations.

## Benefits

1. **Inclusivity**: Removes language that may be associated with slavery (`master`/`slave` terminology).
2. **Consistency**: Aligns with modern defaults across GitHub, GitLab, and other platforms.
3. **Reduced Confusion**: New contributors often expect `main` as the default branch.
4. **Future-proofing**: As tooling evolves, support for `master` may diminish.

## Migration Considerations

- **Tooling Updates**: CI/CD pipelines, deployment scripts, and local git configurations may need updates.
- **Documentation**: Update references in README, contribution guides, and internal docs.
- **Collaborator Communication**: Notify contributors to ensure a smooth transition.

## Recommendations

1. Rename the default branch from `master` to `main` using GitHub's branch rename feature.
2. Update any protected branch rules accordingly.
3. Provide a transition period where both branches exist with redirects.
4. Update automated systems that reference the branch name.

## References

- [GitHub's blog post on renaming](https://github.blog/changelog/2020-10-01-the-default-branch-for-newly-created-repositories-is-now-main/)
- [Git documentation on default branch](https://git-scm.com/docs/git-config#Documentation/git-config.txt-initdefaultBranch)
- [Software Freedom Conservancy's guidance](https://sfconservancy.org/news/2020/jun/23/gitbranchname/)

## Conclusion

Adopting `main` as the default branch name is a small but meaningful step toward a more inclusive and modern development workflow. We encourage this repository to consider making this change.