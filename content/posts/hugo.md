---
author: "Junote"
title: "hugo"
date: "2024-05-02"
lastmod: "2024-05-02"
tags: ["hugo"]
ShowToc: true
math: true
ShowBreadCrumbs: true
---



## How to use this template

1. Click the `Use this template` button above. Create a new repo from this template. Rename it to `<your_repo_name>`. **Don't forget to check the box `Include all branches`.**
2. Change the `baseURL` in `config.yml` to your site's URL. e.g. `https://<your_github_id>.github.io/<your_repo_name>`
3. Open GitHub Pages in your repo's `Settings -> Pages -> Source: Deploy from a branch -> Branch: gh_pages -> Folder: /root -> Save`.
4. (\*Optional)Create a markdown file to write your content in `content` folder.
5. (\*Optional)Commit and push your changes to your repo.
6. Bingo! Your site is live at `https://<your_github_id>.github.io/<your_repo_name>`

Notice: If you meet the problem like `remote: Permission to xxx denied to github-actions[bot].` when you push your changes, you need to give the permission to the `github-actions[bot]` in your repo's by following the steps below: `Settings -> Actions -> General -> Workflow permissions -> Read and write permissions -> Save`.

## images
> post文件夹下直接存放 Markdown 文件，图片存储在static/images文件夹下，引用时![图名](/images/image.png), 但是github不支持这种相对路径，失败。





## reference
1. https://github.com/awesome-actions-template/hugo-papermod-template
2. https://www.bilibili.com/video/BV1ua411B7WH/?spm_id_from=333.880.my_history.page.click&vd_source=a4e3e223ffde8596a5f54a5af60f891d
3. https://theplaybook.dev/docs/deploy-hugo-to-github-pages/

