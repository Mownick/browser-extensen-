
##  Review Extension Permissions and User Feedback

###  Objective

To analyze the permissions granted to each installed browser extension and assess user feedback to identify potential **security or privacy risks**.

---

### 📊 Extension Permissions and Review Summary

| **Extension Name**                               | **Permissions Requested**                                                                           | **Chrome Web Store Rating**  | **User Feedback / Observations**                                                                              | **Action** |
| ------------------------------------------------ | --------------------------------------------------------------------------------------------------- | ---------------------------- | ------------------------------------------------------------------------------------------------------------- | ---------- |
| **Grammarly: AI Writing and Grammar Checker**    | - Read browsing history  <br> - Display notifications  <br> - Read and change all data on all sites | ⭐ 4.5/5 (10M+ users)         | Mostly positive. Some concerns regarding data access due to broad permissions.                                | ✅ Retain   |
| **Adobe Acrobat: PDF Edit, Convert, Sign Tools** | - Read browsing history  <br> - Manage downloads  <br> - Communicate with native applications       | ⭐ 4.2/5 (4M+ users)          | Trusted developer. Permissions align with features. No major complaints.                                      | ✅ Retain   |
| **Online PDF Converter**                         | - Display notifications  <br> - Read and change all data on all sites                               | ⭐ 3.1/5 (10K+ users)         | Reported issues with intrusive behavior, suspicious redirects, and potential adware. Uses suspicious iframes. | ⚠️ Remove  |
| **Google Docs Offline**                          | - Read and change data on docs.google.com and drive.google.com                                      | ⭐ 4.6/5 (9M+ users)          | Official Google extension. Well-rated and widely used.                                                        | ✅ Retain   |
| **Flash Player for the Web**                     | - Read and change all data on all sites                                                             | ⭐ 2.3/5 (Few thousand users) | Obsolete plugin. Users report malware/adware issues. Considered a security risk.                              | ⚠️ Remove  |

---

###  Observations

* **High-permission extensions** (e.g., Grammarly, Adobe Acrobat) are generally safe but should be reviewed periodically due to the sensitive nature of the access they require.
* **Online PDF Converter** and **Flash Player for the Web** raised multiple red flags:

  * Permissions not justified by their claimed functionality.
  * Poor user ratings and reviews citing redirects and potential malicious behavior.
  * Use of deprecated or risky technology (e.g., Flash).

---

###  Conclusion

Based on the permission analysis and user feedback:

* **Retained:**

  * Grammarly
  * Adobe Acrobat
  * Google Docs Offline
* **Removed:**

  * Online PDF Converter
  * Flash Player for the Web

These actions contribute to a more secure and privacy-respecting browsing environment.

---

Let me know if you’d like this turned into a `.csv`, `.md`, or added to your project documentation folder.
