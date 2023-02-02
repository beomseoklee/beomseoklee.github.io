---
title: "What would be the better way for GitHub pages?"
date: 2023-02-01
---

GitHub pages supports several [themes](https://pages.github.com/themes/). At first, I chose [Minima](https://github.com/jekyll/minima) which has the most stars among the themes. Then, for me, [Cayman](https://github.com/pages-themes/cayman) was better so I changed the theme to Cayman. However, unlike Minima, Cayman didn't support the pure blog after building it automatically. Maybe I could be wrong, but as that, I changed the theme to Minima again.

Such decision created a lot of commits. Maybe later, I think I need to create a pull request to merge the changes into `main` branch. Before that, I might need to follow [Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) so that I can preview the actual GitHub pages.

Still, there are many things to improve. However, the current way would be better than creating web pages with HTML, CSS, and JavaScript. At the beginning, I thought about using Bootstrap. Then, I thought, 'Maybe I can build a web application with React and upload built files into GitHub repos.' However, I finally chose to use blog like GitHub pages which I am still not satisfied. One day, I may update this one to other ones, but for now, it's enough.
