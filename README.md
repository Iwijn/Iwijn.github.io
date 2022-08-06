# Running locally

Github does not give a Gemfile when the github pages site is generated.

> bundle init

Add the following line to the new Gemfile:
`gem 'github-pages', group: :jekyll_plugins`

> bundle add webrick

> bundle exec jekyll serve

### Update

> bundle update
