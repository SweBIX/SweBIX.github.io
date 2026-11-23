# SweBIX.github.io

Source of [swebix.github.io](https://swebix.github.io), the website of the *Swedish BioImage Computing Network* (SweBIX).

## Joining SweBIX

Add yourself to the members list in a pull request:

1. Copy [`_members/_template.md`](_members/_template.md) to `_members/<first-name>-<last-name>.md` and fill it out, following the comments in the template.
2. If one of your affiliations is missing, add it to `_organizations/`, based on [`_organizations/_template.md`](_organizations/_template.md).
3. Open a pull request and ask an existing member to approve it.

See [Join us](https://swebix.github.io/#join-us) on the website for details.

## Previewing locally

The site is built with Jekyll on GitHub Pages. To preview changes locally, install [Ruby](https://www.ruby-lang.org/) and [Bundler](https://bundler.io/), then run:

```sh
bundle install
bundle exec jekyll serve --livereload
```

and open <http://localhost:4000>.
