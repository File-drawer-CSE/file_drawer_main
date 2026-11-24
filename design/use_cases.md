# Use Cases
# The File Drawer: Use Case Descriptions

These 14 use cases were extracted from the group's user stories for the
CSE 583 File Drawer project. Prevalence labels are qualitative. Primary
tasks reflect stated user needs; operational workflows are proposed
sequences to validate with the group.

## UC-01: Search and Retrieve Research Records (priority)

**Prevalence:** Very High

### Who is the User?

**Persona/Role:** Researchers, graduate students, librarians, and
academic reviewers.

**Context:** Users want to find previously conducted research,
particularly unpublished studies, unsuccessful experiments, and
inconclusive findings. They may be exploring new research questions,
conducting literature reviews, or investigating alternative experimental
methods.

**Representative personas:** Lily, Bob, Sarah, Martha, Priya, and Felix.

### What Do They Want to Do with the Tool?

**Primary Tasks:** - Search for research using keywords, topics,
methodologies, or experimental outcomes. - Filter search results to
identify relevant studies. - Access records containing research methods,
results, and supporting information.

**Operational Workflows:** 1. User accesses The File Drawer. 2. User
enters a research topic, keyword, or other search criterion. 3. The
system searches available research records. 4. The system displays
matching studies. 5. User selects a study to review its information and
supporting files.

**Functional needs:** 1. Create a search bar where you can type any characters 2. Interface connected to search bar that takes input from search bar and produces a result including some sort of keyword match 3. Add keyword/ genre/ domain filtering if possible 3. Page with search results that user can interact with to view each entry 4. Create a format for each search result that stores the metadata with the files/ profile for the corresponding project 4. Some way for users to be able to download files associated with a particular null result entry. 

**Accessibility needs:** 1. Page works with screen reader for low visibility users 2. Easy and visible search buttons and clear instructions throughout the page 

**Uncertainties/ assumptions:** 1. People know what they're looking for 2. what if people misspell search entries or there are not exact matches, how will we recommend results? 3. Do we care about web scrapers? Do we want to limit the number of downloads a user can make each day? 

**Standard workflow:** 
1. When the user Creates an account the system should store their profile information in our database and the user can login with that information for future sessions
2. When the user search the repository by typing the system should return results that most closely match their search. If there are no matches system returns a message saying there are no matches (or ideally suggesting different results) 
3. User use filtering for results system will narrow down null result entries to those that fit the selected metadata criteria
4. User saves entries of interest (maybe using starring or favoriting) and the system creates a collection of entries on a page that is connected with the user profile 

## UC-02: Navigate the Repository Without Programming Experience (priority)

**Prevalence:** Very High

### Who is the User?

**Persona/Role:** Researchers, students, faculty members, and other
users with varying technical experience.

**Context:** Many potential users have limited or no experience with
GitHub, Python, or software development. They need a straightforward way
to interact with the repository without learning programming.

**Representative personas:** Anderson, Abhi, Eldar, Velma, and Nadia.

### What Do They Want to Do with the Tool?

**Primary Tasks:** - Navigate the repository using an intuitive
graphical user interface. - Search, upload, and access research without
writing code. - Complete tasks efficiently with minimal technical
knowledge.

**Operational Workflows:** 1. User opens the repository through a
graphical interface. 2. User identifies the desired function, such as
searching or uploading. 3. User follows the interface to complete the
task. 4. The system displays results or confirmation of the completed
action.

**Functional needs:** 1. Create a website for navigating the repository 2. Create instructions for user for uploading their own data 3. Create a series of webpages that uses go through to upload data that is synced with the repository and automatically uploads files and metadata 4. Create integration with google/ facebook/ orchid for people to create a profile 5. Create user profile page on website 6. Decide on required and optional fields for upload. 

**Accessibility needs:** 1. Clear instructions 2. Information for who to call if a user needs help (number, chat bot, email etc..) 

**Uncertainties/ assumptions:** 1. Who do people contact if they have issues?

**Standard workflow:** 
1. When the user wants to upload data the system will provide several pages with prompts for entering metadata and uploading files. 
2. When the user finishes uploading data the system will automatically store it and make it searchable.
3. When the user creates an account the system will automatically offer to create an account with their google or orchid login information
4. When the user creates an account they will be able to view and edit their profile on the website. 

**Note:** This is primarily a usability requirement applying to multiple
use cases, rather than a separate system interaction.

## UC-03: Access and Reuse Existing Research Data (priority)

