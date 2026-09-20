---
version: 1
slug: "components-tools-astro"
primary_target: "components/Tools.astro"
related_targets: ["src/pages/index.astro", "components/MenuPanel.astro", "components/Footer.astro"]
---

# Tools section extension

Scope: A tools section on the existing home page, placed after Current Projects and before Open Roles. Visitor mode: Read and persuade.

Audience and job: Hiring managers, prospective collaborators, and clients who need to understand how Nasif moves from an ambiguous business problem to a working product, pipeline, or decision. The section presents the toolkit as an operating stack rather than a collection of endorsements or a decorative logo wall.

## Direction contract

THESIS: Tools form an operating stack. Group them by the job they perform so the visitor sees a connected method of work, not an undifferentiated logo wall.

OWN-WORLD: Preserve the portfolio's established white and near-black surfaces, electric cobalt accent, editorial display type, compact utility labels, and hairline-rule construction. Brand color belongs inside the tool marks; each mark sits on a consistent white logo plate so a varied asset set remains composed.

STORY: The visitor moves through three functional layers: Agentic Engineering for building, orchestrating, and verifying; GTM Systems for finding, enriching, and reaching opportunities; and Frameworks + Libraries as production foundations with explicit jobs.

FIRST VIEWPORT: The established two-column section header introduces “The stack behind the systems.” Below it, three full-width horizontal category bands create the primary rhythm: near-black Agentic Engineering, cobalt GTM Systems, and a light Frameworks + Libraries band.

FORM: Each band pairs a numbered category header with a ruled tool area. Agentic Engineering uses a four-column desktop grid. GTM Systems presents Instantly, Apify, and LinkedIn Sales Navigator in three equal desktop columns, collapsing to one column on mobile. Frameworks + Libraries balances its seven tools as four items followed by three on desktop; at `<=1000px` it becomes a two-column grid with the final item spanning the full width, and at `<=420px` it collapses to one column. The band header stacks above the grid on mobile, while short framework usage labels preserve each tool's role.

SIGNATURE: The site's existing upward reveal motion introduces the header and bands. On pointer hover, each white logo plate lifts slightly and rotates by two degrees, adding a restrained tactile cue without turning the marks into spectacle. Reduced-motion preferences remove the logo transition.

PLACEMENT: Render immediately after Current Projects (`CurrentFocus`) and before Open Roles (`Roles`) in the home-page sequence. Keep the `#tools` anchor aligned with the matching menu and footer links.

FINISH: Preserve semantic nested sections, labelled headings, decorative empty-alt logo images, lazy loading, responsive hairline continuity, and reduced-motion behavior. Future tool changes should keep category purpose and grid balance legible rather than optimizing for a fixed logo count.
