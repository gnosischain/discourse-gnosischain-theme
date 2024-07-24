# Gnosis Chain Discourse Theme

Custom theme used in the [GnosisDAO Forum](https://forum.gnosis.io/).

## Installation

Installing the package is quite simple, first of all create a tar.gc package containing the project:

```
tar --exclude .DS_Store --exclude .github --exclude .git --exclude old_versions -zcvf gc.tar.gz discourse-gnosischain-theme
```

In your administration panel, go to `Customize > Theme > Install`, choose the package and click on install.

You can then choose to enable the theme by default for all users or let them choose which one to use.

## Components

- https://github.com/jordanvidrine/discourse-category-group-boxes
- https://github.com/discourse/discourse-search-banner
- https://github.com/discourse/discourse-clickable-topic


## Setup

In the admin panel go to the settings page and set the following properties.

### Fixed category positions (fixed_category_positions) 

Must be turned on (URL `/admin/site_settings/category/all_results?filter=fixed_category_positions`).


### Desktop category page style

Must be set to `categories and latest topics` (URL `/admin/site_settings/category/basic?filter=category`).

### Category style

Must be set to `bullet`.

### Top menu

Must be set to the following:
- categories
- latest
- top
- unread
- new


### Categories

For Gnosis DAO forum only, go to /categories click on tools and then on "Reorder categories":

- General 0
- Governance 1
- Treasury 2
- Knowledge Base 3
- Delegate communication 4
- Announcements 5
- Staff 6
- Internall staff 7
- Uncategorized 8


### Dark mode

Operating systems and browsers might enforce the dark mode automatically.

In order for Discourse to pick up a color palette of your choice for the dark mode, go to `settings > Basic Setup > default dark mode color scheme ID` and choose the right value for it.


## Resources
- [Beginner's guide to using Discourse Themes](https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966)
- [Developer's guide to Discourse Themes](https://meta.discourse.org/t/developer-s-guide-to-discourse-themes/93648)
