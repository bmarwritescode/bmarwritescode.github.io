# Ben's Website

To build locally, simply run `jekyll serve`.

## Dependencies

Requires [Jekyll](https://jekyllrb.com/), which can be installed using the following commands:
```
brew install ruby
gem install --user-install bundler jekyll
```
You may not have the gem bin on your path if you get the following warning:
```
WARNING:  You don't have /Users/benjaminmariano/.gem/ruby/2.6.0/bin in your PATH,
	  gem executables will not run.
```
If this is the case, add the following to your `.zshrc` config file:
```
export PATH=/Users/benjaminmariano/.gem/ruby/2.6.0/bin:$PATH
```
