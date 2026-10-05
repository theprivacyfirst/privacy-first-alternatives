# Contributing to Privacy-First Alternatives

First off, thank you for considering contributing! Projects like this rely on a passionate community committed to privacy, digital rights, and open-source software.

---

## 🎯 Inclusion Criteria

To keep this directory trustworthy and high-quality, any suggested alternative must satisfy the following rules:

1. **Open Source or Zero-Knowledge / E2EE**:
   - The project should ideally be **Free and Open Source Software (FOSS)** under an OSI-approved license (e.g., MIT, Apache 2.0, GPL, AGPL, BSD, MPL).
   - If a service includes hosted infrastructure, client applications must be open-source and data must be protected with audited **End-to-End Encryption (E2EE)** or **Zero-Knowledge** architecture.
2. **No Invasive Telemetry or Adware**:
   - The application must not harvest user data, sell profiles to advertisers, or bundle invasive analytics.
   - Any optional crash reports must be strictly opt-in.
3. **Actively Maintained**:
   - Projects should have regular updates, active issue tracking, and prompt security patching. Abandoned projects will be removed or replaced.
4. **Direct Replacement**:
   - The alternative must serve as a viable replacement for one or more widely used proprietary/commercial applications.

---

## ✍️ How to Add a New Alternative

Each entry in `README.md` must follow this standardized Markdown structure:

```markdown
- **[Tool Name](Official URL)** — A concise 1-2 sentence description explaining what the tool does, its key privacy benefits, and notable features.
  - 🌐 **Official Website**: https://...
  - 💻 **Open Source Link**: https://github.com/... (or GitLab / Codeberg / source repo)
  - 🔄 **Replaces**: Name of proprietary app(s) it replaces
```

### Formatting Checklist:
- [ ] Tool name is linked to its official website.
- [ ] Description is neutral, factual, and highlights privacy strengths.
- [ ] Source code URL points to the canonical repository.
- [ ] `Replaces:` accurately lists the common proprietary services people are migrating from.
- [ ] Kept in alphabetical or logical order within its category.

---

## 🚀 Contribution Workflow

1. **Fork the Repository**:
   Click the **Fork** button at the top right of this repository.

2. **Clone your Fork**:
   ```bash
   git clone https://github.com/<your-username>/privacy-first-alternatives.git
   cd privacy-first-alternatives
   ```

3. **Create a Feature Branch**:
   ```bash
   git checkout -b add/tool-name
   ```

4. **Make Your Changes**:
   Edit `README.md` to add or update your suggested entry in the appropriate section. If introducing a new category, make sure to add it to the Table of Contents as well.

5. **Commit with a Meaningful Message**:
   ```bash
   git commit -m "feat(category): add ToolName as alternative to ProprietaryApp"
   ```

6. **Push and Open a Pull Request**:
   ```bash
   git push origin add/tool-name
   ```
   Open a Pull Request describing why the tool is a great fit for the directory.

---

## 🗑️ Reporting Invalidation or Removal

If a listed application:
- Changes its license to closed-source or proprietary,
- Introduces covert telemetry or anti-privacy behavior,
- Gets acquired by an advertising/surveillance conglomerate,
- Or ceases maintenance,

Please **open an Issue** detailing the policy change with verifiable references so we can update or remove the entry.

---

## 📜 Code of Conduct

All contributors are expected to uphold our [Code of Conduct](CODE_OF_CONDUCT.md). Please be respectful and collaborative!
