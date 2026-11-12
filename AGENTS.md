# folder.view.custom.css — Agent Instructions

For **every programming task and code review**, follow the [universal Programming Clean Code Standard](https://github.com/Tyree/APApps/blob/main/agent/PROGRAMMING_CLEAN_CODE_STANDARD.md). Priority: correct and safe software first, then clean, maintainable, efficient implementation. Apply it continuously while developing; before production rollout or a significant release, run the standard's **deliberate read-only code-quality audit**, resolve unnecessary complexity in scoped batches, and validate the result. Review-only requests remain read-only. Keep this file focused on project-specific requirements rather than copying general code-quality rules.

## Project-specific safeguards

This project contains custom CSS for unRAID Folder.View-style interfaces and may depend on external plugin markup. Consult current README and plugin-version constraints.

- Avoid selector duplication, contradictory overrides, unused CSS variables, and unnecessary specificity escalation. Group rules by real concerns while retaining readable names and intentional overrides.
- Verify actual theme/plugin DOM and intended variants before declaring a selector unused. Preserve user-customizable properties and working theme behavior. Do not minify source merely to reduce line count.
