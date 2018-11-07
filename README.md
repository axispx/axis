# Axis
A minimal and light [Hugo](https://gohugo.io/) theme for personal blogs.

![axis](https://image.ibb.co/dxpp3V/axistheme.png)

## Configuration Parameters

### Avatar URL
Link for your avatar image.
```
[params]
    avatar_url = "https://youravatarurl.com/img"
```

### Bio
Multiple bio paragraphs can be set.
```
[[params.bio]]
para = "Hi, I'm Ashish. I'm a 0.01x developer playing accross the full stack."

[[params.bio]]
para = "I started this blog to put down my random thoughts in a more concrete format. I write about Software Engineering, Open Source Software, Programming Languages and Tech in general."
```

### Social Links
Social links for people to contact you. Multiple social links with font awesome icons can be set.

```
[[params.social]]
url = "https://github.com/anarchyrucks"
fa_icon = "fab fa-github"

[[params.social]]
url = "https://twitter.com/anarchyrucks"
fa_icon = "fab fa-twitter"

[[params.social]]
url = "mailto:anarchyrucks@gmail.com"
fa_icon = "fas fa-envelope"

[[params.social]]
url = "/index.xml"
fa_icon = "fas fa-rss"
```
