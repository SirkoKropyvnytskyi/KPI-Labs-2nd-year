## List of Requirements

### Functional Requirements
| ID | Requirement | Description |
|:---|:---|:---|
| **FR-01** | **Search Manga** | The system must provide users with the ability to search for manga by title name. |
| **FR-02** | **Content Filtering** | The system must allow filtering search results or the catalog by genres. |
| **FR-03** | **Read Chapters** | The system must provide an interface for viewing the pages of a selected manga chapter. |
| **FR-04** | **Page Loading** | The system must automatically load page images from the server when a chapter is opened. |
| **FR-05** | **Authentication** | The system must allow new users to register and existing users to log in to their personal account. |
| **FR-06** | **Save Progress** | The system must automatically save the last read page number for authorized users. |
| **FR-07** | **Bookmark Management** | Authorized users must be able to add specific chapters to their personal bookmarks. |
| **FR-08** | **Library Management** | Authorized users must be able to add manga to lists (e.g., "Reading", "Plan to Read"). |
| **FR-09** | **Content Upload** | The administrator must be able to upload new manga titles and new chapters to them. |
| **FR-10** | **Content Management** | The administrator must be able to edit manga information or remove chapters/titles from the system. |

### Non-functional Requirements
| ID | Requirement | Description |
|:---|:---|:---|
| **NFR-01** | **Performance** | The full load time of a manga page image must not exceed 2 seconds over a 4G connection. |
| **NFR-02** | **Security** | User passwords must not be stored in plain text; hashing is mandatory. |
| **NFR-03** | **Usability** | The reading interface (Reader UI) must be responsive and display correctly on mobile devices and tablets. |
| **NFR-04** | **Availability** | The system must ensure 99.9% service availability (allowing no more than 43 minutes of downtime per month). |
| **NFR-05** | **Scalability** | The system architecture must support at least 1000 concurrent active readers without speed degradation. |
| **NFR-06** | **Reliability** | In the event of a server failure, no data saved within the last 10 minutes (admin uploads, user reading progress) shall be lost. |