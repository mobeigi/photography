## Forked from
https://github.com/rampatra/photography

## Changes
- Various bug fixes
- Performance optimizations
- Updated to latest multiverse from [https://html5up.net/multiverse](https://html5up.net/multiverse)

---

## Run the website locally to test
1. `$ cd photography` - go to the project directory
2. `$ bundle install` - install gems
3. Change the `baseurl` in `_config.yml`
4. `$ bundle exec jekyll serve` - start/run the website

### Build the website
1. `$ cd photography` - go to the project directory
2. `$ npm install` - install all npm dependencies
3. `$ gulp` - minify css, js, resize images, etc.

Note: You only need to build the website if you make changes such as replacing the images, modifying the css styles, etc.
 
## ProTips

### Resize Images
I have made this as a [npm](https://www.npmjs.com) package with [gulp](http://gulpjs.com/) to __automate image resizing
and thumbnail generation__. So if you're lazy like me then you can just do the following before you push your images to github.

1. Fork and clone the project to your computer
2. Go inside the project `$ cd photography`
3. Install all dependencies by `$ npm install`
4. Copy all your pictures (possibly jpg, the largest size available, straight from your camera) and put it inside `images` directory
5. Run `$ gulp resize` to resize the images and to generate thumbnails automatically
6. Push your changes to github.com by `$ git add --all` and `$ git commit -m "a nice commit message"` and then finally `$ git push origin master`
