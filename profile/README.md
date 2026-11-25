<img src="https://raw.githubusercontent.com/dsd-toolbox/dsd-toolbox/main/docs/assets/icon-256.png" alt="" width="96">

# DSD Toolbox

Open tools for Super Audio CD disc images and DSD audio: play SACD images without extracting
them, extract and convert them, convert DSD to PCM, upconvert to higher DSD rates, and measure how accurately converters do it.

## Projects

| Project | What it does |
|---|---|
| [sacdfs](https://github.com/dsd-toolbox/sacdfs) | Plays SACD images as DSF and WAV tracks in any player, without extracting them (Linux, NAS, Windows, macOS) |
| [pysacd](https://github.com/dsd-toolbox/pysacd) | Extracts and converts SACD images to DSF, DSDIFF, FLAC or WAV, from the command line or Python |
| [beets‑pysacd](https://github.com/dsd-toolbox/beets-pysacd) | Imports SACD images into a beets music library, with MusicBrainz matching |
| [dsd2pcm‑rs](https://github.com/dsd-toolbox/dsd2pcm-rs) | Rust and C library and CLI: DSD to PCM, and DSF, DFF and WAV files |
| [dsd‑measure](https://github.com/dsd-toolbox/dsd-measure) | Measures DSD and PCM converters the way audiophile reviewers do, and writes one readable report |
| [dsd‑upsample‑rs](https://github.com/dsd-toolbox/dsd-upsample-rs) | Converts DSF, DFF, WAV and FLAC files to DSD128 or DSD256, and PCM to DSD64 (Linux x86_64 library and command line; plug-ins and other systems follow) |

### The clean room

| Project | What it does |
|---|---|
| [sacd‑spec](https://github.com/aclater/sacd-spec) | Specification of the SACD disc format, written without reading other implementations' code, with a test corpus |
| [scarletbook‑rs](https://github.com/aclater/scarletbook-rs) | Rust and C library that reads SACD images and decodes DST, written from sacd-spec only |

These two are part of DSD Toolbox but live under the aclater account by design, kept apart, so that the permissively licensed library is
not derived from GPL code. If you contribute to them, please work from sacd-spec only and don't
read the other DSD Toolbox repositories
([how the clean room works](https://github.com/aclater/scarletbook-rs/blob/main/CLEANROOM.md)).

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
