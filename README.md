# Web-Notes

This is the repository hosting the website for [Unit-Notes](https://github.com/CookieUzen/Unit-Notes), a student created textbook/notes for the IB Curriculum.
You can find the website [here](https://cookieuzen.github.io/web-notes).

This website is still under development, and will be merge back into the Unit-Notes repository when done.

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

### 2. Serve

You can compile the site locally by running `jekyll serve`.
It is recommended to use `bundle` in addition to jekyll.

```bash
bundle exec jekyll serve
```

You can then open your browser to [http://localhost:4000/web-notes](http://localhost:4000/web-notes) to see site locally.
