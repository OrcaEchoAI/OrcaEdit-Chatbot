# Privacy Policy for Orcarina

**Orcarina** is a Google Slides™ add-on developed by **OrcaEcho.ai**. It provides an AI assistant directly within the Slides™ interface to help users brainstorm ideas, refine text, and enhance presentation content.

---

### 🧠 Information Handling

Orcarina respects your privacy and limits all data access to what’s strictly necessary for providing its core functionality. The add-on requests the following Google OAuth scopes:

| Scope | Purpose |
|-------|----------|
| `https://www.googleapis.com/auth/script.external_request` | Allows the add-on to securely send HTTPS requests to OrcaEcho’s backend (e.g., `orcaecho-engine` API) to process AI responses. |
| `https://www.googleapis.com/auth/script.container.ui` | Enables the add-on to create and display custom user interfaces such as chatboxes, sidebars, and dialogs directly within Google Slides™. Required for interactive in-product communication. |
| `https://www.googleapis.com/auth/drive.file` | Grants the add-on permission to view and manage *only the specific files* you open or create using Orcarina. It cannot access any other files in your Google Drive™. |
| `https://www.googleapis.com/auth/presentations.currentonly` | Lets the add-on read and modify the *currently open presentation only* to analyze or generate slide content. |
| `https://www.googleapis.com/auth/script.locale` | Reads your language and locale settings to adapt the add-on’s interface. |
| `https://www.googleapis.com/auth/userinfo.email` | Retrieves your Google Account email address for secure session identification. |
| `https://www.googleapis.com/auth/userinfo.profile` | Accesses your public Google profile name and avatar to personalize your in-app experience. |

**Types of Data Accessed**  
All data accessed by Orcarina is strictly limited to the **currently opened Google Slides™ presentation**. The add-on does not access any other files in your Google Drive™.

- Slide text, speaker notes, and layout metadata from the current presentation  
- Structure and formatting information for the current presentation  
- File ID, file name, and related Drive metadata for the current file only  
- User email, display name, avatar, language, and locale  
- UI-related metadata required to render chat panels and dialogs  
- Text you explicitly enter into the chat panel

---

### 📊 Data Collection and Usage

- The add-on processes **only** data relevant to your active Google Slides™ session.  
- Slide text and structure are analyzed **temporarily** when you invoke AI features to generate, refine, or format content.  
- Drive file metadata is used solely to identify and update the open presentation.  
- Messages typed into the chat panel are transmitted securely to OrcaEcho’s backend for processing with the **Google Gemini™ API**.  
- Your email and profile information are used only for session association, access control, and maintaining secure operation.  
- Locale information is used to provide appropriately localized output.

No data is used for advertising, analytics, behavioral profiling, or any unrelated purpose.

---

### 🔐 Data Storage and Protection

- Orcarina does **not** permanently store any Google user data.  
- All slide content, metadata, and chat messages are processed **in memory only** and deleted immediately after generating a response.  
- No presentation content, Drive files, or user profile information is retained on OrcaEcho systems.  
- OAuth tokens and credentials are handled entirely by Google OAuth and are **never stored** by Orcarina.  
- All communication between the add-on, Google APIs, and the OrcaEcho backend uses encrypted HTTPS.

---

### 🤝 Data Sharing

- Orcarina does **not** sell, share, or disclose Google user data to any third parties.  
- Limited data (such as user-submitted chat messages or slide content excerpts) is transmitted only to:
  - Google APIs  
  - OrcaEcho’s secure backend  
  - Google Gemini API  

Google Gemini processes data only to generate responses.  
**Google does not use this data to train or improve generalized AI or ML models.**

---

### 🗑️ Data Retention and Deletion

- Orcarina retains **no** personal data or presentation data after processing.  
- All processed data is immediately discarded once a response is produced.  
- You may revoke Orcarina’s access at any time via your [Google Account Permissions page](https://myaccount.google.com/permissions).

---

### 🤖 Use of Google Gemini

- AI responses are powered by the **Gemini API via Google Cloud™**.  
- In accordance with Google Cloud’s data privacy terms, customer-submitted data is **not used for model training** unless explicitly opted in by the user or organization.  
- Users maintain full control over their Google Account data-usage settings.

---

### 📬 Contact

For any questions, feedback, or privacy concerns, please contact:  
**support@orcaecho.ai**

---

[← Back to Home](./index.md) • [View Terms of Service](./terms.md)

---

### ™ Trademark Attribution
Google Slides™, Google Drive™, Google Gemini™, Google Cloud™, and Google Workspace Marketplace™ are trademarks of Google LLC.
