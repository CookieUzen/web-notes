# Web-Notes

This is the repository hosting the website for [Unit-Notes](https://github.com/CookieUzen/Unit-Notes), a student created textbook/notes for the IB Curriculum.
You can find the website [here](https://cookieuzen.github.io/web-notes).

This website is still under development, and will be merge back into the Unit-Notes repository when done.
You can edit the website by going to [here](https://github.dev/CookieUzen/web-notes).

Web-Notes is based on the [Docsy Jekyll theme](https://vsoch.github.com/docsy-jekyll/), and deployed on Github Pages.

## Usage

### 1. Get the code

You can clone the repository right to where you want to host the docs:

```bash
git clone https://github.com/cookieuzen/web-notes.git
```

### 2.0 Install Dependencies

Ruby is required for jekyll. 
Jekyll is also required for compiling the site locally.
`bundle` is recommended for managing the dependencies.

```bash
gem install bundle
bundle install # run inside the repository
```

You can install gem with your operating system's package manager.

### 2.1 Ruby Version

Github Pages uses ruby version `2.7`.
In order avoid compatibility issues, this project uses ruby version `2.7.2`.
Use a ruby version manager to install `2.7.2` if you do not have it [rvm](https://rvm.io).

### 2. Serve

You can compile the site locally by running `jekyll serve`.
It is recommended to use `bundle` in addition to jekyll.

```bash
bundle exec jekyll serve
```

You can then open your browser to [http://localhost:4000/web-notes](http://localhost:4000/web-notes) to see site locally.

# TODO
- [ ] CSS
	- [x] modify heading/subtitles
	- [ ] add highlight syntax
- [ ] Organization
	- [ ] table of content front page (liquid/javascipt?)
- [ ] Subjects
	- [ ] Physics
		- [ ] Unit 1 Uncertainties
	- [ ] CS
		- [ ] Unit 2 Logic Gates TODOs
	- [ ] Math
		- [ ] Fix Unit structures
	- [ ] Business Management
		- [ ] Unit 2 Ethics
		- [ ] Unit 2 Structrue
