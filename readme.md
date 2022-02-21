
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![GitHub top language](https://img.shields.io/github/languages/top/lowerbarriers/smith-for-congress)
![GitHub language count](https://img.shields.io/github/languages/count/lowerbarriers/smith-for-congress)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

[Click for a free campaign website](https://github.com/lowerbarriers/smith-for-congress/fork)

# Elect Jason Deneau for Berkley School Board

I am Jason M. Deneau and I am running for a position on the Berkley School Board. My home is in Oak Park, which is a part
of the Berkley School District.  The district is special in that it joins with the three cities – Oak Park, Huntington Woods
and Berkley. My kids attend school in the district and we have loved and appreciated every minute.

Currently many school boards around the country are going through some very competitive elections. Tragically, many school
boards have become full of conflicts and divisiveness.  As a member of the Berkley School Board, I pledge to continue the
civil and collaborative environment of our wonderful Berkley School District. So, I’m asking for your vote today. Help me,
help our team to continue the forward momentum that our schools have enjoyed and benefitted from thus far.

## Installation

  1. Fork the repository (button at top of repo page)
  2. On your forked repository page, go to 'Settings' and rename the repository to match your desired behavior
    * Most of the time you will want `user/organization-name`.github.io
    * It can also be any name, typically using the `gh-pages` branch
  3. Edit to your heart's content

If you want to use netlify,
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/lowerbarriers/smith-for-congress)

If you prefer Vercel,
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/import/project?template=https://github.com/lowerbarriers/smith-for-congress)

### Creating a local version for development

  1. Clone the repository to your local machine
  2. `cd` into it
  3. Run the command `bundle install` in the root of the project to get the Jekyll standard items (requires
    [bundler](https://bundler.io/))
  4. Run `npm install` in the root of the project for non-required build dependencies (requires node and npm)
  5. Run `bundle exec jekyll serve --verbose --config _config.yml,_config.localdev.yml` to build and serve your site to
    `http://localhost:4000/`

Optionally you can look at the comments in the `.scripts/` directory for any image (optipng, pngcrush, jpegoptim, webp, avif)
and other dependencies for optimizing assets on the back end. This helps improve front-end performance if you can manage it.

You can run the `.scripts/` from the project root, ideally when the server is not running since it will trigger a rebuild.

```shell script
user@computername $ .scripts/images.sh
```

and

```shell script
user@computername $ .scripts/pre-commit.sh
```

#### Aggressive caching

While the service worker cache should increment every time the site builds, often you will have to use the 'Application'
tab of the devtools to clear all site storage and caches. Keeping the devtools open also allows you to right-click the refresh
button to select "Empty cache and hard reload".

This is a mild inconvenience you learn to live with and admire, and is a reminder that front-end performance and optimization
is important.
