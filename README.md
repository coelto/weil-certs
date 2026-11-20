# Rigorous lower bounds for the truncated Weil form up to support length ln 71 via a lattice minorant

Vadim Chekmachev · chekmachev@phystech.edu · ORCID [0009-0009-2982-0532](https://orcid.org/0009-0009-2982-0532)

DOI of all versions: [![10.5281/zenodo.23848596](https://zenodo.org/badge/DOI/10.5281/zenodo.23848596.svg)](https://doi.org/10.5281/zenodo.23848596)

## Abstract

The truncated quadratic Weil form Q<sub>c</sub> is considered on functions supported in [−L/2, L/2], L = ln c. It is proved that for all integers c = 2, …, 31 and for c = 45, 47 the inequality Q<sub>c</sub>(f) ≥ ε<sub>c</sub>‖f‖<sup>2</sup> holds for every complex f ∈ L<sup>2</sup>(−L/2, L/2) with an explicit constant ε<sub>c</sub> &gt; 0. For these c ≥ 3 the constant ε<sub>c</sub> is at least 3.4 d<sub>c</sub>, where d<sub>c</sub> = (2<sup>14</sup>/3)√2 π<sup>5</sup> c<sup>9/2</sup> e<sup>−4πc</sup> is the Fuchs scale, that is, the asymptotics of the defect of the prolate spheroidal function with index 4. Monotonicity of the form in c implies that it is nonnegative for all real c ≤ 47. For c = 71, Q<sub>c</sub> ⪰ ε<sub>71</sub> Id with ε<sub>71</sub> &gt; 0 is proved on even functions, whence Q<sub>c</sub> ⪰ 0 on them for all c ≤ 71, as for c ≤ 47.

The method rests on an exact identity: after periodization onto the circle of length 2L, the form becomes a sum over the lattice nodes πk/L weighted by the values of a truncated symbol, one in which the Archimedean density is restricted to [−L, L]. The nodes split into two orthogonal systems, and Parseval's identity yields a lower bound for the form, a lattice minorant, on all even functions (the odd ones are treated likewise). The positivity of the minorant reduces to a condition on a finite matrix whose order equals the number of nodes of nonpositive weight in the minorant. All inequalities are verified in ball and interval arithmetic. For c ≤ 31 the transcendental quantities and the final matrix inequalities are recomputed independently in the Arb library. The cost of the method, including the scan of the lattice nodes up to an explicit bound, lies between e<sup>(4 − o(1))√c</sup> and e<sup>(12 + o(1))√c</sup> bit operations, while the scan itself needs only memory polynomial in c.

Pages: 44. Figures: 5. MSC 2020: primary 11M26, secondary 11Y35, 65G20, 65G30, 68Q25.

## Files

The repository contains the PDF of the paper, the notes on the changes in this version (`version-notes-v2.txt`), a list of checksums `SHA256SUMS` and an OpenTimestamps timestamp for the PDF (a file with extension `.ots`). `SHA256SUMS` contains the SHA-256 of the PDF, its `.ots` proof and the version notes. The same PDF and notes are published in the Zenodo record of this version.

| File | Size, bytes | SHA-256 | MD5 |
|---|---|---|---|
| `chekmachev-truncated-weil-form-lower-bounds-v2.pdf` | 886412 | `0141813695092216f83175ae4d3ef898354e03181a3c26b801cb58412340f89d` | `1e9009624531700485dbc80e2aa63e09` |
| `chekmachev-truncated-weil-form-lower-bounds-v2.pdf.ots` | 875 | `2a861c41601bad26eaf37a09bbfbc159e119924ab9068bf2e814f89fdf889329` | `45ad066c54ba92cb5c3e6200d3c0a257` |
| `version-notes-v2.txt` | 894 | `e2fa050874373e7e0834da2aaeca946365000555f51c10adf02b5f61e3d73d77` | `7f693a372a2697c9e2716ada1610951c` |

OpenTimestamps time (UTC): <!-- filled in after the timestamp is upgraded -->

## Version history

Each version of the paper is a separate version of a single Zenodo record with its own DOI. The record's common DOI resolves to the latest version, and the paper should be cited by it.

| Version | Publication date | DOI |
|---|---|---|
| 1.0 | 2026-11-01 | [10.5281/zenodo.23848597](https://doi.org/10.5281/zenodo.23848597) |
| 2.0 (this version) | 2026-11-19 | [10.5281/zenodo.24377501](https://doi.org/10.5281/zenodo.24377501) |

## Data

The certificates of the paper are published in a separate Zenodo record. All versions of this record are listed below.

DOI of all versions: [![10.5281/zenodo.23091912](https://zenodo.org/badge/DOI/10.5281/zenodo.23091912.svg)](https://doi.org/10.5281/zenodo.23091912)

| Version | Publication date | DOI | Title |
|---|---|---|---|
| 1.0 | 2026-10-02 | [10.5281/zenodo.23091913](https://doi.org/10.5281/zenodo.23091913) | Certificate data for the paper "Rigorous lower bounds for the truncated Weil form up to support length ln 71 via a lattice minorant" |
| 1.1 | 2026-10-31 | [10.5281/zenodo.23847003](https://doi.org/10.5281/zenodo.23847003) | Certificate data for the paper "Rigorous lower bounds for the truncated Weil form up to support length ln 71 via a lattice minorant" |

The program that verifies the certificates from these data anew in the ball arithmetic of Arb is published in the Zenodo record [10.5281/zenodo.23986312](https://doi.org/10.5281/zenodo.23986312) and in the repository [coelto/weil-certs-checker](https://github.com/coelto/weil-certs-checker).

## Verification

Checksums. The command `sha256sum -c SHA256SUMS` checks the files of the repository against the list. Zenodo shows each file's MD5 next to it. It is also given in the table above, so whether a file matches the published one can be verified without downloading the archives.

Timestamp. The `.ots` file is an OpenTimestamps proof: the SHA-256 checksum of the PDF is written into a Bitcoin block, and no one can change the time of that block. To verify, it suffices to drag the PDF and the `.ots` file onto the page https://opentimestamps.org or to run `ots verify` on the proof. The file does not leave the computer in the process.

Signature. The commits of this repository are signed by the author, and GitHub marks them as Verified.

## License

The terms of distribution of the paper and its copy in this repository are given in the [`LICENSE`](LICENSE) file.
