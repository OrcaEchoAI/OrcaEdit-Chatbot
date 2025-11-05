# Privacy Policy for Orcarina

**Orcarina** is a Google Slides™ add-on developed by **OrcaEcho.ai**. It provides an AI assistant directly within the Slides™ interface to help users brainstorm ideas, refine text, and enhance presentation content.

---

### 🧠 Information Handling

Orcarina respects your privacy and limits all data access to what’s strictly necessary for providing its core functionality. The add-on requests the following Google OAuth scopes:

| Scope | Purpose |
|-------|----------|
| `https://www.googleapis.com/auth/script.external_request` | Allows the add-on to securely send HTTPS requests to OrcaEcho’s backend (e.g., `orcaecho-engine` API) to process AI responses. |
| `https://www.googleapis.com/auth/script.container.ui` | Enables the add-on to create and display custom user interfaces such as chatboxes, sidebars, and dialogs directly within Google Slides™. This scope is required for interactive in-app communication between the user and the AI assistant. |
| `https://www.googleapis.com/auth/drive.file` | Grants the add-on permission to view and manage *only the specific files* you open or create using Orcarina. It cannot access any other files in your Google Drive™. |
| `https://www.googleapis.com/auth/presentations.currentonly` | Lets the add-on read and modify the *currently open presentation only* to analyze or generate slide content. |
| `https://www.googleapis.com/auth/script.locale` | Reads your language and locale settings to adapt the add-on’s interface. |
| `https://www.googleapis.com/auth/userinfo.email` | Retrieves your Google Account email address for session identification and user-specific functionality. |
| `https://www.googleapis.com/auth/userinfo.profile` | Accesses your public Google profile name and avatar to personalize your in-app experience. |

---

### 📊 Data Collection and Usage

- The add-on processes **only** data relevant to your active Google Slides™ session.  
- Slide text and structure are analyzed temporarily to generate or enhance presentation content when you explicitly invoke AI features.  
- Messages you type into the chat panel are transmitted securely via HTTPS to OrcaEcho’s backend for AI processing using **Google Gemini™** models.  
- No data is used for advertising, analytics, or AI model training.

---

### 🔐 Data Storage and Protection

- Orcarina does **not** permanently store Google user data.  
- Any temporary data processed by the backend is deleted immediately after generating a response.  
- All communications between the add-on, Google APIs, and the OrcaEcho backend occur over encrypted HTTPS connections.  
- User credentials and authorization tokens are managed entirely by Google OAuth and are not stored by Orcarina.

---

### 🤝 Data Sharing

- Orcarina does **not** sell, share, or disclose user data to third parties.  
- Data is transmitted only between Google APIs and OrcaEcho’s secure backend to fulfill your requests.

---

### 🗑️ Data Retention and Deletion

- No personal or presentation data is retained after processing.  
- You may revoke Orcarina’s access at any time via your [Google Account Permissions page](https://myaccount.google.com/permissions).

---

### 🤖 Use of Google Gemini

- AI responses are powered by the **Gemini API via Google Cloud™**.  
- In accordance with Google Cloud™ data privacy terms, customer data is **not used for model training** unless explicitly opted in by the user or organization.  
- End users maintain full control of their Google Account data-usage settings.

---

### 📬 Contact

For any questions, feedback, or privacy concerns, please contact:  
**support@orcaecho.ai**

---

[← Back to Home](./index.md) • [View Terms of Service](./terms.md)

---

### ™ Trademark Attribution
Google Slides™, Google Drive™, Google Gemini™, Google Cloud™, and Google Workspace Marketplace™ are trademarks of Google LLC.
