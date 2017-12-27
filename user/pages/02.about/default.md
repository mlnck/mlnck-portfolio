---
title: About
taxonomy:
    category:
        - Page
---

About me,
fonts,
design decisions,
rcscc,
trello board,
ZenHub
Axe,
gravatar

---

# Grav is Running!
## You have installed **Grav** successfully

---
## Notes

- [Summary](http://127.0.0.1:8080/content/content-pages#summary-size-and-separator) to be used as timeline post value
- [Dates](http://127.0.0.1:8080/content/content-pages#finding-other-pages) to be used when constructing timeline maybe?
- &nbsp;
- Make sure to use [title, slug, taxonomy &amp; date](http://127.0.0.1:8080/content/headers)
  - slug for deep linking support
- For homepage: Include [modular](http://127.0.0.1:8080/content/headers#collection-of-modular-children) page(s)
  - [Exactly](http://127.0.0.1:8080/content/modular#modular-pages) what we want to do:
- &nbsp;
- Remember you can make image links:
  - `[![Alt text](/path/to/img.jpg)](http://example.net/)`
- Built in image [helpers](http://127.0.0.1:8080/content/media#actions)
  - And [metafile](http://127.0.0.1:8080/content/media#metafiles) overwrites
- &nbsp;
- [Twig Templates](http://127.0.0.1:8080/themes/theme-basics#templates)
- [Twig Helpers](http://127.0.0.1:8080/themes/twig-filters-functions#monthize)
- Twig has date and timezone methods (see pdf download)
- &nbsp;
- To use the [theme config(s)](http://127.0.0.1:8080/themes/theme-configuration)
- [Find](http://127.0.0.1:8080/themes/theme-vars#find-url) and collection look like they may be really useful
- &nbsp;
- [Logging](http://127.0.0.1:8080/advanced/debugging#logging)
&nbsp;
&nbsp;

&nbsp;

---
---


Congratulations! You have installed the **Base Grav Package** that provides a **simple page** and the default **antimatter** theme to get you started.

!!! If you want a more **full-featured** base install, you should check out [**Skeleton** packages available in the downloads](http://getgrav.org/downloads).

### Find out all about Grav

* Learn about **Grav** by checking out our dedicated [Learn Grav](http://learn.getgrav.org) site.
* Download **plugins**, **themes**, as well as other Grav **skeleton** packages from the [Grav Downloads](http://getgrav.org/downloads) page.
* Check out our [Grav Development Blog](http://getgrav.org/blog) to find out the latest goings on in the Grav-verse.

### Edit this Page

To edit this page, simply navigate to the folder you installed **Grav** into, and then browse to the `user/pages/01.home` folder and open the `default.md` file in your [editor of choice](http://learn.getgrav.org/basics/requirements).  You will see the content of this page in [Markdown format](http://learn.getgrav.org/content/markdown).

### Create a New Page

Creating a new page is a simple affair in **Grav**.  Simply follow these simple steps:

1. Navigate to your pages folder: `user/pages/` and create a new folder.  In this example, we will use [explicit default ordering](http://learn.getgrav.org/content/content-pages) and call the folder `02.mypage`.
2. Launch your text editor and paste in the following sample code:

        ---
        title: My New Page
        ---
        # My New Page!

        This is the body of **my new page** and I can easily use _Markdown_ syntax here.

3. Save this file in the `user/pages/02.mypage/` folder as `default.md`. This will tell **Grav** to render the page using the **default** template.
4. That is it! Reload your browser to see your new page in the menu.

! NOTE: The page will automatically show up in the Menu after the "Home" menu item. If you wish to change the name that shows up in the Menu, simple add: `menu: My Page` between the dashes in the page content. This is called the YAML front matter, and it is where you configure page-specific options.