**Prevalence:** High

### Who is the User?

**Persona/Role:** Researchers, graduate students, and data analysts.

**Context:** Users want to access existing experimental data,
methodologies, and code for secondary analyses, meta-analyses, or
developing new research directions.

**Representative personas:** Lily, MJ, Lay Heng, Ethan, and Maya.

### What Do They Want to Do with the Tool?

**Primary Tasks:** - Access datasets and supporting research
materials. - Download available files for independent analysis. -
Compare existing findings with their own research. - Reuse available
research methods or code.

**Operational Workflows:** 1. User searches for relevant research. 2.
User selects a study containing useful information. 3. User examines the
available datasets, methods, or code. 4. User downloads the relevant
materials. 5. User uses the information in their own research or
analysis.

## UC-04: Organize Interdisciplinary Research

**Prevalence:** low, starting with just psychology

### Who is the User?

**Persona/Role:** Researchers from different academic disciplines and
repository administrators.

**Context:** Research conducted in engineering, psychology, statistics,
history, and other disciplines can involve different experimental
methods, file formats, and reported outcomes. Users need a repository
capable of accommodating these differences.

**Representative personas:** Sally, Shaq, Brenda, Aseel, and Oliver.

### What Do They Want to Do with the Tool?

**Primary Tasks:** - Organize research by discipline, methodology, and
other relevant characteristics. - Store different research file types. -
Find discipline-specific information. - Retrieve research using
consistent organizational structures.

**Operational Workflows:** 1. User submits or searches for research in a
particular discipline. 2. The system provides relevant organizational
categories or metadata. 3. Research records are associated with
appropriate categories. 4. Users browse or filter records using those
categories. 5. The system displays relevant research information.

**Gap to resolve:** Your group has not yet decided whether to use
universal metadata fields, discipline-specific templates, or a hybrid
approach.

## UC-05: Submit and Preserve Unpublished Research (priority)

**Prevalence:** Very High

### Who is the User?

**Persona/Role:** Researchers, faculty members, and students.

**Context:** Users have unpublished studies, inconclusive experiments,
abandoned projects, or other research materials they want to preserve
for future reference.

**Representative personas:** Anderson, Ryla, Eldar, Abhi, and Penelope.

### What Do They Want to Do with the Tool?

**Primary Tasks:** - Upload unpublished research records. - Submit
supporting documents, datasets, and experimental methods. - Organize
multiple research projects. - Retrieve previously uploaded work.

**Operational Workflows:** 1. User accesses the submission interface. 2.
User provides information describing the research. 3. User uploads
relevant files. 4. The system stores the research record and associated
files. 5. User accesses the stored record when needed.

## UC-06: Share Research and Collaborate with Others (priority)

**Prevalence:** High

### Who is the User?

**Persona/Role:** Researchers, collaborators, research teams, and
students.

**Context:** Users want to share research findings and supporting
information with colleagues or collaborators to support joint research
and discussion.

**Representative personas:** Eldar, House, Sherlock Holmes, Velma, and
Brennan.

### What Do They Want to Do with the Tool?

**Primary Tasks:** - Share research records with collaborators. -
Provide access to relevant findings and supporting materials. -
Communicate research information to team members.

**Operational Workflows:** 1. User locates a research record. 2. User
selects the information they want to share. 3. The system provides a way
to share the record or its contents. 4. The collaborator accesses the
shared information, subject to permissions. 5. The collaborators use the
information for their work.

## UC-07: Manage Privacy and Access Permissions

**Prevalence:** Moderate

### Who is the User?

**Persona/Role:** Researchers submitting unpublished, confidential, or
sensitive information.

**Context:** Users may be concerned about exposing unpublished research,
compromising sensitive data, or allowing unauthorized individuals to
access their work.

**Representative personas:** Eldar, Peter Parker, Bruce Wayne, Penelope,
and Nadia.

### What Do They Want to Do with the Tool?

**Primary Tasks:** - Control who can access research records. - Restrict
access to sensitive materials. - Store private drafts. - Share selected
research with authorized collaborators.

**Operational Workflows:** 1. User uploads or selects a research record.
2. User specifies the desired access restrictions. 3. The system applies
those permissions. 4. An individual attempts to access the record. 5.
The system grants or denies access according to the permissions.

**Gap to resolve:** The user stories do not establish which permission
levels the repository will support.

## UC-08: Evaluate Research Quality and Credibility

