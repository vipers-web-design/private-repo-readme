# feedverse.net

## Table of Contents

##### Pages / Everyone
<table>
  <tbody>
    <tr>
      <td>
        <a href="#authentication">Authentication</a>
      </td>
      <td>
        <a href="#newsfeed">Newsfeed</a>
      </td>
      <td>
        <a href="#profile">Profile</a>
      </td>
      <td>
        <a href="#profile-views">Profile Views</a>
      </td>
      <td>
        <a href="#post">Post</a>
      </td>
      <td>
        <a href="#messages">Messages</a>
      </td>
    </tr>
    <tr>
      <td>
        <a href="#family">Family</a>
      </td>
      <td>
        <a href="#subscription">Subscription</a>
      </td>
      <td>
        <a href="#settings">Settings</a>
      </td>
      <td>
        <a href="#general">General</a>
      </td>
      <td>
        <a href="#addons">Addons</a>
      </td>
      <td></td>
    </tr>
  </tbody>
</table>

##### Roles
<table>
  <tbody>
    <tr>
      <td>
        <a href="#scambaiters">Scambaiters</a>
      </td>
      <td>
        <a href="#police">Police</a>
      </td>
      <td>
        <a href="#mod--admin-controls">Mod / Admin Controls</a>
      </td>
    </tr>
  </tbody>
</table>

##### Misc
<table>
  <tbody>
    <tr>
      <td>
        <a href="#resources">Resources</a>
      </td>
      <td>
        <a href="#credits">Credits</a>
      </td>
    </tr>
  </tbody>
</table>

## Summary
<a href="https://builtwith.com/feedverse.net" target="_blank">feedverse.net Technology Profile - Builtwith.com</a> - Show off the technology I am using to create Feedverse.

#### My goals:
> 1. Privacy
> 2. Security
> 3. Simple & easy to use as possible

