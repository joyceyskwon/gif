#gif
gifs in your terminal. because why not?
---
##installation & setup
`gem install gif` installs this gem
`gif --setup` installs dependencies (gifsicle & imgcat)
---
##usage
`gif` will play a random gif in your terminal
`gif [search_terms]` will filter by search terms. for example, `gif cute pikachu` will cause you to immediately feel 100% happier.
`--loops` or `--l` will let you loop the gif. for example, `gif cute pikachu --loops 10` will cause you to immediately feel 1000% happier.
---
##problems
you need to have ruby, rubygems, and homebrew installed. unfortunately, this gem doesn't work on windows right now (as it uses homebrew for some dependencies). windows/linux support will be coming soon - sooner if you make a PR yourself :)

some gifs will look funky in your terminal. this can happen if they cannot be unoptimized by gifsicle. essentially, many gifs are stored where each frame is a diff. gifsicle can try to turn these diffs into full frames (a process known as unoptimization), but sometimes cannot do this due to complicated color palettes, transparency issues, etc.

please file an issue or PR if you think you can address either of these problems (or anything else you run into).
---
that's all there is to it, folks.
happy giffing!
