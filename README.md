# SourceForge

SourceForge (https://sourceforge.net/) is one of the oldest and most widely used open source software hosting and distribution platforms. Founded in 1999, it provides developers and open source projects with version control hosting (Git and SVN), release management, bug and ticket tracking, discussion forums, wikis, and file download mirrors. SourceForge hosts hundreds of thousands of open source projects and serves as a distribution hub for software downloads worldwide. The platform is built on Apache Allura, an open source project hosting platform that SourceForge originally developed and later donated to the Apache Software Foundation.

**URL:** [https://sourceforge.net/](https://sourceforge.net/)

## APIs

### Allura API

SourceForge exposes a REST API through the Apache Allura platform it is built on. The Allura API allows developers to programmatically access and manage project resources hosted on SourceForge.

**Base URL:** `https://sourceforge.net/rest`

**Documentation:** [https://sourceforge.net/p/forge/documentation/Allura%20API/](https://sourceforge.net/p/forge/documentation/Allura%20API/)

**Authentication:** OAuth 1.0a is required for write operations. Many read endpoints are publicly accessible without authentication. OAuth credentials can be obtained from a user's account settings.

**Key capabilities:**

- Retrieve project metadata, tools, and neighborhood information
- Access and manage Git and SVN repository details
- Read and create tickets in project bug/feature trackers
- Interact with discussion forums and threads
- Read and update wiki pages
- Access user profile and account information
- List project files and download releases

**Response format:** JSON

**Example endpoints:**

- `GET /rest/p/{project}/` — Project summary and tools
- `GET /rest/p/{project}/tickets/` — List project tickets
- `GET /rest/p/{project}/tickets/{ticket_num}/` — Get a specific ticket
- `POST /rest/p/{project}/tickets/new` — Create a new ticket (auth required)
- `GET /rest/p/{project}/wiki/` — List wiki pages
- `GET /rest/u/{username}/profile/` — User profile
