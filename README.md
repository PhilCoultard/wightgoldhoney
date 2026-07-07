# IoWHoney

A GitHub Pages website to act as a holding page for IoW Honey sales.

## Install Jekyll

1. Install: https://jekyllrb.com/docs/installation/macos/
   brew upgrade
   brew install chruby ruby-install
2. Install latest version of ruby: ruby-install ruby 3.4.1
3. Configure the env:
   echo "source $(brew --prefix)/opt/chruby/share/chruby/chruby.sh" >> ~/.zshrc
   echo "source $(brew --prefix)/opt/chruby/share/chruby/auto.sh" >> ~/.zshrc
   echo "chruby ruby-3.4.1" >> ~/.zshrc # run 'chruby' to see actual version

## Custom Domain

Configure a custom domain via repository's Settings/Pages tab. Documentation is linked therein.

## Theme

Originally using [minima theme](https://github.com/jekyll/minima) but it was a bit 'single column' so swithched to [minimal-mistakes](https://mmistakes.github.io/minimal-mistakes/)

See the [Structure](https://mmistakes.github.io/minimal-mistakes/docs/structure/) page for how to lay out the site.