**Prevalence:** Moderate

### Who is the User?

**Persona/Role:** Researchers, librarians, journal reviewers, and
academic editors.

**Context:** Users want to determine whether uploaded studies are
reliable, adequately documented, and appropriate for use in their
research.

**Representative personas:** Sky, Priya, Felix, and Vicky.

### What Do They Want to Do with the Tool?

**Primary Tasks:** - Examine experimental methods and supporting
evidence. - Identify limitations of individual studies. - Distinguish
inconclusive findings from evidence supporting no effect. - Review
available verification information.

**Operational Workflows:** 1. User locates a research record. 2. User
examines the study's methods, findings, and limitations. 3. User reviews
available supporting evidence and verification information. 4. User
assesses whether the research is suitable for their intended purpose.

**Gap to resolve:** The stories request credible information, but they
do not establish a formal verification or peer-review process.

## UC-09: Identify and Cite Original Research Contributors

**Prevalence:** Moderate

### Who is the User?

**Persona/Role:** Research contributors, students, researchers, and
reviewers.

**Context:** Users want to identify the original contributors of
unpublished research and provide appropriate attribution when using
their work.

**Representative personas:** Eldar, Lay Heng, Ethan, and Vicky.

### What Do They Want to Do with the Tool?

**Primary Tasks:** - Identify original research authors. - Retrieve
citation information. - Attribute research contributions. - Access
persistent references to research records.

**Operational Workflows:** 1. User opens a research record. 2. The
system displays available authorship and citation information. 3. User
retrieves or exports the citation. 4. User incorporates the citation
into their own research.

## UC-10: Export and Integrate Research Information

**Prevalence:** Lower-Moderate

### Who is the User?

**Persona/Role:** Researchers, programmers, and data analysts.

**Context:** Technically experienced users want to incorporate
repository data into their existing research workflows and software
tools.

**Representative personas:** Tony Stark, Aseel, Maya, and Ethan.

### What Do They Want to Do with the Tool?

**Primary Tasks:** - Export research information in reusable formats. -
Access structured datasets. - Integrate repository information with
existing software. - Retrieve available code or computational results.

**Operational Workflows:** 1. User locates relevant research records. 2.
User selects the information or files needed. 3. The system provides an
available export format or integration method. 4. User retrieves the
information. 5. User incorporates it into an external research workflow.

## UC-11: Report and Resolve Repository Issues

**Prevalence:** Low

### Who is the User?

**Persona/Role:** Repository administrators, developers, and users
experiencing technical difficulties.

**Context:** Users may encounter technical problems, and administrators
need to coordinate fixes and communicate with affected users.

**Representative personas:** Developer MJ and Kiara.

### What Do They Want to Do with the Tool?

**Primary Tasks:** - Report repository issues. - Communicate problems to
administrators. - Assign issues to team members. - Resolve issues and
provide updates.

**Operational Workflows:** 1. User identifies a problem. 2. User reports
the issue. 3. An administrator reviews the report. 4. The issue is
assigned to an appropriate team member. 5. The team investigates and
addresses the problem. 6. The affected user receives an update.

## UC-12: Save and Organize Research for Later Use

**Prevalence:** Low

### Who is the User?

**Persona/Role:** Researchers and students reviewing multiple studies.

**Context:** Users want to revisit relevant research without repeatedly
searching for the same records.

**Representative personas:** Martha and Felix.

### What Do They Want to Do with the Tool?

**Primary Tasks:** - Bookmark research records. - Save records for later
reference. - Organize saved research into collections.

**Operational Workflows:** 1. User searches for research. 2. User
identifies a relevant record. 3. User saves or bookmarks the record. 4.
The system associates the record with the user's saved collection. 5.
User retrieves the saved record later.

## UC-13: Maintain Long-Term Research Accessibility

**Prevalence:** Low

### Who is the User?

**Persona/Role:** Researchers, librarians, and institutional users.

**Context:** Users want to ensure that unpublished research remains
accessible over time, including after researchers retire or leave their
institutions.

**Representative personas:** Seb, Kiara, Anderson, and Eldar.

### What Do They Want to Do with the Tool?

**Primary Tasks:** - Preserve research for long-term access. - Retrieve
archived research records. - Make appropriate research information
accessible beyond individual institutions.

**Operational Workflows:** 1. User submits research for preservation. 2.
The system stores the research record. 3. The repository maintains
access to the record over time. 4. Future users locate and retrieve the
stored information.

