# DSL Demo Course - course control panel

This is the **`.github` repo** for the `DSL-Demo-Course-E1234` course org - the control panel faculty use to run
the course. **You never need a CLI or to write code: every action is a clickable UI button.**

## Run an action

Open the **[Actions tab](https://github.com/DSL-Demo-Course-E1234/.github/actions)**, pick a workflow, and click
**Run workflow**. Buttons only show if you have write access (you're in this org's `instructors`
or `course-admin` team). The full, annotated list of actions is on the
**[org home page](https://github.com/DSL-Demo-Course-E1234)**.

## Typical flow

1. **New materials repo** / **New assignment** - scaffold your content repos, then fill them in.
2. Create an empty **cohort org** for the year, add the bot as an Owner, then run **Bootstrap cohort**.
3. Each week: **Release materials** / **Release assignment**. Students self-onboard via the cohort's
   **welcome** "Join" issue.
4. Grading: **Grade assignment** -> **Sync gradebooks** -> **Render grades** -> **Distribute grades**.

## What's in here

- `.github/workflows/` - the action buttons (seeded from the central toolkit; refreshed by **Refresh actions**).
- `dsl-course.yml` - this course's identity (name/code). People + schedule are declared per cohort.
- `profile/README.md` - the public org landing page (auto-generated repo index).

Built and kept in sync by the [DSL teaching toolkit](https://github.com/hertie-data-science-lab/dsl-teaching-course-setup).
