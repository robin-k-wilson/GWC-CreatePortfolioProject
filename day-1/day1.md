# Day 1 (this will be the most time consuming day)

## Setup dev environment and create Jekyll Hello World!

1. Setup git
2. Create github account
3. Download Ruby and RubyGems
4. Hello World! Jekyll

#### The Portfolio Creation Game Plan for today

1. Setup github + follow along with the command line
2. Setup homebrew, ruby, gems
3. Startup Jekyll and get it to show up in browser http://localhost:4000

# 1. Setup git and github and learn some command line/terminal commands

Make a github account if you have not already:

https://github.com/

In the command line run:
`git -v`

If the command line did not print a version number, install git:

https://git-scm.com/downloads

Create a new repository for your new website on github.

# 2. Install Jekyll and Dependencies

Different OS Systems mean different installation processes.

While waiting, why not browse Jekyll themes:

[Free Jekyll themes](https://jekyllthemes.io/free)

# Mac

From the (Jekyll on macOS)[https://jekyllrb.com/docs/installation/macos/] installation page

1. Check Ruby version and if you're running it
	- `which ruby` - will respond with a file path
	- `ruby -v` - will respond with a version we need 2.2.5 or above!
2. Install Jekyll
	- `gem install bundler jekyll`

If you need to update or install a later version of ruby, use this guide:

https://usabilityetc.com/articles/ruby-on-mac-os-x-with-rvm/

# Windows

From the (Jekyll on Windows)[https://jekyllrb.com/docs/installation/windows/] installation page

1. Install RubyInstaller and run
    - `https://rubyinstaller.org/`
2. Open up Command Prompt
3. In command prompt type
	`gem install jekyll bundler`

# 3. Make your first Jekyll site and push to update your Github

## Follow these instructions

https://jekyllrb.com/docs/

## Update your repo in github

1. `git status`
2. `git add -A`
3. `git status`
3. `git commit -m "Created initial Jekyll website with jekyll new"`
4. `git push`

#### Finished Day 1!
