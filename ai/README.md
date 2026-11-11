# Publication automation

This repository publishes a pinned HIA Documentation System reference artifact. Read the root README, `snapshot.json` and `.github/workflows/pages.yml` before updating a snapshot.

The source repository owns generation and archive validation. The workflow checks out the exact source commit and runs its regression tests and archive reader. Preserve package identities, locale roots, native artifacts and full-source digests when updating publication metadata.

中文说明见根README。内容构建、回归与归档验证由固定源提交提供，发布仓只维护公开说明、固定工件元数据与Pages工作流。
