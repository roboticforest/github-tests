# github-tests
For testing how GitHub does things.

## Making Private Forks of Public Repos
Visit [this other repo](https://github.com/roboticforest/private-fork-experiment) of mine for details.

## GitHub Flavored Markdown (GFM)

### Anchor Links

Making an anchor link in GFM is identical to making a regular web link, except that instead of a full URL you just write the archor tag part. For example:
```markdown
Here is some [text displayed as a link](#anchor-tag) as an example.
```
yeilding, Here is some [text displayed as a link](#anchor-tag) as an example.

To work, the anchor tag needs to exist somewhere else within the document, and GitHub takes care of that for you.

In some extended versions of Markdown you can explicitly create your own anchor tags inside a heading like so,
```markdown
# Some Section Title Name {anchor-tag-name}
```
... but this doesn't work on GitHub as it makes anchor tags automatically for you from the words of the headings themselves. If you inspect the element of a given heading in your browser you'll see the generated anchor tag and be able to reference it. Most tags are just the words of your heading, but things are odd with numbers and symbols.

`# A Heading` will create the anchor tag `#a-heading`. However, `# Heading 2.0 - A Complex One` will remove the period in `2.0` while preserving the hyphen `-` appearing mid title, generating the anchor tag `#heading-20---a-complex-one`.

[First Heading](#a-heading)  
[Second Heading](#another-heading)  
[Third Heading](#heading-20---a-complex-one)

Lorem ipsum odor amet, consectetuer adipiscing elit.

Venenatis tempor luctus auctor fermentum per vitae pretium tortor. Suscipit venenatis dictum dui justo quis leo. Vulputate aliquet odio natoque habitasse accumsan a. Ligula montes elementum suspendisse mollis adipiscing dolor.

Sociosqu condimentum enim arcu morbi dictum purus senectus. Ac interdum cras nec ipsum nam lorem lorem torquent. Tempor at natoque pharetra amet penatibus; mattis cras senectus eros.

Dictum nulla ante duis pulvinar tortor.

# A heading

Parturient morbi fusce dui cras dictumst congue venenatis tincidunt. Ac sit faucibus vehicula curabitur pretium odio in. Cubilia mi parturient mi nullam porttitor. Conubia nascetur sem erat quam dis nostra sit per. Risus habitasse sagittis fermentum; amet suscipit taciti.

Risus proin sollicitudin ut erat; proin mauris tempus. Vestibulum dis id tortor erat penatibus lectus netus tempor quam! Per sed maximus fermentum cras elit at felis nisl purus. Elit bibendum montes lacus leo vitae mauris. Ullamcorper velit a inceptos diam aenean diam conubia arcu.

# Another heading

Viverra risus blandit nam eleifend porta velit vulputate. Velit natoque consectetur accumsan quisque dapibus luctus potenti parturient. Cras consequat iaculis egestas turpis aenean tempor suscipit metus. Ad leo litora leo condimentum lectus neque; facilisi dictumst porttitor.

Cras tellus cubilia sodales, viverra eget massa dictum fusce montes. Pellentesque ac sed proin interdum ac duis cursus suspendisse. Enim facilisis vel ad lacus suscipit id. Morbi sollicitudin ullamcorper in feugiat dapibus parturient luctus nulla? Euismod aptent nulla curae tellus tellus.

Turpis mus efficitur egestas placerat sociosqu aliquet odio adipiscing.

# Heading 2.0 - A Complex One

Parturient morbi fusce dui cras dictumst congue venenatis tincidunt. Ac sit faucibus vehicula curabitur pretium odio in. Cubilia mi parturient mi nullam porttitor. Conubia nascetur sem erat quam dis nostra sit per. Risus habitasse sagittis fermentum; amet suscipit taciti.

Risus proin sollicitudin ut erat; proin mauris tempus. Vestibulum dis id tortor erat penatibus lectus netus tempor quam! Per sed maximus fermentum cras elit at felis nisl purus. Elit bibendum montes lacus leo vitae mauris. Ullamcorper velit a inceptos diam aenean diam conubia arcu.

Viverra risus blandit nam eleifend porta velit vulputate. Velit natoque consectetur accumsan quisque dapibus luctus potenti parturient. Cras consequat iaculis egestas turpis aenean tempor suscipit metus. Ad leo litora leo condimentum lectus neque; facilisi dictumst porttitor.

Cras tellus cubilia sodales, viverra eget massa dictum fusce montes. Pellentesque ac sed proin interdum ac duis cursus suspendisse. Enim facilisis vel ad lacus suscipit id. Morbi sollicitudin ullamcorper in feugiat dapibus parturient luctus nulla? Euismod aptent nulla curae tellus tellus.

Turpis mus efficitur egestas placerat sociosqu aliquet odio adipiscing.

Venenatis tempor luctus auctor fermentum per vitae pretium tortor. Suscipit venenatis dictum dui justo quis leo. Vulputate aliquet odio natoque habitasse accumsan a. Ligula montes elementum suspendisse mollis adipiscing dolor.

Sociosqu condimentum enim arcu morbi dictum purus senectus. Ac interdum cras nec ipsum nam lorem lorem torquent. Tempor at natoque pharetra amet penatibus; mattis cras senectus eros.

Dictum nulla ante duis pulvinar tortor.
