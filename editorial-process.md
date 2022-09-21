_This doc aims to document the process by which the newsletter is created and distributed, mainly for the benefit of new volunteer editors._

## Process for publishing a new issue of the newsletter

1. When you start a new issue of the newsletter, there should already be a github issue open calling for contributions from the community (created before the previous newsletter was sent out). Make sure to disseminate the link widely on social media. 
2. Create a NEW github issue (using the default issue template) with the appropiate number for the NEXT issue of the newsletter. (Try not to confuse github issue numbers and newsletter issue numbers.) This will be necessary to update relevant links in the newsletter itself. 
3. Create a new branch named `newsletter-YYYY-MM` and make a copy of the `newsletter-template.md` file, renaming it to `YYYY-MM.md` and moving it to the `newsletters/` directory.
4. Update the Table of Contents (`table-of-contents.md`) to link to the new newsletter file, and add a line linking to the new github issue you created earlier for the next newsletter. Add a new year subheading if needed.
5. In the `YYYY-MM.md` file, edit the `FIX THIS LINK` instances in the header notes (link to newsletter file in github) and in the footer notes (link to the call for contributions for the next issue; again this is the new github issue you created earlier). 
6. Start filling in the relevant content by section. A few notes:
  - If lacking community updates, get @OBF_NEWS to tweet out the call again;
  - Ask for any OBF and GSoC updates in the OBF slack workspace (open-bio.slack.com, distinct from the BOSC slack workspace);
  - The Event Fellowships section (formerly Travel Fellowships) is a standard blurb, you just need to update the event and deadline dates.
  - [...? Anything else to note?]
7. When the draft is complete, open a PR and ask OBF board members (via OBF slack) to review/comment. Iterate until approval. 
8. Once the draft has been approved, close the issue calling for contributions and merge the PR.
9. Send the newsletter out via the mailing lists, bosc-announce (Google Groups will require moderation for first time) and open-bio-l (mailman requires subscribing first). Forward the newsletter to the OBF Board, alerting them that mailing list moderator approval may be required.
10. Sit down with your preferred relaxing beverage and look forward to doing it all again in 3 months.


## Notes for onboarding a new newsletter editor

There are 3 places where text needs to be updated with the name and contact info of the new editor:

1. Main README file (`README.md`)
2. Issue template (`.github/ISSUE_TEMPLATE`)
3. Newsletter template (`newsletter-template.md`)

It's best to make these updates to the templates BEFORE starting the newsletter creation process to avoid having to update the relevant info manually.
