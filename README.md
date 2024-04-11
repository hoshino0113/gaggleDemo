**UWGaggle**

# **Project Description:**

Waterloo can be a lonely place. With assignments, projects, job-searching, many students find it challenging to meet new people who share similar interests. For many students, an unfortunately large portion of their social interaction is with old friends they can't see anymore on a group chat. Introducing UWGaggle: an anonymous messaging app where students are matched with a new group chat based on their interests every week! UWGaggle allows users to get to know those in their groups, and to easily share their contact information with those that they enjoy talking to.

# **Features:**

- Anonymous Chat: Your contact information is kept anonymous until you choose to share it with others
- Contact Sharing: If you enjoy talking to somebody, click on the share contact button to give them your social media handles
- Interest Matching: Enter in your interests when you sign up, and our matching algorithm will put you in a group with similar interests

# **Team Members:**

Alan Zhong
Josh Chen
Joshua Kim
Michael He

# **Release Notes:**

**UwGaggle 0.1**

- Designed firestore structuring for groups, users, messages
- Designed matching algorithm for putting users into groups based on interests
- Got sign-up page UI running
- Created Figma designs for login and email verification  
  **UwGaggle 0.2**
- Created forgot password screen design
- Added firebase integration for sending messages, user authorization, editing/creating profiles with interests and contacts  
  **UwGaggle 0.3**
- Got auth working end-to-end
- Created interest interface with login
- Created firebase integration for receiving messages  
  **UwGaggle 0.4**
- Chat now works end-to-end
- Create matchings cloud function is operational, matchings are made based on interests using a custom algorithm
- Interests are now entered in the sign-up page
- Profile can now be edited after account creation
- UI overhaul: all menus have been given a blue and white theme, general aesthetic clean-up
- View group: brings you to a list of your group members, clicking on any of them brings you to their profile
- Clicking on other users in your group brings you to their profile  
  Contact Sharing:
- Contact info (discord, instagram) is hidden to others until you go to their profile and click "share contact"
- If you would like to go back on your decision to share your information, you can click "unshare contact"
