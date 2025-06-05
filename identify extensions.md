

##  Open Browser’s Extension/Add-ons Manager

###  Objective

Access the browser’s extension manager to view all installed extensions and gather detailed information such as status, permissions, source, and version for a comprehensive security review.

---

###  Detailed Steps

1. **Open Google Chrome**
   Launch the Chrome browser on your system.

2. **Access the Extension Manager**

   * Click the **three-dot menu** at the top-right corner of the browser.
   * Navigate to:
     **More tools → Extensions**
   * **OR** directly open:
     `chrome://extensions/`

3. **View Installed Extensions**
   On the Extensions page, you will see a list of all installed browser extensions. Each extension shows:

   * **Name**
   * **Version**
   * **Description**
   * **Permissions granted**
   * **Status toggle (On/Off)**
   * **Remove button**
   * **Details link** for more in-depth information

4. **Check Each Extension’s Details**
   Click **"Details"** under each extension to review:

   * **Permissions**
   * **Site Access** (All sites / Specific sites / On click)
   * **Allow in Incognito** (if enabled)
   * **File URL Access**
   * **Size, version, and install source**
   * **Service worker status** (active/inactive)

5. **Document Installed Extensions**
   For each extension, note the following:

   * **Extension Name**
   * **Version**
   * **Size**
   * **Permissions granted**
   * **Install Source** (Chrome Web Store or third-party)
   * **Service Worker Status** (active/inactive)

---

###  Summary of Extensions Found

| **Extension Name**       | **Version** | **Size** | **Source**            |
| ------------------------ | ----------- | -------- | --------------------- |
| Grammarly                | 14.1238.0   | 65.4 MB  | Chrome Web Store      |
| Adobe Acrobat            | 25.5.4.0    | 7.6 MB   | Third-party installer |
| Online PDF Converter     | 3.1.1       | < 1 MB   | Chrome Web Store      |
| Google Docs Offline      | 1.92.1      | < 1 MB   | Installed by default  |
| Flash Player for the Web | 0.2.2       | 25.9 MB  | Chrome Web Store      |

---

###  Notes & Initial Observations

* **Grammarly** and **Adobe Acrobat** are from trusted sources but have **extensive permissions**, which should be monitored.
* **Online PDF Converter** showed:

  * Multiple suspicious iframe redirects
  * Inactive service workers
  * Marked as **suspicious**
* **Flash Player for the Web** uses **deprecated technology**, has **risky permissions**, and has a history of **malicious behavior**—**flagged for removal**.

---

