---
headless: true
title: Hugo Comments Test-Site
---

<div align="center">
<img alt="Foto del perfil" class="be6sR" src="https://instagram.fmex10-2.fna.fbcdn.net/v/t51.2885-19/s150x150/141178627_111546030899969_2267140937590127994_n.jpg?tp=1&amp;_nc_ht=instagram.fmex10-2.fna.fbcdn.net&amp;_nc_ohc=ijbGsMnA1FgAX-5PhrA&amp;oh=d17dd2960abf5e49cec619def9e6b13f&amp;oe=606F9AA0">
<br><br>
<h1 id="johan">Johan</h1>
</div>



# Johan

Detailed description: https://ttntm.me/blog/static-blog-comments-hugo/

GitHub: https://github.com/ttntm/hugo-comments

## Description

The comments posted are handled by [Netlify Forms](https://www.netlify.com/docs/form-handling/) and get processed there according to this flowchart: https://bpm.wiki/diagram/Static-comments-with-Netlify-94

During the build process, the comments are obtained from Netlify Forms via their API and put into a `comments.json` file by Gulp. In order to make this work on `localhost` environments, don't forget that you'll need an `.env` file within the project directory that stores the necessary `Form ID` and `API Token` for your own Netlify setup.

Based on: https://css-tricks.com/jamstack-comments/