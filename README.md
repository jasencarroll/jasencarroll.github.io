# BlogSite

This will be the repo for my blog, managed by Jekyll, a Ruby gem. Thanks to [David's Blog](https://dfederm.com/creating-a-blog-using-github-pages/) for getting me started. 


### Installation
```
# Must be using a Unix based system (Linux, MacOS, WSL, etc.)
# Install Ruby
sudo apt-get install ruby-full build-essential zlib1g-dev

# Ensure RubyGems packages are installed under the user account instead of root.
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

# Install Jekyll and Bundler:
gem install jekyll bundler
```

After navigating to your desired repo folder, use `jekyll new .` to start a new site. 