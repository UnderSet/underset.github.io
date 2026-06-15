---
title: GitHub Pages crash course
---

*Note:* Guide only applies to as is on GitHub.com, and only at time of writing. If you're on Enterprise Cloud/Enterprise Server...this may not help you.

*Note 2:* Guide does not cover Pages with Actions.

How to set up a GitHub Pages site quickly, basically.

Send any feedback to my email or submit an Issue.

***Guide is a heavy work in progress.***

## Prerequisites
- A GitHub account and experience using GitHub
- Some Git experience
    - Technically not strictly necessary but it'll be quite a bit more painful than if you do

## Setting up a GitHub Pages site
1. Create a new repository
    - What you name your repository is important - if it's *anything other than `<your name>.github.io`*, it'll be placed under `<your name>.github.io/<repository name>`
    - **Unless you have a GitHub paid subscription, set this repository public!** Pages for private repositories require a paid subscription.
    - Tick the box to create a README file. This will automatically make a branch for you. You'll need a branch.
        - *Tip for later:* This will show in place of an index.md/index.html file if you don't have that automatically on Pages. *This does not apply to stock Jekyll unless you set it up manually.*
    - Technically not required unless you literally have 0 repositories, but makes following this guide easier.
2. Enable Pages
    - Go to *Settings* > *Pages*, select *Branch*, and select `main` (or whatever you set your default branch as). Click *Save*.
        - *Don't* alter *Source* unless you know your way around GitHub Actions.
    - Once you enable Pages you may also want to add a link to your site's details on the main page's sidebar for easy navigation.
        - Right hand side on *Code* tab (main page) > cogwheel beside *About* > *Use your GitHub Pages website* (***do not enable*** if you already configured a site for this repository!), click *Save changes*, and you're done.
3. Nope, no third step, you're done!