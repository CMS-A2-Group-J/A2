# Deployment Workflow
## Stage & Live
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
1. For content creation, use accounts associated with one of those four roles: 'Author', 'Contributor', 'Editor', 'Subscriber'. Unless absolutely necessary, **do not** use 'Admin' account for creating new content.
2. Create backup at `live server` using [All-in-one WP Migration](https://wordpress.org/plugins/all-in-one-wp-migration/), and download backup file (**backup-old**).
3. Import **backup-old** into `localhost`, to set up localhost as `staging site`.
4. Test new content and make sure there are no conflict. After everything tested out, create a new backup file at localhost (**backup-new**).
5. Import **backup-new** into `live se plugin.ver` to migrate new content. Keep the **backup-old** for 30 days until deletion.


## Automation
TODO: research and add this part ...