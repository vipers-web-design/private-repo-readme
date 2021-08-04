# feedverse.net
 
There is a reference to `config.inc.php` file that is missing in the repo. That holds:
- The DB connection
- API keys
- SEO Text

## Todo
### Authentication
- Login
  - 2FA

### Newsfeed
- Show when someone unfriends you

### Messages
- Private message system (and notifications)

### Family
- Family posts, news and event planning
- The geneology tree

### Settings
- Change Password
- other recommendations

### General
- User search / autocomplete
- Edit / Delete / Report status updates and comments
- Allow images to be uploaded --- need to get AWS S3
- Premium subscription (subscribers will be ad-free)
  - If you sign up within the first 60 days of launch and subscribe before the site is ~2 months old: US$1/month
  - If you sign up within the first 60 days of launch and subscribe after the site is 2 months and before 3 months old: US$2.50/month
  - If you sign up after the site is 2 months and and subscribe within the first 30 days of registration: US$2.50/month
  - If you sign up after the site is 2 months old and wait over a month to subscribe: US$5/month

## Finished
### Authentication
- Register
  - activate
- Sign In
- Reset password process

### Newsfeed
- Birthday;
  - Shows friends when it is their birthday
  - 1-click wish friends a Happy Birthday (need to rework, currently only works on large screens)
- Pending requests
  - New friends
  - Accept someone's "Feedverse official" request if you're dating them

### Profile
- Can request, cancel request, and block people
- "About" Section
  - Update bio
  - select hometown
  - update both 'religious' and 'political' views
  - Can tag your partner / spouse, have to be friends first
- Shows list of friends

### Public
- Define filters (only can set age and the 'reverse filter' -> enabled by default)
  - shows your friend's PUBLIC posts in the "Public" feed

### Post
- Marks wall post and any reactions as "seen" when coming to this page

### Profile Views
- Shows you who've visited your profile (needs to change the layout)
  - If viewer is invisible (currently admin, eventually subscribers), they won't show up if they visit
  - Will show "new" on the first load of the page, a simple refresh will mark them as old

### Stats
- Shows how many statuses wrote
- Shows wall posts you wrote and recieved
- Shows how many likes you gave and received
- Shows how many comments you've written and gotten

### Settings
- Change name
- Turn invisible (currently admin only, soon will be subscriber only)
- Made a mistake blocking someone, you can unblock them

### General
- Time localization, for the most part
- Post statuses / Post to another user's wall
- "Friend Request" system operational (add, remove, cancel, block, unblock)
  - Finished "block" logic
- Notifications
  - Get notified when someone;
  - writes on your wall,
  - comments,
  - likes
- Can 'star' people's statuses
- Able to comment on statuses
  - if comment textarea is empty, "comment" button is disabled to prevent submitting without text
- Can see which friends are online on the right side
- Finished notify status poster about a new like- post status comment
- Legal pages, gotta be transparent -- suck it Facebook

## Enhance
### Profile
- Update the rest of the "About" section
  - Edit current city
  - Geneology tagging
- Privacy

### Public
- Filter form

### Post
- Mark comments as "seen" when you are reading a specific post thead

### General
- Responsiveness

## Addons
### General
- Mentions (status/wallposts ... maybe comments) ... and notifications
- Hashtag 

### Business / Like / Fan pages
### Group pages

-----------------------
# Credits & Resources
- All my friends - Thank you for believing in me and being patient with the slow development while I had very frequent doctors appointments and frequiently ended up in the hospital.
- [MDBootstrap](https://mdbootstrap.com/) - The layout, responsiveness, some functionality framework.
- [PHPMailer](https://github.com/PHPMailer/PHPMailer) - What makes sending emails possible.
