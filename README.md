# Jira Cloud: Make Work Ready to Act On

Independent portfolio sample by Lorne Hopkins. Release candidate, not official employer/vendor training.

## Run

Open index.html, or run `python3 -m http.server 8000` in this folder. Public preview sends no learner data.

## Author and brand

Edit assets/course.json, then run `python3 scripts/build.py`. Brand values live in the JSON and generated css/brand.css. HTML, CSS, JavaScript and assets remain separate.

## Learning record modes

SCORM 1.2 launches initialize an LMS API, write bookmark, limited suspend state, score and participation completion. Writing is excluded from LMS storage. Resume requires re-entering/reviewing the written response. Local synthetic xAPI mode requires the suite lab gateway and `?tracking=lab`. Never place LRS credentials in these files.

## Verification boundary

See qa/ for executed checks. A mocked SCORM test is not a Moodle runtime test. Screen-reader testing, real LMS launch/resume and pilot review remain release gates. This custom portfolio player is an explicit development choice to preserve the high-fidelity design; it is not an Adapt export. Existing Adapt infrastructure remains available and unchanged.

## Sources

- [Atlassian: Create a work item](https://support.atlassian.com/jira-software-cloud/docs/create-a-work-item-and-a-subtask)
- [Atlassian: Jira workflows](https://support.atlassian.com/jira-software-cloud/docs/what-are-jira-workflows/)

Reviewed 9 October 2026. Company-specific procedures and UI configuration must be validated in the intended tenant.
