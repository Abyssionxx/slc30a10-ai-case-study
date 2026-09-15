# Public distribution notes / 发布说明

This is a distribution snapshot, not the original Git history. It was exported from source commit `24ac2e7590411632dbe5bd00773a14ee04bc8efc`. The original local project and scientific outputs were not modified. All figures and analytical tables retain their source bytes except any files explicitly listed as path-normalized in PUBLIC_FILE_MAP.json.

Private workstation/server directory strings were replaced by /path/to placeholders in the files listed in PUBLIC_FILE_MAP.json. Those are examples, not executable environment settings. Configure wrappers and the historical scripts before running in a separate project. Target-specific biological parameters remain SLC30A10-specific. The scripts are archival research code, not a turnkey general-purpose application.

Historical .sha256 files and Git hashes remain as historical evidence. Some historical checks WILL FAIL in this distribution because paths were normalized or third-party files omitted. Do not regenerate the historical manifests and call them original. Verify this snapshot with PUBLIC_FILES.sha256 (or python3 verify_public.py). To replay numerical analysis, use an isolated copy, supply missing source assets, document remapping, and prepare stage-specific inputs. Do not delete the blind lock in the source project. No scientific rerun was performed during publication.

Third-party paper text, figures, rendered supplement pages, full source workbook and workbook-cell transcription are not bundled. See SOURCES.md and OMITTED_FILES.txt. Derived experimental labels and benchmark tables are retained with source references. Raw sequence and model inputs are included with their retrieval metadata. This is computational data, not newly generated wet-lab raw data.

Original blind checkpoint: 008b7ad7a436fc02898292ec7d0441cf0df6c390
Final scientific report checkpoint: 03379f6af433d0134a8d910a39cd8993fc0ea9a3

The public PDF is a byte-identical copy of the existing 25-page technical report PDF; it is not peer-reviewed and does not report new wet-lab experiments. The source snapshots and PDF use historical study dates, not a claim of independent prospective clinical or experimental validation.

No new software/content reuse license is granted by this snapshot. A code license and an original-report license can be selected by the owner later; third-party source terms remain separate. Do not call this repository fully open-source until those terms are specified.
