# feedverse.net
[feedverse.net Techology Profile - Builtwith.com](https://builtwith.com/feedverse.net) - Show off the technology I am using to create Feedverse.

#### My goals:
> 1) Privacy
> 2) Security
> 3) Simple & easy to use as possible

![image](https://user-images.githubusercontent.com/8532498/128605918-c1d713e7-cca4-4bc9-86f5-aff3a6bc7827.png)

Right now the domain rests on a Shared Hosting server, with my business website a couple of sites I made for friends. This plan will not support the traffic for a site of this genre.\
I've created a Donation button to seek help with the costs, [Donate With PayPal](https://www.paypal.com/donate?token=Zt3BwCxjNdiJKflAXIQCpf0Q9etoJ0gWt0Wse2eViZP0CsC_z8pWYr5G3yrCclwyXFbbbbT4fiZZisFQ)\
If you want to know when I launch;
- Please 'Like' my Facebook pages [Feedverse.net - Facebook](https://www.facebook.com/feedverse/) and [Viper's Web Design - Facebook](https://www.facebook.com/viperswebdesign)
- Please follow my business Twitter account at [Viper's Web Design - Twitter](https://twitter.com/viperswebdesign)

## Todo
### Authentication
- 2FA

### Newsfeed
- Show when someone unfriends you

### Profile
- "About" section
  - Geneology tagging

### Messages
- Private message system (and notifications)

### Family
- Family posts, news and event planning
- The geneology tree

### Pictures
- Just everything still, won't work on this until I get S3 set up.

### Settings
- Privacy
- Need ideas....

### General
- Proper error messages if queries fail
- User search / autocomplete
- Feed infinate scroll
- Edit / Delete / Report status updates and comments
- Allow images to be uploaded --- need to get AWS S3
- Premium subscription (subscribers will be ad-free)
  - If you sign up within the first 60 days of launch and subscribe before the site is ~2 months old: US$1/month
  - If you sign up within the first 60 days of launch and subscribe after the site is 2 months and before 3 months old: US$2.50/month
  - If you sign up after the site is 2 months and and subscribe within the first 30 days of registration: US$2.50/month
  - If you sign up after the site is 2 months old and wait over a month to subscribe: US$5/month
- Create phone apps for Android and iOS

### Admin Controls
- Everything in one convenient place for admins and moderators

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
- Define filters
  - shows your friend's PUBLIC posts in the "Public" feed
- "Reverse Filter" (currently admin, will also be subscriber only)
  - How the reverse filter will work, say you set your age preference between 22 - 31. Accounts between those ages will show for you, while everyone from 18 - 125 years old can find you, if you are in their preferred age range... like a standard filter form. IF you are a subscriber and have this enabled (which will be by default), accounts between those ages that you defined can only see you if you are in their age range.

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
- Deep linked tabs to become shareable if you need to show were a setting is located
- Change name
- Turn invisible (currently admin only, soon will be subscriber only)
- Change Password
- Made a mistake blocking someone, you can unblock them

### General
- Ads
- Time localization
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
- Legal pages, gotta be transparent
  - [Privacy Policy](https://www.feedverse.net/privacy-policy)
  - [Terms of Use](https://www.feedverse.net/terms-of-use)

## Addons
### General
- Mentions (status/wallposts ... maybe comments) ... and notifications
- Hashtag 

#### Business / Like / Fan pages
#### Group pages

-----------------------
## Resources
- [AWS SDK for PHP](https://docs.aws.amazon.com/sdk-for-php/v3/developer-guide/welcome.html) - To upload images to Amazon S3
- [FontAwesome](https://fontawesome.com/) - For all the cool icons
- [MDBootstrap](https://mdbootstrap.com/) - The layout, responsiveness, some functionality framework.
- [PHPMailer](https://github.com/PHPMailer/PHPMailer) - What makes sending emails possible.

## Credits
- All my friends - Thank you for being awesome and believing in me.
- Thank you to both [@Ravavyr](https://github.com/Ravavyr) and [@OpenSourcerer](https://github.com/OpenSourcerer) for being a soundboard and helping me become a better PHP developer that I am today.
