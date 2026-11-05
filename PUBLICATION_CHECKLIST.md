# Public repository publication checklist

Before making this repository public:

- [ ] Confirm the project owner approves the public description and all included claims.
- [ ] Confirm that this curated starter is the only content being published; do not copy the full internal architecture tree into it.
- [ ] Recheck the entire Git history and all files for secrets, patient data, personal data and confidential material.
- [ ] Remove any private issue, PR, action log or artifact references before publication.
- [ ] Enable private vulnerability reporting / security advisories.
- [ ] Enable secret scanning and push protection where available; still scan locally before every push.
- [ ] Review GitHub Actions and workflow permissions. Remember that public repository action history and logs can be visible publicly.
- [ ] Decide whether to add a license. Do not imply open-source reuse until an actual license is selected.
- [ ] Keep the complete internal engineering architecture in a separate private repository.
- [ ] Reconfirm that no clinical, regulatory, partner-integration or production-readiness claims are unsupported.

A public repository can be forked and copied. Changing it back to private later does not guarantee that public forks or copies disappear.
