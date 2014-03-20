githubrepo-octopress
====================

Plugin to display Github Repos in Posts for Octopress. The plugin uses
[JoelSutherland/GitHub-jQuery-Repo-Widget](https://github.com/JoelSutherland/GitHub-jQuery-Repo-Widget)
to generate a box for displaying your favourite Github repo in your posts.

### Installation

1. Clone Github jquery Repo Widget to your computer

	```git clone https://github.com/JoelSutherland/GitHub-jQuery-Repo-Widget```


2. Clone githubrepo-octopress to your computer

	```git clone https://github.com/sotsy/githubrepo-octopress```

3. Copy ```jquery.githubRepoWidget.min.js``` in
	```youroctopressfolder/source/javascripts``` and put ```githubwidget.rb``` into ```youroctopressfolder/plugins```

4. Merge ```head.html``` with ```youroctopressfolder/source/_includes/custom/head.html```

### Usage

Shortcode for adding Github Repo to your post

```
{% githubrepo sotsy/githubrepo-octopress %}
```

Make sure you set the full name in the shortcode. Otherwise the .js doesn't find
the correct repo.