**Gap to resolve:** The user stories do not specify a preservation
platform, retention policy, or long-term funding model.

## UC-14: Detect and Prevent Malicious Activity

**Prevalence:** Rare but Critical

### Who is the User?

**Persona/Role:** Malicious individuals, repository administrators, and
legitimate research contributors.

**Context:** Individuals may attempt to access restricted information,
scrape research data for exploitation, misrepresent findings, or use
unpublished work without proper attribution.

**Representative personas:** Dan and Dr. Doofenshmirtz.

### What Do They Want to Do with the Tool?

**Primary Tasks:**

*Malicious users:* - Attempt to obtain research information for
unauthorized or unethical purposes. - Exploit weaknesses in the
repository. - Misuse research data or claim credit for others'
contributions.

*Repository administrators:* - Prevent unauthorized access. - Identify
suspicious activity. - Respond to security incidents.

**Operational Workflows:** 1. An individual attempts to access or
extract repository data. 2. The system checks applicable access
permissions. 3. The system denies unauthorized requests. 4. Suspicious
activity may be recorded or flagged. 5. Administrators investigate and
respond when necessary.

**Gap to resolve:** The user stories establish the threat, but your
group still needs to determine which security safeguards and monitoring
capabilities are appropriate.

**Functional needs:** 1.	System should log all user actions (logins, searches, failed access attempts) with timestamps and user IDs. 
2.	System should only allow users to view/download resources they are authorized for. 
3.	System should apply rate-limiting rules (e.g. cap the number of downloads) to prevent scraping large amounts of data. 
4.	System should flag activity that crosses defined thresholds (e.g. repeated failed login attempts and unusually high download volume). 
5.	System should automatically respond to flagged activity with growing actions (e.g. CAPTCHA challenge, temporary account logout, and restricting actions). 
6.	 System should notify administrators when suspicious activity is flagged with a dashboard where they can review the incidents. 
7.	System should allow administrators to manually ban, suspend, or restrict a user account. 

**Accessibility needs:** 
1.	Admin security dashboard should be screen-reader accessible with clearly labeled alerts and action buttons.
2.	CAPTCHA or bot-detection challenges presented to users should offer accessible alternatives. 
3.	Notifications to users about account restrictions or lockouts should be clearly worded and accessible. 

**Uncertainties/ assumptions:** 
1.	How do we define thresholds for "suspicious" activity? 
2.	There can be overlap between innocent and malicious behavior.
3.	Do we need to comply with specific institutional or legal requirements around logging user behavior and data retention?
4.	Should the system support IP-based blocking, or only account-based restrictions?
5.	How long should activity logs be retained?
6.	Do we assume all users must have authenticated accounts, or do we also need to handle anonymous/guest access?

**Standard workflow:** 
Standard Workflow: 
1.	When a user creates an account, the system stores their credentials and assigns a default permission role. During registration, the system presents a CAPTCHA challenge to verify the user is human.
2.	When a user performs any action (search, view, download), the system logs the action with a timestamp and user ID.
3.	When a user attempts to access a restricted resource, the system checks their role permissions and denies the request if unauthorized, logging the failed attempt.
4.	When a user's activity exceeds defined thresholds (e.g., too many downloads or failed access attempts in a short period), the system automatically flags the account and may apply a temporary restriction (lockout, CAPTCHA re-verification, or reduced permissions).
5.	When activity is flagged, the system sends a notification to repository administrators with details of the incident.
6.	An administrator reviews the flagged activity on a security dashboard and decides whether to restore access, extend the restriction, or permanently ban the account.

**Edge Cases** 
1.	What if an admin accidentally locks out a legitimate user?
2.	What if a flagged user is actually innocent?
3.	What happens if the admin is unavailable when an alert fires?
4.	What if a malicious user creates multiple accounts to get around rate limits?

------------------------------------------------------------------------

## Final Note for the Assignment

These descriptions provide a starting point based on the user stories,
as the CSE 583 lecture slide suggests. The **primary tasks** are
grounded in the stated user needs, while several **operational
workflows** are proposed sequences that the group should validate and
refine.

Pay particular attention to **UC-02, UC-04, UC-08, UC-13, and UC-14**.
These describe important system-wide qualities or responsibilities, but
they may need to be broken down into more specific use cases or
documented separately as functional and nonfunctional requirements.

This structure should help the group discuss each use case consistently,
identify missing requirements, and decide which interactions belong in
the initial prototype.
