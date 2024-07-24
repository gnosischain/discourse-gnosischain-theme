# GnosisChain Theme

Official Discourse theme for GnosisChain.

## Configuration

### Discourse Settings

Following setting changes are required for this theme to render properly:

- `Admin Settings > Basic Setup > top menu` needs to be set to **category, latest, new, unread, top**
- `Admin Settings > Basic Setup > desktop category page style` needs to be set to **Boxes with Subcategories**

### Discourse Search Banner

In the options for the `discourse-search-banner` theme component, the following changes are required for this theme to render properly, set them in `Admin > Customize > Components > discourse-search-banner`:

- `show-on` options needs to be set to **homepage**
- `background image` can be set as per your requirement

### Discourse Showcased Categories

In the options for the `Showcased Categories` theme component, following changes are required for this theme to render properly:

- select the `feed one category` and `feed two category` as per your requirement
- fill in the `feed one title` and `feed two title` as per your requirement
- recommended value for `max list length` is `3`.


## Installation

Installing the package is quite simple, first of all create a tar.gc package containing the project:

```
tar --exclude .DS_Store --exclude .github --exclude .git -zcvf gc.tar.gz discourse-gnosischain-theme
```

In your administration panel, go to `Customize > Theme > Install`, choose the package and click on install.

You can then choose to enable the theme by default for all users or let them choose which one to use.
