# `gathering`

# How do I get in?
1. Be a UCSD student or a former UCSD student.
2. Have the buttons for `gathering`
3. Have some content on your webpage.
4. Submit a PR!

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

# Credits

This project uses [`ringfairy`](https://github.com/k3rs3d/ringfairy). Please go check it out!