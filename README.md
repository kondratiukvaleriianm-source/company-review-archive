# Company Review Archive

Team-only, bilingual (EN / UK) directory of outside-company reviews: revenue, business model, evidence-tagged numbers, scores and verdicts. One template for every review.

- Single static page: `index.html` (data and code in one file, no build step).
- Add a review: append an object to `REVIEWS` above the `/*__NEW_REVIEWS_ABOVE__*/` marker. Every text field is `{en, uk}`.
- Controlled lists (categories, business models, verdicts, statuses) sit at the top of the data block.
- Template spec: see the "Companies review" project, `company-review-template-v1.md`.
- Access: a code screen in the page, same approach as the Network State Atlas. Change `ACCESS_CODE` near the end of `index.html`.
- Deploy: Netlify, continuous deployment from `main`, no build step. Keep this repository private.
