githubrepo-octopress
====================

Plugin to display Github Repos in Posts for Octopress. The plugin uses [JoelSutherland/GitHub-jQuery-Repo-Widget](https://github.com/JoelSutherland/GitHub-jQuery-Repo-Widget) to generate a box for displaying your favorite Github repo in your posts.

### Installation

Clone Github jquery Repo Widget to your computer

```bash
git clone https://github.com/JoelSutherland/GitHub-jQuery-Repo-Widget
```

Clone githubrepo-octopress to your computer

https://github.com/sotsy/githubrepo-octopress

Copy ```jquery.githubRepoWidget.min.js``` in ```youroctopressfolder/source/javascripts``` and put ```githubwidget.rb``` into ```youroctopressfolder/plugins```

### Usage

Shortcode for adding Github Repo to your post

```
{% githubrepo sotsy/githubrepo-octopress %}
```

Make sure you set the full name in the shortcode. Otherwise the .js doesn't find the correct repo.
