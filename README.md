# 🏦 Noticeboard-CityBank

A web-based digital notice board system developed using **Classic ASP**. This application allows administrators to manage official announcements, providing a streamlined way to create, edit, and display notices for an organization like CityBank.

## 🛠️ Tech Stack

* **Language:** Classic ASP (Active Server Pages)
* **Scripting:** VBScript / JScript
* **Server:** Internet Information Services (IIS)
* **Frontend:** HTML/CSS (Embedded)

## 🚀 Key Features

* **Notice Management**: Add new notices via `noticeboardform.asp`.
* **Notice Editing**: Update existing announcements using `editnoticeboard.asp`.
* **Automated Validation**: Integrated logic to ensure notices are correctly formatted (`validateNoticeBoard.asp`, `validateEditNoticeBoard.asp`).
* **Data Retrieval**: Fetch and display current notices through `retrieveNoticeBoard.asp`.
* **Summary View**: A quick overview of all active notices with `summaryNoticeView.asp`.

## 📥 Installation & Setup

Since this project uses Classic ASP, it must be hosted on a Windows environment with **IIS** enabled.

1.  **Clone the Repository**:
    ```bash
    git clone [https://github.com/shakil642/Noticeboard-CityBank.git](https://github.com/shakil642/Noticeboard-CityBank.git)
    ```

2.  **Move to Web Root**:
    Copy the project folder into your IIS webroot (typically `C:\inetpub\wwwroot`).

3.  **Enable Classic ASP in IIS**:
    * Open **Control Panel** > **Programs and Features** > **Turn Windows features on or off**.
    * Navigate to **Internet Information Services** > **World Wide Web Services** > **Application Development Features**.
    * Ensure **ASP** is checked.

4.  **Database Connection**:
    * Ensure database (MS SQL Server) is configured, and connection strings are updated in the relevant `.asp` files.

5.  **Run**:
    Open browser and navigate to `http://localhost/Noticeboard-CityBank/noticeboardform.asp`.

## 📂 Project Structure

* `noticeboardform.asp`: The entry form for creating new notices.
* `retrieveNoticeBoard.asp`: Script for fetching notices from the backend.
* `validateNoticeBoard.asp`: Handles backend validation for submitted data.
* `summaryNoticeView.asp`: A dashboard view for users to see all current notices.

---
**Developed by [Shakil Ahmed](https://github.com/shakil642)**
