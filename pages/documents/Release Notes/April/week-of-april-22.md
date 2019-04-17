---
pagename: Week of April 22nd
categoryName: Release notes
subCategoryName: 2019
indicator: both
subtitle: ''
level3: April
permalink: release-notes-2019-april-week-of-april-22nd.html
isTutorial: false
isNew: false
date: 2019-04-17 10:38:13 +0300
published: false

---
## Enhancements

### New Minimize window icon (CX-286)

<table class="releasenotes"> <thead> <tr class="categoryrow"> <th>Web Messaging</th> <th>Mobile App Messaging</th> <th>SMS</th> <th>Facebook Messenger</th> <th>ABC</th> <th>Line</th> <th>Google RCS</th> <th>Google My Business</th> <th>WhatsApp Business</th> <th>CM</th> <th>Chat</th> </tr> </thead> <tbody> <tr> <td>Yes</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>Yes</td> </tr> </tbody> </table>

An additional style has been added for the minimize window icon. Campaign managers and admin users are able to choose the icon to minimize the window. This is configurable via the engagement window studio under the “title bar” section. This feature is available for Desktop only.

**Dependencies:**

* LE UI 10.7

**To configure the minimize window icon:**

Default icon:

(add screen shots)

## Bugs Fixes

### Welcome message is sent in PCS (CX-320)

<table class="releasenotes"> <thead> <tr class="categoryrow"> <th>Web Messaging</th> <th>Mobile App Messaging</th> <th>SMS</th> <th>Facebook Messenger</th> <th>ABC</th> <th>Line</th> <th>Google RCS</th> <th>Google My Business</th> <th>WhatsApp Business</th> <th>CM</th> <th>Chat</th> </tr> </thead> <tbody> <tr> <td>Yes</td> <td>Yes</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> </tr> </tbody> </table>

When the welcome message is configured for “Every new conversation” and a Post Conversation Survey is configured for the window, the welcome message is displayed after the conversation is closed and before the survey is displayed.

This issue has now been resolved and when the conversation is closed, the welcome message will not be shown when the PCS is configured, even when the welcome message is configured for “Every new conversation”.

**Screenshots**

![](/img/Webex2.png)

### Agent avatar appears next to visitor’s message when visitor sent an image (CX-169)

<table class="releasenotes"> <thead> <tr class="categoryrow"> <th>Web Messaging</th> <th>Mobile App Messaging</th> <th>SMS</th> <th>Facebook Messenger</th> <th>ABC</th> <th>Line</th> <th>Google RCS</th> <th>Google My Business</th> <th>WhatsApp Business</th> <th>CM</th> <th>Chat</th> </tr> </thead> <tbody> <tr> <td>Yes</td> <td>Yes</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> </tr> </tbody> </table>

When a brand is using web messaging and has the agent avatar enabled, the agent avatar appears next to the visitor’s message when the visitor sends an image to the agent.

This issue has now been resolved. The agent avatar should not appear next to the image when a visitor sends an image.

**Screenshots**

**![](https://lh3.googleusercontent.com/qVHhmCiYCkdcg5D_CtPS8gD5xGcyq0EQnvg5bRxB5z1jprP-8a6YPXi_0cv3yPn5HPH7fqTBmQPmsD1gfQJHRt9Yjxt26LvznHMdQSJPrUVLuT8YjSCteEepVhrse31PmLpRaXRs =197x280)**

### “Alt text” on header of engagement window does not disappear even after deleting from settings (CX-194)

<table class="releasenotes"> <thead> <tr class="categoryrow"> <th>Web Messaging</th> <th>Mobile App Messaging</th> <th>SMS</th> <th>Facebook Messenger</th> <th>ABC</th> <th>Line</th> <th>Google RCS</th> <th>Google My Business</th> <th>WhatsApp Business</th> <th>CM</th> <th>Chat</th> </tr> </thead> <tbody> <tr> <td>Yes</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>No</td> <td>Yes</td> </tr> </tbody> </table>

When adding a header image with Alt Text within the engagement window studio configuration, Alt text appears when the visitor hoovers over the header image. However, when you delete “Alt text” within the engagement window studio, “Alt text” still appears on the visitor side when the visitor hoovers over the header image.

This issue has now been resolved. Alt text should not appear when deleted and saved in the engagement window studio.

**Screenshots**

**![](https://lh3.googleusercontent.com/cKSXRn8FyIWQcRTwN61AYfFGIzA6zcFwfmk071BmNWV6JHQYar4aV_B2WE-93HyWaxXbnirtnPuv_14AT6NOIYwT3NHvqAt6YZuWz_E1AoTsJgHBGALx5lGN6xqF1KYNmwTUjZmt =236x335)**

**![](https://lh5.googleusercontent.com/4WgfnwN8Wdm-ezWl8-505ZypVhBxxwdkFJJLJgN7Nmq4saTLgBcPLPsqUTjhgrecNT-cjk_o4j4kmix6_4VfsPYpAzHpcphOcAxuhSN839sCcil_ekceePIvQvYkp8AuPPuFJruH =243x350)**