![image](https://user-images.githubusercontent.com/8532498/128605918-c1d713e7-cca4-4bc9-86f5-aff3a6bc7827.png)

## Checklist
#### Legend
<table>
  <thead>
    <tr>
      <th>Finished</th>
      <th>Enhance</th>
      <th>Todo</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>:heavy_check_mark:</td>
      <td>:white_check_mark:</td>
      <td>:pencil:</td>
    </tr>
  </tbody>
</table>

### Authentication
- :heavy_check_mark: Register / Account Activation
- :heavy_check_mark: Sign In / Sign Out
- :heavy_check_mark: Reset Password
- :pencil: 2FA

### Newsfeed
- Profile Box
  - :heavy_check_mark: Shows selected profile pic
  - :heavy_check_mark: Link to the "Photos" tab on the Profile page
  - :white_check_mark: Shows current Versebucks amount, with links to Buy & Exchange (both launch modal windows)
    - added a Versebucks coin image to the "Buy" modal
  - :heavy_check_mark: Button-link to subscription form
- Actions (aka Notifications)
  - :white_check_mark: New Friend Request Count
  - :white_check_mark: New Profile Views Count
  - :white_check_mark: New Message Count
  - :white_check_mark: New Question Count
  - :white_check_mark: New Comment Count
- Birthdays
  - :white_check_mark: Card/Panel will only show when it is a friend's birthday
- Friend Manager
  - :pencil: Shows when someone accepted your friend request
  - :white_check_mark: Shows when you've been unfriended
- Online Friends
  - :white_check_mark: Shows friends who are online at the time of page load
- Stats
  - :white_check_mark: Shows how many statuses wrote (1)
  - :white_check_mark: Shows how many "questions" you wrote and received (2)
  - :white_check_mark: Shows how many likes you gave and received (2)
  - :white_check_mark: Shows how many comments you've written and gotten (2)
  - :white_check_mark: Shows how many conversations you've started & received (2)
  - :white_check_mark: Shows how many messages you've written (2)
- The newsfeeds
  - Tab features:
    - The first three tabs auto-save in DB
    - The first three tabs have a "refresh" link/button to check if new posts are made
  - Tab: Near Me
    - :heavy_check_mark: Has a "Filter form" summary (gender list, age range, location)
    - Define filters
      - :heavy_check_mark: Age
      - :heavy_check_mark: Relationship status
      - :heavy_check_mark: Gender
      - :white_check_mark: Location
      - VIP Filters
        - :heavy_check_mark: Ethnicity
        - :pencil: Orientation
        - :white_check_mark: "Reverse" Filter (meaning: anyone you are <ins>***not***</ins> searching for won't be able to find you)
    - :heavy_check_mark: Shows the 10 most recent posts made
  - Tab: Friends
    - :heavy_check_mark: Shows the 10 most recent posts made
  - Tab: Everyone
    - :heavy_check_mark: Shows the 10 most recent posts made
    - :heavy_check_mark: Based on age, regardless of location on Earth. If `your < 18` only shows posts from 13 - 17 years old; if `your >= 18`, then show posts 18 - 125 years old.
  - Tab: My Chatter
    - Shows the 10 most recent posts made by you

### Profile
- :heavy_check_mark: Profile pic, nice and large
- :heavy_check_mark: Friends List
- :heavy_check_mark: Can "request" and "cancel" friend requests, also can block people
- :pencil: Initialize/continue the conversation from the profile
- :pencil: Ability to allow the user to design what their profile looks like, like MySpace

#### "Timeline" section
- Shows the 10 most recent posts made by or answered by you

#### "About" section
##### "Basic Info"
- :heavy_check_mark: Can edit your "about me"/bio
- :heavy_check_mark: Set/change pronouns
- :white_check_mark: Add/Edit/Delete Employment History
  - Add / Edit;
    - Fields; Company, Position, City/Town, Description, Dates
- :white_check_mark: Add/Edit/Delete College History
  - Add / Edit;
    - Fields; School, Dates, Graduated(?), Description, Concentration (3?), Attended [College / Graduate School], Degree
- :white_check_mark: Add/Edit/Delete High School
  - Add / Edit;
    - Fields; High School, Dates, Graduated(?), Description

##### "Contact Info"
- :heavy_check_mark: Change current city
- :heavy_check_mark: Website and other links (current list below)
  - "Portfolio" -> open to interpretation
  - Twitter
  - Twitch
  - LinkedIn
  - GitHub
  - Reddit

##### "Personal Info"
- :white_check_mark: Set relationship status
- :heavy_check_mark: Set political alignment
- :heavy_check_mark: Set religious background
- :heavy_check_mark: Set Hometown
- :heavy_check_mark: Add/Edit favorite quotes
- :pencil: Geneology tagging

#### "Photos" section
- :white_check_mark: Picture display grid (okay for now)
- :heavy_check_mark: Change profile picture, don't allow gif images
- :heavy_check_mark: Delete single picture

#### "Videos" section (hidden for now)
- :pencil: ... I'm deciding if I want to allow video uploads.

### Post
- Marks the following as "seen" when reading the single post
  - :white_check_mark: Received wall posts
  - :white_check_mark: Received reactions
  - :pencil: Received comments

### Messages
- Private message system
  - :heavy_check_mark: Creates new thread
  - :white_check_mark: Notifies when you have unread messages
  - :heavy_check_mark: Displays if & when your message gets read
  - :pencil: Conversation search
  - :pencil: Ajax fetch
  - :pencil: Ajax reply

### Family
- :white_check_mark: Family posts, news and event planning
- :pencil: The genealogy tree

### Profile Views
- :heavy_check_mark: Lists the people who've visited your profile (needs to change the layout)

### Subscription
- :white_check_mark: The entire page
- :white_check_mark: Rates: USD$6.95/month
  - Notice: Fees are subject to change, current subscribers will get notified via email - I will try to send a notice at least 60 days in advance.
- Perks:
  - :pencil: Filter to preferred ethnicity ("Near Me" > Filter form)
  - :pencil: Filter to preferred orientation ("Near Me" > Filter form)
  - :white_check_mark: "Reverse Filter" ("Near Me" > Filter form)
  - :pencil: Create multiple style presets (Profile)
  - :heavy_check_mark: Set nickname (Profile > About)
  - :pencil: Set orientation (Profile > About)
  - :heavy_check_mark: Set ethnicity (Profile > About)
  - :heavy_check_mark: Stealth setting (Settings > Privacy Tab)
  - :white_check_mark: Ad-free (General)
  - :heavy_check_mark: Daily Login Bonus; 30% more Versebucks (General)
  - ... and more, TBD

### Settings
##### (Following Facebook's flow)
- :heavy_check_mark: Deep linked tabs to become shareable if you need to show where a setting is located
- "General" tab
  - :heavy_check_mark: Change name
  - :white_check_mark: Change email
- "Security & Login" tab
  - :heavy_check_mark: Change Password
- "Privacy" tab
  - :white_check_mark: Privacy
  - :heavy_check_mark: Limit who can send you messages
- "Profile" / "Profile & Tagging" tab
  - :heavy_check_mark: Limit who can post on your wall
- "Blocking" tab
  - :heavy_check_mark: Can unblock people

### General
- :white_check_mark: Responsiveness
- :white_check_mark: Ads
- :white_check_mark: Time localization
- :white_check_mark: Card / Panel contains:
  - Shows your most recent status that doesn't have any pictures included in the post
  - A WYSIWYG editor to share status updates
  - **_**ONLY IF YOU ARE VIEWING YOUR OWN PROFILE**_** Collapsable panel containing file-input field
    - Limit of 2 images to be added
    - Accepts file types; JPEG/JPG, PNG, and GIF. The JPEG/JPG and PNG get converted to WEBP during the upload process
  - The share button, disabled by default until the WYSIWYG or file input contains something, will (should) return to the default state if both fields are empty.
- :heavy_check_mark: "Friend Request" system operational (add, remove, cancel, block, unblock)
- Notifications
  - Get notified when someone;
    - :white_check_mark: writes on your wall,
    - :white_check_mark: comments,
    - :white_check_mark: likes
    - :white_check_mark: Sends you a message
- :heavy_check_mark: Can 'like' people's statuses & people's Q&A
- :heavy_check_mark: Able to comment on statuses
- :heavy_check_mark: Can see which friends are online on the right side
- :heavy_check_mark: Finished notifying status poster about a new like- post status comment
- :heavy_check_mark: Legal pages, gotta be transparent
- :heavy_check_mark: Collapse comments on posts on load if there are more than 2 comments
- :white_check_mark: When someone turns 18, update their age filters automatically
- :pencil: Proper error messages if a specific action fails
- :white_check_mark: User search / autocomplete
- :white_check_mark: Add a "Load More" infinite scroll on the newsfeeds and private messages
- Post/status updates & comment actions
  - POSTS / STATUS UPDATES
    - :heavy_check_mark: Edit
    - :heavy_check_mark: Delete
    - :white_check_mark: Report
  - COMMENTS
    - :white_check_mark: Edit
    - :white_check_mark: Delete
    - :white_check_mark: Report
- Image upload where necessary
  - :heavy_check_mark: Status Update (max 2 images, allow - jpeg/jpg, png, gif... jpeg/jpg & png images converted to webp on upload)
  - :pencil: Comment picture (max 1, allows the same as the status update, will also convert to webp)
  - :pencil: Messages picture (max 2? allows the same as the status update, will also convert to webp)\
  Note: I wanted to allow a maximum of 5 images, but uploading 3+ images to Cloudinary will work—but the API or something will return Code 500 "Internal Server Error"—which might be because of the Free Plan.
- :pencil: Create phone apps for Android and iOS

### Addons
- #### Post
  - Mentions (status/wall posts ... maybe comments) ... and notifications
  - Hashtag

- #### Business / Like / Fan pages

- #### Group pages

### Scambaiters
- :pencil: Ability to create persona's profiles through their own

### Police
- :pencil: ?

### Mod / Admin Controls
- :pencil: Everything
- :pencil: Add symbol to Admin role to prevent impersonation.

---

## Resources
- <a href="https://cloudinary.com/documentation/cloudinary_references" target="_blank">Programamble Media API References | Cloudinary</a> - To upload images to Cloudinary
- <a href="https://fontawesome.com/" target="_blank">FontAwesome</a> - For all the cool icons
- <a href="https://mdbootstrap.com/" target="_blank">MDBootstrap</a> - The quick layout, basic responsiveness, and some functionality
- <a href="https://github.com/stripe/stripe-php" target="_blank">stripe-php</a> - Payment gateway for subscription
- <a href="https://www.mailersend.com/" target="_blank">Email Sending Service - MailerSend</a> - What makes sending emails possible
- <a href="https://github.com/dr5hn/countries-states-cities-database" target="_blank">dr5hn &#8725; countries-states-cities-database</a> - The world database I am using

## Credits
- All my friends - Thank you for being awesome and believing in me.
