# Hugo Remark Themem
This is a simple theme for Hugo that is based on the [Remark](https://github.com/gnab/remark) presentation tool. It is designed to be simple and easy to use, and to make it easy to create presentations that look good.

## Installation
To install the theme, you need to clone the repository into your Hugo site's `themes` directory:

```bash 
# add submodule to your site
git submodule add https://github.com/akhuang/remark-hugo.git themes/remark-hugo

# update
git submodule update --init --recursive --remote

```

Then, add the following line to your site's `config.toml`:

```toml
theme = "remark-hugo"
```
## Acknowledgements
The theme is heavily inspired by yihui's blog and his xaringan theme, as well as gnab's remark theme. Special thanks to them.

## reference
- [Remark](https://github.com/gnab/remark)
- [Hugo](https://gohugo.io/)
- [Hugo Themes](https://themes.gohugo.io/)
- yihui's [xaringan](https://slides.yihui.org/xaringan/zh-CN.html#11)