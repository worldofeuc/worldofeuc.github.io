---
layout: page
description: Blogging with the World of EUC
---

-  Table of Contents
{:toc .large-only}

![Blogging]({{site.baseurl}}/assets/img/blog-writing.jpg)

# Want to write a blog?

Blogging is an important part of our community space. It is fair to say that none of us are where we are without the knowledge sharing of others. Blogs typically are the foundation for this.

Not everyone wants to host or manage their own site, and fair enough. We provide a home for those with content, and nowhere to put it, or for those that just want to get started out.

# Our Platform and Methodology

Our entire site is based on [Github Pages](https://pages.github.com/) and they [Hydejack](https://hydejack.com/) theme. This means that any posting requires some structure and standardisation in [markdown](https://www.markdownguide.org/). This is not hard, but might be a bit of a learning curve the first time.

To submit a new post, there are a few things you will need to do:

1.  Write the the content in markdown. This will be your `post`.
2.  Provide the images associated with your post with a decent naming standard. Please be cognizant of the usual copyright considerations. [Unsplash](https://unsplash.com/) is your friend.
3.  Submit a [Github pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests) with details. If you are not comfortable doing that, then reach out within Slack. One of us will help you.

# Tools For Writing

Moving to markdown and associated Github Pages handling means you need/should get familiar with a few of tools:

1.  A Markdown editor. You can use [VSCode](https://code.visualstudio.com/) or you can use something like [Markdown Monster](https://markdownmonster.west-wind.com/). Both offer a nice way of writing, and previewing your content. A great guide on how you can format things is found here: [How to Write with Hydejack](https://hydejack.com/docs/writing/)
2.  A spell checker. You can use a [VSCode extension](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker) for this, or, you can copy into word or whatever your tool of choice is and spell check there. Basic spell checking is expected.
3.  Structure your post nicely. Intro, Detail, Summary. Use sub headings to help build a nice Table of Contents
4.  Category management. We use `featured Categories` to help with indexing and grouping posts. This will be by both technology, and by author. Have a think about what categories your post falls under.

The beauty of this platform, is that you can always reference someone elses post structure to get you started, including associated front matter, which is what controls your post within the site.

# Author Profiles

As this is a shared content site, there are a few things we (the admins) will do to make sure posts are tagged and associated with the right folk:

1.  We will create a `featured category` for you, as an author, so that we can group any posts you write together.
2.  We will create an `author` within the main site configuration. This allows us to tag your poste with the appropriate `Author` front matter value. This makes sure that a post by Ray, is a post by Ray and not James. The following information can help with understanding the [author logic](https://hydejack.com/docs/config/#adding-an-author). Include an image for yourself.
  
# Ex CUGC Content

If the content was previously posted on the CUGC website, we will tag this with a `CUGC` Featured Category to ensure that content can be grouped together and found. Please let us know if the content was previously on CUGC, or, if you are at the point of writing your own post front matter, include the `CUGC` category value.

# Submission Standards

For your post file, please submit a post in the `community_drafts` folder in a format of `your-post-name.md`. If you want to retain the existing posting date, please provide us the file in the format of `YYY-MM-DD-your-post-name.md`. If this is a net new post, we will include the post date for you at the time of merge/release.

For your images, please create an image folder under the `assets\img\blog` folder that matches your post name. For example `assets\img\blog\your-post-name`. Put your images in there.

When referencing images in markdown, please use the following format:

```
[![Image Summary]({{site.baseurl}}/assets/img/your-post-name/ImageName.jpg)]({{site.baseurl}}/assets/img/your-post-name/ImageName.jpg)
```

Ensure you alter:

-  The `Image Summary`
-  The `your-post-name`
-  The `ImageName`

For new `Featured Categories`, please make a note in your pull request of what you would like, or if comfortable, create a new category under the `_featured_categories` folder in the site root and include it in your pull request.

# An Example Post

There is a bit to take in. Here is an [example post](https://worldofeuc.com/a-draft-post-used-for-how-to-blog) where we walk through a few components with exampels. You can always look at the raw markdown in github to understand what we are doing.

# How do I see posts before they land on Github

Given this is such a simple deployment, you can render your content locally by a number of different mechanisms. Over on the island of convicts, there is an example of how you could [undertake this adventure](https://jkindon.com/hydejack-github-pages-docker-containers/).
