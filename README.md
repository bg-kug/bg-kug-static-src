# Bulgarian Kotlin Usergroup

Static website for the bulgarian kotlin usergroup, built using [hexo.io](https://hexo.io/)

### Dev dependencies:

- [Node.js](https://nodejs.org/en/)
- [Git](https://git-scm.com/)

```
npm install -g hexo-cli
git clone https://github.com/bg-kug/bg-kug-static-src.git
cd bg-kug-static-src
npm install
```
### Run locally

`hexo server`

Starts local webserver with generated files at `http://localhost:4000`

### Create a new post

`hexo new <title>`

Creates a new post with `title YYYY-MM-DD-title.md` in `/source/_posts/`

### Deploy

```
hexo clean
hexo deploy
```