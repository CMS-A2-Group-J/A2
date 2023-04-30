# Site

Provides instructions on to maintain/update website.

## Questions that need to answer
- How would people who take over add new content (could be a page or a post)?
  - In what category
  - What plugins they need to be familiar about
- Detailed explanation on how to maintain, organize, and update this WP website.

## Site Customization
### Site title
For the purpose of SEO -- increasing our rank on search engine, the title of our site should relate to treading topics.

After doing some research, we picked a few hot keywords (in Singapore) from 'python tutor', 'math tutor', 'science tutor', 'homework help', etc. 

*source: [Google Keyword Planner](https://ads.google.com/intl/en_sg/home/tools/keyword-planner/)

![SEO keyword](./images/keyword.png)

### Icon
icon image: `Center_Logo_1`

![Center Logo 1](./images/Centre_Logo_1.jpg)

### Header
The Header section is composited of three parts: icon, menu, and social links. 

#### Header Icon
Header [site icon](###icon) (Center_logo_1) height: 81px;

#### Header Menu
Menu order: Home, About, Posts, Schedule, Registration 

### Popup
Using plugin [hustle](https://wordpress.org/plugins/wordpress-popup/) to create promotion popup. The popup is set to only shows on the 'Home' page, and the reset interval is set to every 3 minutes.

Popup Background Image:

<img src="./images/popup_bg.gif" width="300px" />

## To update and create new post/page
1. For content creation, use accounts associated with one of those four roles: 'Author', 'Contributor', 'Editor', 'Subscriber'. Unless absolutely necessary, **do not** use 'Admin' account for creating new content.

2. Starting on the `Staging Site`, create a backup file using [All-in-one WP Migration](https://wordpress.org/plugins/all-in-one-wp-migration/) before you start any editing. To make sure a snapshot is always available in case of emergency.

3. After adding content, preview to check for errors, you should create a new backup file on `Staging Site`, then upload the backup file to transfer content into `Live Site`.

