---
layout: blogsy
---

So I was just reading a blog post titled [*How GitHub Writes Blog Posts*](http://zachholman.com/posts/how-github-writes-blog-posts/) and it pointed to a help page discussing GitHub workflows that are [entirely within the browser](https://github.com/blog/1557-github-flow-in-the-browser). 


 I have been thinking about blogging and writing workflows that leverage github, but are also not too complicated for non-technical users. With this 100% in-browser workflow, I think it might be possible to work and collaborate on writing projects with folks who are not text-editor/command-line junkies. I am a lover of plain-text as a format for writing, but not everyone shares that love. I work and collaborate with many different kinds of people with a variety of writing and working styles. It is my hope that I might be able to convert some folks to a GitHub + Plaintext/Markdown style of working using the in-browser workflows.

I'm currently writing this post on my personal website, which has a couple of blogs hanging off of it. None of them are particularly well integrated because my personal website is a big fat mess. I am perfectly fine with that for now. In December of 2012 GitHub [added a feature for creating new files from the browser](https://github.com/blog/1327-creating-files-on-github) and that I think opens up the possibility for using GitHub as a plain-text/markdown based content management system. 

The next step is developing some materials for teaching a workshop or short course on using GitHub as a collaboration tool. GitHub is not just for code, it is now a full fledged groupware system. I don't necessarily see GitHub replacing Sharepoint in the near future, but I do think for some workflows GitHub is a more attractive option. One place where GitHub falls down as a CMS is in uploading files. [GitHub removed the feature whereby you could upload files](https://github.com/blog/1302-goodbye-uploads), but you can [still upload images to a repository's wiki](https://help.github.com/articles/adding-images-to-wikis/). 

I guess any asset files, like images, documents, or other binary blobs should be uploaded to an external content delivery network and linked to from the repository. This is where complexity begins to creep into the scenario. It isn't easy to upload files to Amazon S3 and for systems were it is easy, like Dropbox or Box, serving content via public links is [frowned upon.](https://www.dropbox.com/en/help/45) Also, getting a direct link can be a pain from Dropbox, although it looks pretty easy for [paid Box.net users](https://support.box.com/hc/en-us/articles/200519908-Direct-Linking-to-a-File)

Stay tuned as I continue to refine the workflow!
