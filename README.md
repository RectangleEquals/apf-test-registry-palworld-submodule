# APF Test Registry — Palworld (Submodule Chain)

A test registry used to verify submodule traversal in APF Manager.

This repo itself contains no mods. It links to `apf-test-registry-palworld-minimal` as a Git submodule.
APF Manager should follow the submodule and discover the mods from that repo.

## Setup (do this after pushing `apf-test-registry-palworld-minimal` to GitHub)

```bash
git submodule add https://github.com/YOUR_USERNAME/apf-test-registry-palworld-minimal
git add .gitmodules apf-test-registry-palworld-minimal
git commit -m "Add submodule: apf-test-registry-palworld-minimal"
git push
```

## Expected Behaviour

When added as a registry in APF Manager, the mods from `apf-test-registry-palworld-minimal`
should appear in the Mods tab as if they were part of this repo.

## GitHub Topics

This repo is tagged: `apf-ue4ss-registry`, `apf-ue4ss-registry-palworld`
