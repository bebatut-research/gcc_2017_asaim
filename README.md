Poster about ASaiM at GCC 2017
==============================

![Poster](images/poster.png)

# Generate the website locally

## Requirements

- Install Jekyll using [RubyGems](https://rubygems.org/pages/download):

    ```
    $ gem install jekyll
    $ gem install jemoji
    $ gem install jekyll-feed
    $ gem install bundler
    ```

    If you encounter any errors make sure `ruby` and it's corresponding developer packages (e.g. `ruby-dev`, `ruby2.3-dev`) are installed.

    If you are installing it on Mac OSX, you need to install it this way as `/usr/bin/` is not writable:

    ```
    $ sudo gem update —system
    $ sudo gem install -n /usr/local/bin/ gem name
    $ sudo gem install -n /usr/local/bin/ jemoji
    $ sudo gem install -n /usr/local/bin/ jekyll
    $ sudo gem install -n /usr/local/bin/ jekyll-feed
    $ sudo gem install -n /usr/local/bin/ bundler
    ```

## Usage

- Run a local Jekyll server

    ```
    $ make serve
    ```

- Visualize the generated website locally at [http://localhost:4000/](http://localhost:4000/)
