## Where to perform common tasks:
- **Updating profile**: _data/members.yml
- **Adding publications**: _publications/*paper\_name*.yml

The BibTeX and citation should be copied verbatim from the ACM DL, if possible.
Thumbnail pictures should be 16x9, at least 300 px wide.


## Local Development

1. Install Ruby if not already installed (installed by default on OS X). On Windows, use http://rubyinstaller.org/. On Linux, run `sudo apt-get install ruby-full`. This should come with the gem package manager.
2. Install Jekyll and plug-ins in one fell swoop. `gem install github-pages` (OS X users may need to `sudo gem install github-pages`) This mirrors the plug-ins used by GitHub Pages on your local machine including Jekyll, Sass, etc.
3. Clone down your fork `git clone git@gitlab.cs.washington.edu:ubicomplab/ubicomplab.github.io.git`
4. Serve the site and watch for markup/sass changes `jekyll serve`
5. View your website at http://127.0.0.1:4000/
6. Commit any changes and push everything to the master branch of your GitHub user repository. GitHub Pages will then rebuild and serve your website.
