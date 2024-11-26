## Requirements
To locally test the result of the website we recommend using Jekyll.
More information can be found [here](https://jekyllrb.com/docs/installation/)

## How to use?
Under index.md you can edit the webpage which can be served with:
```jeckyll serve```
This will open a local webserver on https://127.0.0.1:4000/. While editing
index.md you can see your edits live on the webpage. The given template can be changed to your liking using the file in _layout, default.html.

Different sub-pages can be created and added linked through the default.html file.

## How to setup a github pages account?
First you will have to create a new repository with the md files or clone this repository as a start.
For a full explanation on how to create a GitHub Pages Account click [here](https://docs.github.com/en/pages/quickstartz). After creation your webpage will be available under [USERNAME].github.io.

In case you would like to connect your own web-domain this is possible. In the root of the github repository you will need to add an file called "CMAKE" with the domain name you would like to use:
```example.domain www.example.domain```

In your DNS host add an A record with the contents:
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

Or an AAAA record:
```
2606:50c0:8000::153
2606:50c0:8001::153
2606:50c0:8002::153
2606:50c0:8003::153
```

For a full explanation on how to add a custom domain to GitHub Pages click [here](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).