# Heath Sanchez — Independent Software Assurance Researcher

Minimal, responsive, static portfolio, with independent primary-evidence links. No framework, third-party script, build chain, or tracking.

## Public evidence

The portfolio specialises in semantic integrity, formal verification and mathematical correctness across aerospace, AI and scientific computing.

GitHub author-search snapshot (26 November 2026): 58 external submissions across 30 repositories, including 26 merged PRs across 13 repositories. Own-account and Metalogic Labs repositories are excluded. The count includes checker submissions and updates, not just original defect discoveries. [Browse the search](https://github.com/pulls?q=is%3Apr+author%3Aheathsanchez+-user%3Aheathsanchez+-org%3Ametalogiclabs+-user%3Ametalogiclabs).

Selected merged work:
- [L4YAML #1](https://github.com/nasa-jpl/L4YAML/pull/1): serialization proofs and a bounded normative/runtime anchor-policy separator; full parser correspondence remains open.
- [ANISE #912](https://github.com/nyx-space/anise/pull/912): rotating-frame transformation composition.
- [Nyx #615](https://github.com/nyx-space/nyx/pull/615): trajectory frame identity.
- [ONNX #8791](https://github.com/onnx/onnx/pull/8791): Hardmax conversion semantics.
- [OpenC3 COSMOS #4433](https://github.com/OpenC3/cosmos/pull/4433): exact integer preservation in Python telemetry accessors.
- [OpenMDAO #3848](https://github.com/OpenMDAO/OpenMDAO/pull/3848): assembled Jacobian source-index mapping.
- [L4YAML #232](https://github.com/nasa-jpl/L4YAML/pull/232): malformed JUnit report rejection.
- [L4YAML #290](https://github.com/nasa-jpl/L4YAML/pull/290): embedded NUL identity across the C/Python interface.
- [Lean Kernel Arena #166](https://github.com/leanprover/lean-kernel-arena/pull/166): bounded recursor soundness repair in a sokonanoda-derived checker.
- [Nyx #613](https://github.com/nyx-space/nyx/pull/613), [Brahe #608](https://github.com/duncaneddy/brahe/pull/608), [ROS 2 #634](https://github.com/ros2/rmw_cyclonedds/pull/634) and [JSBSim #1543](https://github.com/JSBSim-Team/jsbsim/pull/1543): further scoped corrections.

Additional historical evidence:
- [SAIR Mathematics Distillation Stage 2](https://competition.sair.foundation/competitions/mathematics-distillation-challenge-equational-theories-stage2/overview): 196/200 (98%) on the official leaderboard for both Solo model configurations.
- [Lean Kernel Arena (September 2026 round)](https://arena.lean-lang.org/round/2026-09/checker/mathgraph/): dated benchmark results, not perpetual standings.
- [Ethereum Geth #35890](https://github.com/ethereum/go-ethereum/pull/35890): merged upstream.
- [Linux rvgen V2 maintainer reply](https://lists.openwall.net/linux-kernel/2026/10/16/793): accepted by maintainer; no merged claim.
- [Equational Theories #1461](https://github.com/teorth/equational_theories/pull/1461): merged upstream.

Reproducer discrepancies are not actual mission incidents. Scoped contributions do not imply institutional employment, endorsements or whole-system certification.

## Branding
- Local `tux.svg` reproduces Garrett LeSage's CC0 redraw of Larry Ewing's Tux mascot, from https://github.com/garrett/Tux (credit to Larry Ewing, Garrett LeSage, and IFo Hancroft). This is community Linux imagery, not Linux Foundation or kernel maintainer endorsement.
- Heath's supplied headshot in `heath-headshot.jpg` is reused as the small top-left logo and browser-tab icon. There is no large homepage portrait.
- SAIR organizers are named as stated by the official competition, without implying an endorsement.

## Publishing
The repository is named `heathsanchez.github.io`. To enable publication, visit **Settings → Pages → Build and deployment** and choose **Deploy from a branch**, `main`, `/ (root)`. Wait for the Pages deployment, then check https://heathsanchez.github.io.

## Editing text without writing code
1. Open https://github.com/heathsanchez/heathsanchez.github.io/edit/main/index.html (GitHub sign-in required).
2. Use Find to locate a sentence you recognize, then edit the visible wording between the HTML tags. Leave the tags (`<h1>`, `<p>`, `<span>`, and so on) in place.
3. Click **Commit changes** and save directly to `main`.
4. Refresh https://heathsanchez.github.io after GitHub Pages has deployed the new commit.

**Simplest alternative:** Tell ChatGPT the exact sentence to replace and the new wording; it can edit the linked repository.

GitHub organization/repository-owner avatars are hotlinked for visual source identity, not endorsements. The leaderboard screenshots are intentionally not embedded. The 2:59 video is the original, unmodified MP4 supplied by Heath, hosted locally as `mathgraph-demo.mp4` and played with native HTML5 controls. No video graphics or channel identifiers in the footage were edited or removed. The YouTube embedded player has been replaced to eliminate YouTube's channel badge.

The historical commercial results are attributed to Heath's published account and not represented as independently audited. No affiliation or institutional endorsement is implied by open-source contributions.


## Original video authenticity
The original uploaded file is 12,420,182 bytes, SHA-256 `8d9648f9d1e1cbf9008e93239edf9da9ca77f4ac6c0072908a5a1873f24a30d0`. The transfer was reconstructed by [this one-time verification workflow](.github/workflows/assemble-original-video.yml) from temporary base64 chunks; the workflow verified the exact SHA-256, committed the MP4, and removed the temporary chunks. No logo removal, crop, watermark alteration, or transcoding was performed.
