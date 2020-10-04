# FACILITATOR / REPO MAINTAINER GUIDE
*WIP Document*

## Some Personas:

- **Facilitator**: This is the person who is organizing the book club - primarily in charge of making sure someone presents for the following meeting, setting out meeting times/dates, and making sure someone records the meeting. It's also helpful if the **Facilitator** serves as a backup **Discussion Leader**, coming armed with some questions or discussion topics to help flesh out meetings and makes sure that everyone understands the content.  
- **Repository Maintainer**: This is the person who is in charge of making sure the GitHub repository is updated - updating the README for upcoming presentations, making sure presenters are claiming their upcoming meetings, making sure presentations are uploaded to the repository along with any supporting code.
- **Presenter**: Each week, a different person is the Presenter - they'll present `something` each week, whether it's a chapter content review, discussion of existing applications of the content, or live-coding through some practical examples. They're formally in charge about 20 minutes each week, although it can be longer (up to a full hour, sometimes). 

The **Facilitator** and the **Repo Maintainer** do not have to be the same person, and ideally the **Discussion Leader** role is organic and passed back and forth between members of the group. 

## Parts of the Repository

# Main README page

### Sections: 

- Main info

This section provides a quick summary of the main parts of the repository (usually a folder rundown). It also highlights how book club members can make Pull Requests (to claim presentations and to add their presentation contents to the repository). 

- Meeting Schedule

This section lists (only) upcoming meetings for each cohort - the next ~three are shown in the main page and the remainder are "hidden" in a details HTML block. 

Presenters are encouraged to make PRs to this section to sign up by adding their name to a chapter (and possibly a link to their Twitter handle or other website if desired).

Names and links are moved to the Presentations/Recordings section after the meeting is complete and annotated with links to slides, video, and other presentation materials. 

- Presentations and Recordings

This section lists presentations and recordings for each chapter, indexed by chapter and then by cohort. 

Slides (ie RMDs + data + supporting JS/CSS libs etc, but also possibly PPTX) should be uploaded to the `Presentations` folder. We encourage everyone to use R Markdown / Xaringan (and become comfortable using it) because it knits R code/plots/tables together better than any other presentation format, although powerpoints and links to google slides are also acceptable. The repository is pre-configured to host HTML slides that are uploaded to the Presentations folder as part of `https://r4ds.github.io/bookclub_{BOOK}` and can be linked directly (see previous examples in the Advanced R repo). 

Videos should be recordings uploaded to the R4DS Youtube - if you have questions about this part, you should ask Jon Harmon. 

# Companion

In each book club, we try to maintain a **Companion**, which is a bookdown document that holds Learning Objectives for each chapter (most are by Jon Harmon) as well as a record of every question and answer that comes up in the discussion/Slack channel post-meeting.   
