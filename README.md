# GnosisDAO Forum Theme

Custom theme used in the [GnosisDAO Forum](https://forum.gnosis.io/).

## Installation

Installing the package is quite simple, first of all create a tar.gc package containing the project:

```
tar --exclude .DS_Store --exclude .github --exclude .git -zcvf gc.tar.gz discourse-gnosischain-theme
```

In your administration panel, go to `Customize > Theme > Install`, choose the package and click on install.

You can then choose to enable the theme by default for all users or let them choose which one to use.

## Components
- https://github.com/discourse/discourse-color-scheme-toggle
- https://github.com/discourse/discourse-search-banner
- https://github.com/discourse/discourse-gifs


## Setup

Fixed category positions (fixed_category_positions) must be checked (URL `/admin/site_settings/category/all_results?filter=fixed_category_positions`).


Desktop category page style set to `categories and latest topics` ( URL `/admin/site_settings/category/basic?filter=category`).

Category style set to `bullet`.

`Top menu` must be set to the following:
- categories
- latest
- top
- unread
- new

Go to /categories click on tools and then on "Reorder categories":
- General 0
- Governance 1
- Treasury 2
- Knowledge Base 3
- Delegate communication 4
- Announcements 5
- Staff 6
- Internall staff 7
- Uncategorized 8


## Resources
- [Beginner's guide to using Discourse Themes](https://meta.discourse.org/t/beginners-guide-to-using-discourse-themes/91966)
- [Developer's guide to Discourse Themes](https://meta.discourse.org/t/developer-s-guide-to-discourse-themes/93648)