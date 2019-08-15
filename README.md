# Design Docs
This README is an index of documents for important components and changes, as well as notes, thoughts, and discussions that don't fit anywhere else yet.

See [Design Docs: What are they and how we use them](designdocs.md).

## Design Docs
_Newest to oldest_

* [Separating Messages from Block](https://docs.google.com/document/d/1xOHUeM-svZoE3qQtOPCx1U96EQ6CuKsfB2GJYOHOk18/edit?usp=sharing) July 2019
* [Faults & Slashing implementation](https://docs.google.com/document/d/1U3b9GVNVOLoS_-q9kXU3a9dqHGvcrHprwDFzNYgLI0M/edit#) - June 2019
* [SectorSet and Bitfield Implementation Plan](https://docs.google.com/document/d/1aE5a-QZojprMkig6IyYkwV1SrMDDLOnNBqNdnwpu9tk/edit?usp=sharing) - June 2019
* [Model for change: Filesystem repo migrations](https://docs.google.com/document/d/1THzh1mrNCKYbdk1zP72xV8pfr1yQBe2n3ptrSAYyVI8/edit?usp=sharing) - April 2019
* [Slashing Mechanism](https://docs.google.com/document/d/1bGjNI4wItBWgH5SOxpLNFF3ij85CRKG_uRVSbI7yLS4/edit#heading=h.2xtbr35i3dx3) - March 2019
* [Outbound Message Queue](https://docs.google.com/document/d/1Ns5_ushX9exsKr0xbc2Kt0ZHzAA0WnVvl42hyGRR5l0/edit) - March 2019
* [Message Tracking](https://docs.google.com/document/u/2/d/1Ofoid90l9JwyW8zUy00kaHdvpLoV4gr2mcN3s4irkPY/edit?usp=drive_web&ouid=117191042581679083795) - Feb 2019
* [Porcelain/Plumbing Refactor Plan](https://docs.google.com/document/u/2/d/1L5hbcDGhfH3AlMti4RQ3Zke6nc4-eGOmk9lD0nNoiEs/edit?usp=drive_web&ouid=117191042581679083795) - Feb 2019
* [JSON REST API Rationale and Plan](https://docs.google.com/document/d/1ANnTHOU-8612ayvvS7Ru4B1L4voojLE0R0TQ8zF1x5s/edit#) - Aug 2019
* [meta] [Design Docs: What are they and how we use them](https://github.com/filecoin-project/designdocs/blob/master/designdocs.md) - Aug 2018

### Video Recordings
_Explainer talks or demos._

### Other Writeups & Notes
_Other writeups or less-edited notes from discussions & meetings_
* [Are We Speced Yet?](https://docs.google.com/spreadsheets/d/1zh7Ys6Tr0y4nLsR9d9e28Q0pYNBvclmcgHU3yuwMhSI/edit?usp=sharing)

## How to Create New Design Docs
We follow a process to ensure that new design docs are accessible and communicated widely.
* Create a GitHub issue for the design doc in the appropriate repository (e.g. [go-filecoin](https://github.com/filecoin-project/go-filecoin), [consensus](https://github.com/filecoin-project/consensus)).
* Create a new Google doc in the `Filecoin Community` team drive, `Design Docs` folder.
  * Check that you're using the GApps identity of your choice.
  * Use `DRAFT`, `IN REVIEW`, `IMPLEMENTING` near the top of the content to note status.
* When you're ready, enable public comments. As of April 2019, this takes 5 clicks:
  * Click "Share" button.
  * Click "Who has access" to open the advanced settings panel.
  * Toggle on "Link sharing".
  * Choose who: "Anyone with the link".
  * In the dropdown after "Access", select "Can comment".
* Add an entry with shareable link in this README's list of design docs, thus making the document public (you can commit directly).
* Email a link to the `dev@filecoin.org` email list, which will reach all committers. 
Also announce in `#fil-dev` or other appropriate channel the filecoin-project Slack.
  * This email thread will function as a low-noise channel for high-level discussion of the proposal.
* Solicit feedback from individuals and/or channels, evolving the design as needed.
  * Advertise major changes with a post to the email/slack threads where the design was announced.
  * Seek approval from at least one maintainer before considering the proposal accepted.
* Once ready, translate into GitHub/ZenHub epics or issues according to the appropriate repo's contributing guide.

Note: people outside committers and some other full-time project contributors cannot directly place docs in the team drive.
If a document originates outside this set but is accepted, a committer should copy the content into the team drive.

As an alternative to Google Drive, a design doc may be drafted in a PR to a markdown file in the `docs` directory of this repository.


## Contributing to this repo
We play fast and loose in this here `designdocs` repo, but not recklessly.
- If you are adding new content, committers can commit directly.
- If you are editing or refactoring existing content, get 1 reviewer (preferably the original author, but others if they're not available). 
If they don't reply in 3 days with reasonable reminding efforts, committers can commit directly.
