# GitHub → Zenodo DOI publication procedure

1. Obtain institutional approval for public documentation and software redistribution; complete `PUBLICATION_CHECKLIST.md`.
2. Create a **new, public, documentation-only** GitHub repository. Upload only this reviewed package, with no private Git history. Do not upload the Python application source.
3. Finalize citation authorship, ORCIDs, repository URL and publication date. Add an approved `CITATION.cff`; no fabricated metadata.
4. After Windows setup and security gates pass, upload the versioned installer and SHA-256 checksum as **GitHub Release assets** (not repository files). Confirm the release contains only approved material.
5. Connect the public GitHub repository to Zenodo, enable archiving, and create/publish the approved GitHub release (e.g. tag `v2.0.0`). Verify the archive and DOI at Zenodo.
6. Check what Zenodo actually archived: GitHub integration generally archives the repository release snapshot; GitHub binary release assets may require separate Zenodo deposit/attachment depending on integration behavior. Do not assume the installer is preserved in Zenodo without checking.
7. Add the issued DOI badge and citation to README and CITATION files, then publish a documentation update. Distinguish concept DOI from version-specific DOI where relevant.

**No DOI has yet been issued.** A documentation-only archive can have a DOI even if the Python source remains private, provided the deposited content and rights are accurately described. Verify Zenodo's current GitHub integration requirements at publication time.
