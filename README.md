# family-hub ReadMe
Digital hub for your family

See the wiki for documentation and detail. 

## TODO
At some point we'll use github projects, but for now we can keep it here.

* How would it work on a TV and mobile phone
* How to connect to different sources
* Source categories: photos, videos, clippings, etc

## Tech stack
Currently using static site generator jekyll 

## Running locally

1. **Install dependencies:**
   ```bash
   bundle install
   ```

2. **Build and serve the site:**
   ```bash
   bundle exec jekyll serve
   ```

3. **View the site:**
   Open your browser and navigate to `http://localhost:4000`

The site will automatically rebuild when you make changes to files in the `docs/` directory.

**Prerequisites:**
- Ruby and Bundler installed on your system
- For this dev container, you may need to install Ruby first:
  ```bash
  apt update && apt install -y ruby-full build-essential
  gem install bundler jekyll
  ```