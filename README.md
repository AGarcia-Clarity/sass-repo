## Steps
### 0. Clone this repo
 - Use the Green Code button to grab the URL (URL should end in .git) and copy it.
 - In your local directory run `git clone https://URLonGitHub.git`
 - Navigate into the directory `cd sass-repo`

### 1. Install Sass by running `npm install -D sass`
  - This will add it to 'dependencies' in the package.json

### 2. Install Parcel by running `npm install -g parcel-bundler`
  - This will add parcel-bundler globably

### 3. Run `npm run dev` to start the parcel bundler


## WTF is...
Parcel is a web application bundler, basically takes any file you throw at it (.scss, .svg, .html, etc) and compiles it.

Sass is a preprocessor that turns the Sass/SCSS styling format and compiles it into CSS.


## How the fuck is this working?
Parcel is fucking magic. Basically it sees that the Sass package is installed and that the styles.scss file is referenced in the index.html file and runs the Sass package automatically while watching the index.html file :sunglasses: