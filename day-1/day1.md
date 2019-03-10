# Day 1 (this will be the hardest day)
## Setup dev environment and create Jekyll Hello World!

1. Setup git
2. Create github account
3. Download Ruby and RubyGems
4. Hello World! Jekyll

#### The Portfolio Creation Game Plan for today
1. Setup github + follow along with the command line
2. Setup homebrew, ruby, gems
3. Startup Jekyll and get it to show up in browser http://localhost:4000

Different OS Systems mean different installation processes.

While waiting, why not browse Jekyll themes:

[Free Jekyll themes](https://jekyllthemes.io/free)

# Mac

From the (Jekyll on macOS)[https://jekyllrb.com/docs/installation/macos/] installation page

1. Install Homebrew
	1. Open terminal
	2. Run this command
    	- `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
2. Install Ruby in terminal
	- `brew install ruby`
3. Change Ruby path
    - `export PATH=/usr/local/opt/ruby/bin:$PATH`
4. Check Ruby
	- `ruby -v`
	- `which ruby`
5. Install Jekyll
	- `gem install bundler jekyll`

# Windows

From the (Jekyll on Windows)[https://jekyllrb.com/docs/installation/windows/] installation page

1. Install RubyInstaller and run
    - `https://rubyinstaller.org/`
2. Open up Command Prompt
3. In command prompt type
	`gem install jekyll bundler`

# To double check dependencies for macOS and Windows in Terminal/Command Prompt
- `ruby -v`
- `gem -v`
- `gcc -v`
- `g++ -v`
- `make -v`

# Quick Start with Jekyll

https://jekyllrb.com/docs/

#### Stretch Goals
1. Setup a free theme
2. Take photos of your A-Frame project
3. Host these photos
