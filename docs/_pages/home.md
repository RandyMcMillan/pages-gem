---
title: "GitHub Pages Docker"
layout: home
permalink: /
title: "GitHub Pages Docker"
author_profile: true

---

<html>
<head>
  <link rel="stylesheet" href="/assets/css/main.css">
</head>
</html>

```
Install docker
```
then

```
git clone https://github.com/RandyMcMillan/pages-gem.git
cd pages-gem
SITE=./docs make image
SITE=./docs make server
```

# Templated theme:

Click [<i class=""></i> **Create Theme**](https://github.com/randymcmillan/pages-gem-starter/generate){: .btn .btn--primary} for the quickest method of getting started with the [Minimal Mistakes Jekyll theme](https://github.com/mmistakes/minimal-mistakes){: .btn .btn--primary}.

```
Use the link above to create a new theme repo
git clone https://github.com/RandyMcMillan/<your-theme>.git
cd <your-theme>
SITE=~/<your-theme> make image
SITE=~/<your-theme> make server
```


## License

Distributed under the [MIT License](https://raw.githubusercontent.com/RandyMcMillan/pages-gem/master/LICENSE){: .btn .btn--primary}.