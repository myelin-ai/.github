---
name: New release
about: Choose this template when you want to publish a new version
title: Release [VERSION]
labels: ''
assignees: ''

---

# Prepare the release
- [ ] Bump the version numbers
- [ ] Update dependency versions for neighbouring crates
- [ ] Update the `changelog.md` of updated crate
- [ ] Create a pull request

# Perform the release
- [ ] Merge the pull request
- [ ] Run `cargo publish`
- [ ] Create a Tag/Release (e.g. '0.1.2'):
       `hub release [VERSION]`
       Use the relevant part of the `changelog.md` as the release description.
