## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/xGoustt/kmuu/edit/gh-pages/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

# Download the apk file
function download() {
    echo -e "Downloading..."
    local ua="Mozilla/5.0 (Windows NT 6.1; WOW64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/38.0.2125.104 Safari/537.36"
    local url=`printf ${APK_DL_URL} ${PACKAGE_NAME}`
    curl "$url" -o "$PACKAGE_NAME.apk" --write-out "%{http_code}" --compressed --retry 10 --retry-max-time 0 \
        -H "Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,*/*;q=0.8" \
        -H "Connection: keep-alive" -H "Accept-Encoding: gzip,deflate,sdch" \
        -H "Accept-Language: en-US,en;q=0.8,ta;q=0.6" \
        -H "User-Agent: $ua"

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/xGoustt/kmuu/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
