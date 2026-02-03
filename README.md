# `gathering`

## What is Webring?

A webring is a collection of websites linked together in a loop. Each website contains links to the previous and next websites in the ring. If you navigate far enough, eventually you end up back where you started!

<a href="https://upload.wikimedia.org/wikipedia/commons/9/97/Webringwork.png"><img src="https://upload.wikimedia.org/wikipedia/commons/9/97/Webringwork.png" width="512" alt="Webring example graphic"/></a>

Webrings were popular in the early days of the internet as a way for website owners to promote each other's content and encourage community engagement.

[Create an issue to join](https://github.com/pink10000/gathering/issues/new?template=join.md)

## How do I get in?

1. Be a UCSD student or a former UCSD student.
2. Put the navigation buttons for `gathering` somewhere on your webpage (see below).
3. Have some content on your webpage. Tell us about yourself!
4. [Create an issue to join](https://github.com/pink10000/gathering/issues/new?template=join.md) or create a PR manually.

Take a look at `websites.toml` and put your website information down there. Not all fields need to be filled out, like `atom` or `rss`.

An entry might look like:

```toml
[[websites]]
name ="Example 1 Site"
slug = "Example1"
about = "Example Website 1!"
url = "https://example1.com"
owner = "owner 1 (your github username is fine!)"
```

After that, add the webring HTML somewhere on your site, like the sidebar or footer. Replace `YOUR_SLUG` with the slug you wrote above!

```html
<a href="https://kytrinh.me/gathering/YOUR_SLUG/previous">&larr;</a>
<a href="https://kytrinh.me/gathering">gathering</a>
<a href="https://kytrinh.me/gathering/YOUR_SLUG/next">&rarr;</a>
```

And that's it!

## Credits

This project uses [`ringfairy`](https://github.com/k3rs3d/ringfairy). Please go check it out!
