# How To Contribute to the Github Repository

### Getting Collaborator Access

Once you're ready to contribute to the github repository, <a href="mailto:dfmcmurray@gmail.com?subject=[la-homeless-data] Collaborator Access Request">send Donovan McMurray an email</a> to request collaborator access. Then you will get a confirmation email. After you click the invitation link in the email, you'll have access to add and edit content.

### Adding a Post

First, ensure that you've selected the gh-pages branch.

![Ensure that the gh-pages branch is selected](https://raw.githubusercontent.com/dfmcmurray/la-homeless-data/gh-pages/img/how-to-contribute/gh-pages-selection.png)

Then, go into the `_posts` directory. All of the files in this directory will get listed on the home page in reverse chronological order (just like any other blog). You can click on a current file to edit it. If you want create a new post, click the "Create new file" link. 

From here, you can add the name for this file. The format of the post file names should be the date followed by the post name. The extension is md (short for markdown). For example, if you want to add a post on June 21, 2016 with the name "Homelessness on the Westside", then your file should be named `2016-06-21-homelessness-on-the-westside.md`.

In the larger text area, you can add the content of your post. The formatting of this file should be markdown (here's a [getting started guide](http://kramdown.gettalong.org/quickref.html)). If you need help getting your post into this format, you can ask someone [from our group](http://dfmcmurray.github.io/la-homeless-data/about/) to help you. There is a convenient preview feature that will help you as you add things to this file, as well. Furthermore, your post must have some configuration information at the top. This information is used to display your post. See the following example configuration: 

```
---
layout: post
title:  "Example Post 1"
date:   2016-06-16
author: "Donovan McMurray"
blurb: "This post explores certain aspects about homelessness in Los Angeles."
thumbnail: bar.png
---
```

The `layout` field should always be set as `post`, but the other fields should be updated for your specific post. The `thumbnail` field should be an image file that exists in the `img` directory (located at the top-level of the repository).

Finally, before you click the "Commit new file" button, you should add a message so that everyone will know what changes you made. There are two fields to enter this message. The first textbox should have a short summary, and additional information can go in the larger text area. Also, make sure that "Commit directly to the `gh-pages` branch" option is selected. At that point, you can click "Commit new file" to publish your post. Keep in mind that it might take a few minutes for the new post to show up on the website.

### Adding a New Top-Level Page

To start out, our website only has 3 top-level pages: "Home", "About", and "Data". If you'd like to add an additional top-level page, you just need to add a `.md` file to the top-level directory. As long as this file has the proper configuration at the top of the file, it will automatically get added to the navigation bar at the top of the website. Here's an example of the top-level page configuration:

```
---
layout: page
title: About
permalink: /about/
---
```

### Custom Requests

If you need something more customized to be done, you need to <a href="mailto:dfmcmurray@gmail.com?subject=[la-homeless-data] Website Feature Request">send Donovan McMurray an email</a>. 