# Static file server for Heroku

There're sometimes when we want to test something and we just need to serve static files on the web. This repository is meant for that!

# Usage

1. Clone this repository
2. Run `heroku create --app your-name`
3. Add any files you want :).
4. `git push heroku master`

You don't need to install anything.

Whatever file you've added to this folder will get served. For example, as there's a `index.html` created as an example, you can just go to that URL and that file will be shown. As simple as that

Try going to [https://static-file-server.herokuapp.com/](https://static-file-server.herokuapp.com/) and [https://static-file-server.herokuapp.com/sub-path/hi.json](https://static-file-server.herokuapp.com/sub-path/hi.json)

# Licence

MIT
