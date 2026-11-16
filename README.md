# Hadithi Zetu — Final Interactive Media Design Project

## Project overview
Hadithi Zetu is a responsive front-end interactive storytelling interface for exploring and sharing Kenyan cultural stories. It is designed for university and college students, young people, educators, researchers and anyone interested in cultural heritage.

## Run locally
1. Extract the complete ZIP folder.
2. Keep `index.html`, `style.css`, `script.js`, the five image files and this README in the same `hadithi_zetu` folder.
3. Open `index.html` in Chrome, Edge, Firefox or Safari.
4. Internet access is required for the remote Unsplash landscape images and Google Fonts. The five community photographs supplied for this project are stored locally in the folder.

## Files
- `index.html` — page structure, sections, forms and modals
- `style.css` — responsive visual design and layout
- `script.js` — story library, search, filters, quiz, comments, ratings, feedback, saved stories and submissions
- `MIJIKENDA.jpg`, `MAASAI.jpeg`, `LUO.jpg`, `KALENJIN.jpg`, `KIKUYU.jpg` — photographs supplied by the project owner
- `Hadithi_Zetu_Design_Report.pdf` — 1–2 page design report

## Main interactive features
- Navigation links and community collection cards
- Search and filtering by community and story type
- Story reading modal with text-to-speech narration, save control, rating and comments
- Knowledge quiz with immediate correct/incorrect feedback, explanations, score and retry
- Cultural story contribution form with pending-review confirmation
- Audience feedback form with submission confirmation
- Responsive mobile navigation

## Alignment with BJO 213 project guidelines
**Purpose and target audience:** The purpose is to support discovery, learning and respectful sharing of cultural stories. The intended users are students, young people, educators, researchers and heritage enthusiasts.

**At least two interactive elements:** The prototype includes navigation, clickable community cards, searchable/filterable story cards, story controls, a quiz, comment/rating controls, a feedback form and a story-submission form.

**Immediate feedback:** Quiz answers show correct/incorrect states and explanations. Form submissions display confirmation messages. Saved stories and ratings also show visible status changes.

**Logical layout and hierarchy:** Content follows a familiar sequence: introduction, community collections, searchable story library, learning activity, critical reflection, contribution and feedback. Headings, spacing, labels and consistent controls establish hierarchy.

**Cognitive psychology principles:**
1. Recognition rather than recall — visible community cards, search labels, categories and familiar action names help users recognise available choices instead of remembering commands.
2. Chunking — stories are divided into short paragraphs and the interface separates discovery, reading, quiz and feedback into clear sections.
3. Immediate feedback — the quiz and forms respond visibly to user actions.
4. Hick’s Law / choice reduction — the main navigation and story filters present a limited set of clear options at each step.

**Mental models:** The design uses familiar patterns: a logo links to home, navigation links move to labelled sections, magnifying-glass/search conventions find content, a play control starts narration, a heart saves a story, star controls rate it, and forms use familiar labels and submit buttons. These patterns match common expectations and avoid misleading labels.

**Confirmation bias:** A dedicated “Think beyond what you know” section asks users to notice prior assumptions, compare perspectives and check sources. It encourages curiosity and source evaluation rather than reinforcing only information that confirms existing beliefs.

## Prototype limitations and responsible use
This is a front-end prototype. Comments, ratings, saved stories, feedback and submissions are stored in the visitor’s own browser using local storage; they are not shared between devices or users. Story submissions are marked pending review but there is no secure administrator account or live moderation backend. A production service would need a server/database, authentication, access control and moderation workflow.

The included sample story narratives are illustrative demonstration content, not verified traditional oral histories. They must not be presented as authentic community traditions. Replace them with stories gathered from reliable sources or community contributors, with consent and attribution. Verify translations and cultural details with knowledgeable speakers, and do not publish sacred or restricted knowledge without permission.

The five community photographs are the user-supplied images and are used as collection-card visuals according to the user’s requested mapping. Confirm permission and add photographer/source credits and accurate captions before public distribution. Landscape images from Unsplash are illustrative only and do not represent a particular community.

## Final testing checklist
- Open the page and use every navigation link.
- Select each of the five community cards and confirm the story filter updates.
- Search for a story and test both filters.
- Open a story; test narration, save, rating and comment.
- Complete the quiz, read the feedback and retry.
- Submit a sample feedback form and a sample story contribution.
- Resize to mobile width and test the menu.
