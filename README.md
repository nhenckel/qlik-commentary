# Qlik Commentary Extension  

**Qlik Commentary Extension** is an open-source extension that enables users to add, manage, and display comments directly within Qlik Sense dashboards. This extension supports both fixed panel discussions and floating comment bubbles tied to specific objects, allowing for easy collaboration and context-aware discussions.

## Features  
✅ **Fixed Panel Mode** – Centralized discussions for a single-threaded comment view.  
✅ **Floating Bubbles** – Attach comments to specific Qlik objects for contextual feedback.  
✅ **Apply Selections** – Restore dashboard filters as they were when the comment was created.  
✅ **User Profiles & Avatars** – Supports user profile links and custom avatar templates.  
✅ **Edit & Delete** – Users can edit their comments within a configurable time window.  
✅ **Threaded Replies** – Keep discussions organized with nested replies.  
✅ **Selection Persistence** – Optionally save and restore Qlik selections with comments.  

## Usage  
1. Drag and drop the **Qlik Commentary Extension** onto your dashboard.  
2. Configure the extension via the property panel:  
   - Choose between **Fixed Panel** or **Floating Bubbles** mode.  
   - Set the **thread ID** for fixed panel discussions.  
   - Configure **bubble locations** for object-based comments.  
   - Enable/disable the **Apply Selections** button.  
3. Start adding and managing comments!  

## Configuration  
### Global Settings  
- **Apply Selections Button**: Allows users to restore dashboard filters saved with comments.  
- **Edit Window Days**: Set how long a user can edit their comments after posting.  
- **Filter Days**: Display only comments created within the specified timeframe.  
- **User Profile URL**: Hyperlink comment authors to their profile pages.  
- **User Avatar Template**: Define the avatar image URL pattern for users.  

### UI Settings  
- **Mode**: Choose between **Fixed Panel** or **Floating Bubbles** mode.  
- **Fixed Panel Settings**: Define the `threadId` used to group comments.  
- **Bubble Configuration**: Assign `qId` and `threadId` to display comment bubbles on specific objects.  

## License  
See the full [LICENSE](LICENSE) file for more details.  

## Contributions  
Contributions are welcome! Feel free to submit pull requests or report issues.  

---

🚀 Enjoy using the **Qlik Commentary Extension** and make your dashboards more interactive! 🚀  
