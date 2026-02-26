# ssl-a-team.github.io
Source for our team's website

## Dev Setup
1. Install Jekyll
   ```shell
   # Commands for Ubuntu
   sudo apt-get install ruby-full build-essential zlib1g-dev
   echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
   echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
   echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
   source ~/.bashrc
   gem install jekyll bundler
   ```
1. Run local server to preview website changes
   ```shell
   bundle exec jekyll serve
   ```
