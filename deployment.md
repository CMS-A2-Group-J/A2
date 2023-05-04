# Deployment Workflow

- Staging site
  - For staging site, we require admin/user to use `localhost` as staging site.
- Live site
  - Our live server is at: https://baizonnlearning.click

## Project management
Tools we are using:
- [GitHub Projects](https://github.com/orgs/CMS-A2-Group-J/projects/1)
  - For porject management, we create a new iteration every week, then add and update tasks to indicate development progess.
- [Discord](https://discord.gg/82SSbSvv)
  - We are using discord for all group communication activities, including daily standup, collaboration works, and sharing resource materials.

## Version control
- GitHub
  - For all php files (theme etc.), use this [repo](https://github.com/cMS-A2-Group-J/a2) to store.
- Backup plugin & backup policy
  - Everyday, admins need to create backup at `live server` using [All-in-one WP Migration](https://wordpress.org/plugins/all-in-one-wp-migration/), download backup file name it as `backup-YYYY-MM-DD`.
  - Retention policy: all backup files must keep for 30 days before deletion.

## Testing
Before update or add any content on WordPress webiste, admins or authors will need to read and follow the rules stated below.

### General Rules
Steps to follow to add/update content:
1. Create backup at `live server` using [All-in-one WP Migration](https://wordpress.org/plugins/all-in-one-wp-migration/), and download backup file (**backup-old**).
2. Import **backup-old** into `localhost`, to set up localhost as `staging site`.
3. Test new content and make sure there are no conflict. After everything tested out, create a new backup file at localhost (**backup-new**).
4. Import **backup-new** into `live server` to migrate new content. Keep the **backup-old** for 30 days until deletion.

### Update Pages
There are five pages on our wordpress website, here are decriptions of how to make update on those pages:

#### Home
TODO: how to update home page ...
#### About
TODO: how to update about page ...
#### Post
TODO: how to update post page ...
#### Schedule
For schedule site, we are using plugin [Timetable and Event Schedule](https://fr.wordpress.org/plugins/mp-timetable/) to create timetable. In WordPress admin page, go to plugin timetable

<img src="images/timetable.png" width="100px"/>

week days from Monday to Sunday are set as `Columns`. If user wishes to change timetable, edit `Events` to add or update course on timetable.

To update price table on courses, straightly edit tables in WordPress schedule page.

#### Registration
TODO: how to update registration page ...

## Automation
TODO: research and add this part ...