## Install

1. Install [Hugo](https://gohugo.io/getting-started/installing/) e.g. `brew install hugo`
2. `git clone https://github.com/eugenesiow/eugenesiow.com.git`
3. `cd eugenesiow.com`
4. Create a `public` folder with the `gh-pages` branch with `git worktree add -B gh-pages public origin/gh-pages`
5. Build the static `public` folder with Hugo and commit the `gh-pages` branch with `./commit-gh-pages-files.sh`
6. Push the `gh-pages` branch to github with `./push-upstream.sh`