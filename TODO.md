# TODOs

```
~~~ 3022.VO.2 ~~~

- ctrl f TODO
- Fix TOC ids (20s everywheres)

https://github.com/Munter/netlify-plugin-checklinks


ORIGIN

- Make it shorter, less than 15 minutes, but move out content to differente sections
- Less emphasis on inconcequential stuff, move all the "Neutral Foundation" to another section

- Add trustworthyness checklist for apps

CONTENT

- Spell check, content
- Edit Genesis, Write Decentralization
- Content!
- copywriting
- Github project issues
- Ensure correct contributors for each piece of content (git blame)
- i18n 404 redirects, make sure all old pages get redirected properly
- Ensure old site feature parity
- check page metadata, rss feeds and sitemap are correct
- Update Readme
- Disable i18n

PREFLIGHT

- Videos for contributing
- Update url refs from etc3022.netlify
- Lighthouse
- 404 page styling
- remove perf tools from config
- udpade branch settings for agolia plugin
- After banner update, review Social image

~~~ 3022.V1 RELEASE, PUBLIC ~~~

~~~ 3022.V1.1 I18N ~~~

- check all content keys are underscored correctly
- Add comment to all YAML files explaining format __
- i18n contributions flow
- Fix collection localization

~~~ 3022.V1.NEXT ~~~

- Memes
- Turn banners into NFTs
- POAP for contributors
- Check https://github.com/gatsbyjs/themes/issues/93
- images in metadata
```

---

Hello, I am looking for help with a github related task.

I am working on a new version of a website and want to add a list of contributors to a number of markdown/yaml files based on `git blame` of previous versions of the files.

For example, https://github.com/ethereumclassic/ethereumclassic.github.io/blob/3022/content/philosophy/roadmap/index.en.yaml
should include an array of `__contributors` of all the IDs that are contributors of the previous version https://github.com/ethereumclassic/ethereumclassic.github.io/blob/master/content/knowledge/roadmap/timeline.en.yaml AND https://github.com/ethereumclassic/ethereumclassic.github.io-v1/blob/source/components/home/fork-timeline.js

In this case, it would be ["IstoraMandiri", "gitr0nin", "TheEnthusiasticAs", "dax-classix", "arvicco", "philippgille", "realcodywburns", "andyrewlee"]

Markdown example: https://github.com/ethereumclassic/ethereumclassic.github.io/blob/3022/content/philosophy/principles/index.en.md

You can also include your own github id for contributing.

Delivery will be in the form of a pull request to the 3022 branch.