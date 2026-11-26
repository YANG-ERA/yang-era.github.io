# Website Maintenance

- Goal: Keep the current site structure while updating the profile and publications and incorporating the owner's layout and content preferences.
- Completed: Updated the profile to second year and added CellPatch. Restored News as the final home section with month-and-year dates and kept the two Ph.D. milestones exclusively there. Removed inline personal contributions and all visible figure-credit UI. Figures link to the source paper; the markup retains creator and license information.
- Verified: Jekyll built with GitHub Pages dependencies. Browser checks at 320, 390, 768, 1024, and 1440 px covered figure loading and source links, responsive layout, absence of Figure credits, footer position, and CellPatch details. News date and position, and CV exclusions, were also verified.
- In progress: No remaining source changes. GitHub Pages publishes from `master`; the public page is https://yang-era.github.io/publications/.
- Input needed: None.
- Decisions: Keep the current Jekyll collection and article URLs. Use a 7:3 text-to-figure layout on wide screens and one column on narrow screens. Keep bibliographic years aligned with journal issues and identify the CellPatch release as an online publication.
