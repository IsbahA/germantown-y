---
title: Create a Repository
stub: create
section: repository
section_order: 1
---

{:.py-4 .mt-4 #create}
***

## 1. Create a New Repository

First, set up a repository on GitHub for your CollectionBuilder project.
Each repository on GitHub is basically a folder for storing and tracking the code for a project.

{% capture newrepo %}
1. Login on [GitHub](https://github.com)
2. Go to the repository corresponding to the type you are using: 
    - **GH** - <https://github.com/CollectionBuilder/collectionbuilder-gh>
    - **CONTENTdm (CDM)** - <https://github.com/CollectionBuilder/collectionbuilder-contentdm> 
    - **SA** - *Currently under development--coming soon!*
3. Click the green "Use This Template" button.    
4. This brings you to a "Create a new repository" form. Follow these steps:
    - **Enter your new repository name**. Use a lowercase name without spaces or odd characters. We often append `_source` or `_draft` to our projects to keep track of the status. If you are using GH, this name will become part of your site URL, so think through how it will look as a link.
    - Most users should choose "Public" repository. If you are hosting on GitHub Pages it *must* be public unless you upgrade to a paid account.
    - Leave the "Include all branches" option **Unchecked**! (you do not want all branches, only the main/master branch)
    - Click on the green button "**Create repository from template**." This will take you to your new repository.
{% endcapture %}
{% include bootstrap/card.md text=newrepo %}