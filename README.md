# OpenEMR Blog

## Front Matter

Add front matter to posts with YAML. This content includes the title, author,
date, slug, summary, images, featured status, etc.

### Images

Images play a key role in sharing your content on social media. To add images
for social media sites to see, add them to your front matter under the `images`
key. For example:

```YAML
images:
    - path/to/image/1.jpg
    - path/to/image/2.jpg
```

Every post contains a featured image. It is either displayed full-width, behind
the title of your post, or just above the title for smaller images. The first
image defined under the `images` tag will be used as your cover image. By
default, the cover image style is `standard` - which will add the image just
above you title. If you wish to use a full width image, set `coverImageStyle` to
`full` in your front matter. 

### Author

The following information for authors should be used:

```YAML
author:
    name: Your Name
    twitter: @your-twitter-handle
    email: your-email@domain.com
```

This allows for better cross-platform sharing.
