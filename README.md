# Custom Icon Badges

![stars](https://custom-icon-badges.herokuapp.com/github/stars/DenverCoder1/custom-icon-badges?logo=star)
![issues](https://custom-icon-badges.herokuapp.com/github/issues-raw/DenverCoder1/custom-icon-badges?logo=issue)
![license](https://custom-icon-badges.herokuapp.com/github/license/denvercoder1/custom-icon-badges?logo=repo)

Allows users to more easily use their own icons and logos to [shields.io badges](https://github.com/badges/shields).

This is still a work in progress. I plan to create a demo site to simplify the process.

- [⚡ How to use](#-how-to-use)
- [🖼️ Existing logos](#️-existing-logos)
  - [Octicons](#octicons)
  - [Miscelanious](#miscelanious)
- [➕ Adding a new logo](#-adding-a-new-logo)

## ⚡ How to use

1. Get a badge URL from [shields.io](https://shields.io/).

2. Replace `img.shields.io` with `custom-icon-badges.herokuapp.com`

3. Use any available slug as the logo query parameter.

```md
https://custom-icon-badges.herokuapp.com/badge/play-station-blue.svg?logo=controller
```

Preview:

![img](https://user-images.githubusercontent.com/20955511/126047615-7f47d37f-30af-4feb-b29c-9498422d9c93.png)

## 🖼️ Existing logos

The following are examples of existing icons and logos that are already available.

### Octicons

Currently a subset of [Octicons](https://primer.style/octicons/) are supported:

| Slug       | Example                                                                                  |
| ---------- | ---------------------------------------------------------------------------------------- |
| `issue`    | ![img](https://custom-icon-badges.herokuapp.com/badge/Issue-red.svg?logo=issue)          |
| `fork`     | ![img](https://custom-icon-badges.herokuapp.com/badge/Fork-orange.svg?logo=fork)         |
| `star`     | ![img](https://custom-icon-badges.herokuapp.com/badge/Star-yellow.svg?logo=star)         |
| `commit`   | ![img](https://custom-icon-badges.herokuapp.com/badge/Commit-green.svg?logo=commit)      |
| `comments` | ![img](https://custom-icon-badges.herokuapp.com/badge/Comments-teal.svg?logo=comments)   |
| `repo`     | ![img](https://custom-icon-badges.herokuapp.com/badge/Repo-blue.svg?logo=repo)           |
| `pr`       | ![img](https://custom-icon-badges.herokuapp.com/badge/Pull%20Request-purple.svg?logo=pr) |
| `heart`    | ![img](https://custom-icon-badges.herokuapp.com/badge/Heart-D15E9B.svg?logo=heart)       |
| `mail`     | ![img](https://custom-icon-badges.herokuapp.com/badge/Mail-E61B23.svg?logo=mail)         |

### Miscelanious

| Slug         | Example                                                                                    |
| ------------ | ------------------------------------------------------------------------------------------ |
| `controller` | ![img](https://custom-icon-badges.herokuapp.com/badge/Controller-blue.svg?logo=controller) |
| `swi-prolog` | ![img](https://custom-icon-badges.herokuapp.com/badge/Prolog-E61B23.svg?logo=swi-prolog)   |


## ➕ Adding a new logo

Upload new icons using the demo site!

<https://custom-icon-badges.herokuapp.com>

[![image](https://user-images.githubusercontent.com/20955511/128404656-30af9c39-39a4-4ac8-a4b0-2a077806a94c.png)](https://custom-icon-badges.herokuapp.com)

<!-- ## 📤 Deploying it on your own

If you can, it is preferable to host the files on your own server.

Doing this can lead to better uptime and more control over customization (you can modify the code for your usage).

<details>
  <summary>Deploy to Heroku</summary>

  1. Sign in to **Heroku** or create a new account at <https://heroku.com>
  2. Click the Deploy button below

  <p align="center">
    <a href="https://heroku.com/deploy?template=https://github.com/DenverCoder1/custom-icon-badges/tree/main">
      <img src="https://www.herokucdn.com/deploy/button.svg" title="Deploy to Heroku" alt="Deploy"/></a>
  </p>

  3. Add the url of a Mongo database as the `DB_URL` config var. The database should have a collection called `icons`. See [getting started](https://docs.atlas.mongodb.com/getting-started/) for more info on setting up a free Mongo Atlas database.

![image](https://user-images.githubusercontent.com/20955511/126066250-108fc119-4bc3-4ba0-9b07-0c7402c5790e.png)

  4. Click **"Deploy App"** at the end of the form
  5. Once the app is deployed, you can use `<your-app-name>.herokuapp.com` in place of `custom-icon-badges.herokuapp.com`
	
</details> -->
