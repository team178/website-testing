# website-testing
A place for testing
available at [http://farmingtonrobotics.org/website-testing](http://farmingtonrobotics.org/website-testing) :)

### How to run locally
This assumes you already have Jekyll set up; if you don't, head [here](https://github.com/team178/team178.github.io#running-locally).

1. Make sure you have a local version of the main website:
<br>`git clone https://github.com/team178/team178.github.io.git`

2. Navigate into the repository:
<br>`cd team178.github.io`

3. Clone this reposititory into the main website:
<br>`git clone https://github.com/team178/website-testing.git`
<br>The .gitignore in the main website has `/website-testing` in it. So this repo won't be tracked by git while in the main website's folder. But if you cd into `/website-testing`, you can still commit changes.

4. Run `jekyll serve` to see the website on `http://localhost:4000`.

5. If you get any errors or warnings, try running `bundle exec jekyll serve` instead.
