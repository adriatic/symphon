# Symphony Application Design Project

**[This website](https://adriatic.github.io/symphony-docs/)** is a structured collection of documents describing the details of Project Symphony, depicted below.

<p style="text-align:center">
<img src="https://user-images.githubusercontent.com/2712405/83949611-dc68c780-a7f2-11ea-8950-1ca4a0f5f4b3.png">
Image 1
</p>

Strapi, defined as the leading open-source headless CMS, is 100% Javascript, fully customizable and developer-first. Symphony is a "full-stack application", specifically designed to show Strapi in as many contexts as possible. In contrast with Strapi **tutorials and blogs**, Symphony is a real distributed application utilizing Strapi based back end, combined with many distributed services, demonstrating how to use the information in Strapi Guides, how to write multiple Strapi plugins, how to use some of the key Identity Management Services, etc.

At the moment we envision that Symphony will be a part of the **[Strapi Write for the Community](https://strapi.io/write-for-the-community)** effort.

---

This site is generated with **[mkdocs](https://www.mkdocs.org/)** tool. To maintain it be aware that all persistent information consists of:

- **mkdocs.yml** file at https://github.com/adriatic/symphony-docs/blob/master/mkdocs.yml
- markdown files in the docs folder: https://github.com/adriatic/symphony-docs/tree/master/docs

Typical update process consists of updating or adding markdown files in the [docs](https://github.com/adriatic/symphony-docs/tree/master/docs) folder and making the correspondent changes to the [mkdocs.yml](https://github.com/adriatic/symphony-docs/blob/master/mkdocs.yml) file.

To make your changes persistent, commit and push the changes from the root folder (in my case the folder at `c:\work\symphony\symphony-docs`). In order to regenerate the site, run the command `mkdocs gh-deploy` from the same (root) folder. The updated host site is in the `gh-pages` branch - `https://github.com/adriatic/symphony-docs/tree/gh-pages`