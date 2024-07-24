See my Homepage in [Deno-V.github.io](https://deno-v.github.io) !

This is a Personal HomePage modified from academicpages/academicpages.github.io

Here are some changes I made:
1. Modified navigation.yml/nav.list to adjust the order, removed unnecessary content, added an About, and included Chinese content navigation.
2. Adjusted archive-single.html to allow images to be displayed and removed the "published" label to support arXiv, displaying it on the publications page. (archive-single is used to display each item in publications page)
3. Changed the sorting method for publications to ensure sorting by a specified field (post.date). Applied the publications sorting to the About Me and CV page and publication page.
4. About Me page and CV page list publications in a custom way in singleitem.html (replace archive-single-cv.html)
5. Modified the implementation of the download links, citations, etc., in archive-single.html to make it more flexible.
6. Defined new pattern for every md file in publication files (these markdown files in publications use single.html as layout, I simply change the pattern in md file not in single to avoid cross influence)