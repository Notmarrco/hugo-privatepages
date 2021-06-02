# Hugo Private Pages

```sh
git submodule add https://github.com/notmarrco/hugo-privatepages.git themes/notmarrco.hugo-privatepages
```

In your ` config.toml` add :

```toml
themes = ["notmarrco.hugo-privatepages" , ....]
```

Then add :

```md
---
private: true
---
```

in your frontmatter to hide the content from default sitemap.xml and rss.xml.

