# Update Log

This file contains all the updates for Michael's website including the things that need to be fixed.

# Updates
## Pages to update (complete when checked)

- [x] - Home
- [x] - Contact
- [x] - About
- [x] - Education
- [x] - Rowing
- [x] - Hockey
- [x] - Computer Science
- [x] - Travel

## Other

- [x] - Update to Bootstrap 4
- [x] - Add FontAwesome
- [x] - Setup Jekyll
- [x] - Final Release
- [x] - New branch for old website
- [ ] - Add mandatory HTTPS (will be done when website is released)
- [x] - Add updated website to [beta.michaelbateman.ca](https://beta.michaelbateman.ca)
- [x] - Add Travis CI
- [x] - Update Nav to Bootstrap 4
- [x] - Update error 404 page

# Notes

## Friday Feb 17

* Created final release for old website
* Added new branch for old website, which is avalible for viewing at [michaelbateman.ca](http://michaelbateman.ca)

## Sunday Feb 18

* Added Bootstrap 4
* Added FontAwesome
* Setup Jekyll
* Redesign homepage without `panel` as Bootstrap 4 dropped
* Redesigned nav

## Monday Feb 20

* Experiementing with website, running on local development sever - Apache

## Tuesday Feb 21

* Focus on `contact.html` which now lives at `{{ site.baseurl }}/contact/`
* Added contact methods using panels, with the backgrounds being colors for the contact type
* Database I used can be found at [https://brandcolors.net](https://brandcolors.net)

## Wednesday Feb 22

* Rename `aboutme.html` -> `about.html`
* Change the `about.html` page for Bootstrap 4 which is now at `{{ site.baseurl }}/about/`
* Change the `education.html` page for Bootstrap 4 which is now located at `{{ site.baseurl }}/about/education/`
* Changes Nav links

## Thursday Feb 23

* More internal testing on local dev server, nothing ready to be pushed yet.

## Friday Feb 24

* Change the `rowing.html` page to `{{ site.baseurl }}/about/rowing/`.
* Update the `rowing.html` page to conform with Boostrap 4

## Saturday Feb 25

* Adds Travis CI integration (badge for `README.md` will come once the whole project has finished.

## Tuesday Feb 28

* Complete the new `hockey.html` page
* `hockey.html` page has now been relocated to `{{ site.baseurl }}/about/hockey/`
* Redesign of the `computer-science.html` page
* `computer-science.html` now located at `{{ site.baseurl }}/about/computer-science/`
* Make the next `travel.html` page which is located at `{{ site.baseurl }}/about/travel/`

## Wednesday Mar 1

* Fixed the `404.html` page.