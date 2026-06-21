# SharedHub Starter

This is a third GitHub/Cloudflare Pages site for shared co-owned characters.

## Folder structure

Upload these files exactly like this:

/index.html
/style.css
/characters/index.html

Optional images:

/images/placeholder.png
/images/sharedhub-icon.png

## Required Notion setup

Use the same shared character database already used by StarHub and LunaHub.

The character database needs a property:

Hub

Set co-owned/shared characters to:

Shared

Existing values can be:

StarHub
LunaHub
Shared

## What this site does

- Fetches from:
  https://charahub.crysthigpen.workers.dev/characters

- Shows only characters where:
  Hub = Shared

- Character profiles load from:
  https://charahub.crysthigpen.workers.dev/character/{slug}

- World tags link to the master world pages:
  https://characterhub.pages.dev/world/?slug=...

## Deploy steps

1. Create a new GitHub repo, for example:
   sharedhub

2. Upload these files.

3. Create a new Cloudflare Pages project connected to that repo.

4. Set build command to blank.

5. Set output directory to:
   /

6. Deploy.

7. In Notion, set co-owned characters to:
   Hub = Shared

8. Visit your new Pages URL.

## Recommended site names

SharedHub
Starbrew SharedHub
StarSundae x LunaBrew SharedHub
