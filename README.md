# foobar.opensuse.org

This openSUSE website is generated from [openSUSE Jekyll Template](https://github.com/openSUSE/jekyll-template).

> Please remember openSUSE is __NOT__ SUSE, and neither this nor any other website with openSUSE branding is fit for webservers hosting on suse.com/suse.de domains or other SUSE related projects.

## Generate Repository From Template

1. Open [Repository Generator](https://github.com/openSUSE/jekyll-template/generate) to create a new repositosiry based on this one
2. Edit `_config.yml` to customize site name, navbar and footers, etc.
3. Edit `index.md` to render content for your home page.
4. Add as many more `.md` and `.html` files as you need to expand the site.

## Development

### How to set up environment?

```bash
sudo zypper in ruby ruby-devel
bundle install --path vendor/bundle
```

### How to build?

```bash
bundle exec jekyll build
```

Resulting site will be in `_site` directory.

### How to serve locally?

```bash
bundle exec jekyll serve
```

Visit <http://127.0.0.1:4000/> in your browser.
