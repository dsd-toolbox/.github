<img src="https://raw.githubusercontent.com/dsd-toolbox/dsd-toolbox/main/docs/assets/icon-256.png" alt="" width="96">

# DSD Toolbox

Open tools for Super Audio CD disc images and DSD audio: play SACD images without extracting
them, extract and convert them, convert DSD to PCM, and measure how accurately converters do it.

> scarletbook-rs contributors: please don't read the DSD Toolbox repositories ([why](https://github.com/dsd-toolbox/dsd-toolbox/blob/main/docs/clean-room.md#for-scarletbook-rs-contributors)).

## Projects

| Project | What it does |
|---|---|
| [sacdfs](https://github.com/dsd-toolbox/sacdfs) | Plays SACD images as DSF and WAV tracks in any player, without extracting them (Linux, NAS, Windows, macOS) |
| [pysacd](https://github.com/dsd-toolbox/pysacd) | Extracts and converts SACD images to DSF, DSDIFF, FLAC or WAV, from the command line or Python |
| [beets‑pysacd](https://github.com/dsd-toolbox/beets-pysacd) | Imports SACD images into a beets music library, with MusicBrainz matching |
| [dsd2pcm‑rs](https://github.com/dsd-toolbox/dsd2pcm-rs) | Rust and C library and CLI: DSD to PCM, and DSF, DFF and WAV files |
| [dsd‑measure](https://github.com/dsd-toolbox/dsd-measure) | Measures DSD and PCM converters the way audiophile reviewers do, and writes one readable report |
| [scarletbook‑rs](https://github.com/aclater/scarletbook-rs) | Rust and C library that reads SACD images and decodes DST |
| [sacd‑spec](https://github.com/aclater/sacd-spec) | Specification of the SACD disc format, with a test corpus |

Where to start, how the projects fit together, and every release:
[DSD Toolbox](https://github.com/dsd-toolbox/dsd-toolbox). Questions and ideas:
[Discussions](https://github.com/dsd-toolbox/dsd-toolbox/discussions).

## How we work

- **Measured, not claimed.** We check audio quality with
  [dsd-measure](https://github.com/dsd-toolbox/dsd-measure), our measurement toolkit; its
  methodology is open, and we encourage other projects to use it.
- **Tested before release.** Releases follow a written release test plan.
- **Security.** Report vulnerabilities privately through the Security tab of the repository
  concerned.

## Licence and citing

Code is under each project's own licence. Documentation and published measurement data are
[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): reuse them freely, with attribution.
Each repository has a citation file; use GitHub's "Cite this repository".
