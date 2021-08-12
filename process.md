## npm init

-> creates package.json

## Packages needed

.DART-SASS `helps compile sass to css`
.BOOTSTRAP 5
.FONTAWESOME `helps with icons`
.AUTOPREFIXER `is a plugin which saves you the monotony of wording prefixes to css`

# to install sass go to npmjs.com

-> npm install bootstrap --save
`--save to include to dependency` `now it is not needed as it is already included in npm install`

# install fontawesome by npm command given in fontawesome.com

# to install autoprefixer go to npmjs.com

## Now to compile sass to css we need to made changes in scripts in package.json

# the scripts stores commands so we have to create a command which will store the compiled css files (from our sass from given folder) to given folder

command - "compile:sass":"sass scss(folder in which sass is stored):assets/css(folder in which css is going to save)"

# run - `npm run compile:sass`

to compile sass file in scss folder and create a css file in assets/css folder
.css.map is a source map file (search for more description)

## Add `--watch` flag in the script so that it does not terminate process and check for changes

## Now Customize Bootstrap

-> create a custom sass file to keep variables which will override bootstrap
-> the file name should start with `_` means it is not to compile by scripts

# download bootstrap bundle folder/directory/zip/archive

# copy the `webfonts` folder from `node_modules/@fontawesome` and paste in assets

# the `--something` in class naming is called BEM `Block Element Modifier`

-> `--` is Modifier
-> `__` is Element

# download illustrations from `manypixels.com` and give your color

# for background wave `getwaves.io`

-> waves at down of a section which cuts border

# for display videos `glightbox` from github.io

-> download the bundle - inside the bundle from dist folder copy css,js folders and paste in vendors inside assets

-> see the lightbox options from npmjs.com/.../glightbox or from github

# go to fontawesome cheatsheet for icons

# for svg icons `tablericons.com`
