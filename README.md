# Van Voorhis Group Website

This website is built with [Jekyll](https://jekyllrb.com/).
It is derived from the great template provided by the
[Allan Lab](https://www.allanlab.org/aboutwebsite.html), at Leiden University.


## How to Add Yourself to the Team Page

Members are stored as markdown files under
[_pages/team/_posts](_pages/team/_posts).

Each new member `.md` file must look like [this](_pages/team/_posts/1900-01-01-postdoc_grad.mdexample):

``` yaml
---
layout: member
category: grad # pi, postdoc, grad, ugrad, alumni
name: Tim Beaver # preferred name
image: troy.png # upload image to images/team/
office: 6-222
email: timbeaver@mit.edu
fellowship:
  - MIT Beaver Fellow
  - Beaver Association Fellow
education:
  - PhD, Beaver Economics, MIT, 1918
  - Sc.B., Beaver Economics, MIT, 1917
---
```

Make sure to add your image (png or jpg), formatted to 450px-by-600px in [_images/team](_images/team).

Once you have made these changes in a branch, please submit a pull request. One of the webmanagers will approve and incorporate your request.

## Setup

``` bash
brew install ruby
gem install bundler jekyll
```

Clone this repository, then install the dependencies:

``` bash
bundle install
```

## Run

Run the local webserver with:

``` bash
bundle exec jekyll serve
```
