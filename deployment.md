# Deployment Workflow

## Project management
Things we need:
- Staging site
- Live site

Tools we are using:
- GitHub Projects (instead of Trello)
- Discord (instead of Slacks)

For our wordpress website, we will need 5 pages:
- Home
- About
- Registration
- Contact
- Services

> *You only need to put your **custom theme folder** or **wp-content folder** under git (don't include core WordPress files). It should be kept up-to-date throughout the project. **Every** team member must commit to this repository so that there is evidence of each member's contribution (see a2 pdf project management).*

Things we could use:
- Stand-up meetings (preferably daily, at least every other day), see lecture 06 slides page 3

## Version control
- See if we need to use Git as version control for WP files.
  - This may require to set up git in AWS Lightsail
- Backup plugin & backup policy


## Testing and automation
- Do research on CI/CD tools for WP

## Update page
### Home
how to update home page ...
### About
### Post
### Schedule
For schedule site, we are using plugin [Timetable and Event Schedule](https://fr.wordpress.org/plugins/mp-timetable/) to create timetable. In WordPress admin page, go to plugin timetable

<img src="images/timetable.png" width="100px"/>

week days from Monday to Sunday are set as `Columns`. If user wishes to change timetable, edit `Events` to add or update course on timetable.

### Registration

