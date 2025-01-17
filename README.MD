# README

## Contribute to the FIT Resources Page

### How to add a post 
1. [Fork](https://docs.github.com/en/github/getting-started-with-github/quickstart/fork-a-repo) this NOAA FIT [resources repo](https://github.com/noaa-fisheries-integrated-toolbox/resources)
2. Create a blog post [markdown file](https://guides.github.com/features/mastering-markdown/) and add it to the [posts folder](https://github.com/noaa-fisheries-integrated-toolbox/resources/tree/master/_posts) in your forked repo
3. Label the `.md` file `YYYY-MM-DD-post-name.md`
4. Create a header and add a category and tags (to search by). Here's an example header: 

```
---
title: "Contributing to R tools in the Toolbox"
excerpt: "R tools"
date: 2021-06-11
toc: true
categories:
  - onboarding
tags:
  - R
---
```

> See [contributing.md](https://raw.githubusercontent.com/noaa-fisheries-integrated-toolbox/resources/master/_posts/2021-06-11-contributing.md) for an example of the `.md` file code.
6. Add your post to the table of contents by adding it to the `navigation.yml` [located here](https://github.com/noaa-fisheries-integrated-toolbox/resources/blob/master/_data/navigation.yml).
7. In the `navigation.yml`, choose the header it lies under and add a title for your new page.

```
      - title: "~ Contributing to the Toolbox"
        url: /onboarding/contributing    
```
> The url will be `/category/post-name` depending on the category indicated in the `.md` file and the name of the `.md` file after the date in the posts folder
7. Once a post is created in the post folder and the `navigation.yml` file is updated, [create a pull request](https://docs.github.com/en/github/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) so we can merge the changes and update the FIT site.
 
### How to embed a video in a `.md` page

#### Using a link from YouTube or Vimeo:
1. Click `share`
2. Click `embed link`
3. Copy and Paste the embed link into the `.md` file where you want the video to appear

Example code from YouTube embed link:
```
<figure class="video_container">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/A7qDN2oYSxc" frameborder="0" allowfullscreen="true"> </iframe>
</figure>
```
#### Embedding an `.mp4` file

To embed an `.mp4` file directly onto a github page, you'll need to use [Git Large File Storage](https://docs.github.com/en/repositories/working-with-files/managing-large-files/about-git-large-file-storage) in order to add the video to a repository. The GitHub docs linked below will walk you through this. 

1. [Install Git Large File Storage](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage)
2. [Configure Git LFS](https://docs.github.com/en/repositories/working-with-files/managing-large-files/configuring-git-large-file-storage)
