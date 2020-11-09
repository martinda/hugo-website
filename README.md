# The website for the Cardinal Creek Community Association

Deploy instructions:

```
# Generate the website
hugo

# Upload
rsync -azP public/ cardinal@cardinalcreek.org:/home/cardinal/public_html/hugo
```
