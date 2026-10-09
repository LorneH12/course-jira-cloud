# Branded course release — 9 October 2026

Jira Cloud: Make Work Ready to Act On

## Creative direction
Playful / collaborative / visible progress. Amex lens · Jira DC / Rally to Cloud enablement.

Existing shared course engine enhanced with topic-specific HTML/CSS artwork, short entrance motion, interactive ungraded rehearsal, optional narrated companion video, English captions and transcript. Text remains sufficient. Motion respects device preferences and the learner's Reduce motion setting. No autoplay. No AI clone or impersonation is used.

## Source
Edit branded-course.json; regenerate course-data.js as window.COURSE=<JSON>; experience.js is the enhanced shared player; widgets.js supplies topic-specific rehearsal; experience.css contains base and theme styles. Original js/tracking.js remains the existing SCORM/local-lab adapter. Older assets/course.json and js/player.js are retained historical source and are not loaded by this release. Do not run the older scripts/build.py over this release. release-scorm12.zip is the matching package candidate.

## Media reuse
Companion: https://lorneh12.github.io/learning-portfolio-platform/media--jira-cloud--ji-1.mp4
Catalog baseline: dbc29fed2529503420d17e1b3df975407a15634f. Transcript reviewed and sampled film frames inspected for alignment. Complete listening/visual review remains a review task. Reused film is a separate fictional scenario; its response is provided beneath it. Media remains hosted by the catalog; no catalog files were changed. Video requires internet even in the SCORM package.

## Evidence and constraints
Brand-inspired portfolio sample, no employer endorsement. All scenarios synthetic. Five-question check target 80%; participation completion is separate. Writing self-review is not a competence score. No learning-record backend deployed. Full accessibility, human pilot and real LMS interoperability remain pending. No purchases or new credentials.

## Interactive media revision — 9 October 2026
Prominent editorial hero, direct Watch entry, existing narrated scenario with captions and Read alternative. The activity now precedes the worked explanation. Jira and Confluence have topic-specific builders with guarded release/status decisions. ADKAR retains an evidence-based coaching rehearsal; Adult Learning builds a 12-minute workshop; EBITDA includes an animated earnings meter. Hero art is AI-generated illustration, not employer imagery or an AI presenter. Presenter media remains pending from dot. Existing tracking and scoring preserved.
Source: media-first.js provides the presentation/interaction layer; edit it with experience.css. The reusable engine remains experience.js.
