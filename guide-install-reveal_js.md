## Howto Slides on Reveal.js

Ref: https://medium.com/@marcus_baw/using-reveal-js-a74b30e4065b

- create a new GitHub repo with the name you want the presentation to be known as (other online Git-integrated source control platforms are available)
- git clone this repo to a suitable local directory, which should create a subdirectory of the same name as your presentation.
- git clone https://github.com/hakimel/reveal.js.git
- Start adding content to your slides. The Reveal.js documentation is very simple, and very helpful. I won’t duplicate it here.
- Make local commits (eg git commit -am "my commit message") as required. Usually I just work in the master branch, and make commits irresponsibly infrequently. So sue me.
- Push to GitHub
- In the GitHub settings for that repo, you need to enable GitHub Pages and select the master branch.
- A few minutes later (there’s always a slight lag for the first time page build) your reveal.js presentation is up at http://[yourusername].github.io/[reponame]
