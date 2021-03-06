# [r/CompetitiveOverwatch](https://reddit.com/r/competitiveoverwatch) CSS & Images

### Building
* Clone the repo
* `yarn`
* `yarn build` to minify images and CSS
    - Alternatively, `yarn css`/`yarn img` individually
* Find minified CSS in `dist/final.css` and compressed images in `dist/images`

### Structure
* CSS: `src/styles.css`
* Raw image files (PSDs): `src/images`
* Exported image files (JPG/PNG): `src/images exported`

### 3rd Party Image Sources
* Main spritesheet – [Naut](https://github.com/Axel--/Naut-for-reddit/blob/master/PSD/spritesheet.psd) with heavy customisations
* Flag spritesheet assembled from [FlagKit flag images](https://github.com/madebybowtie/FlagKit/tree/master/Images)
* [Sidebar Twitter image](https://brand.twitter.com/en.html)

### License
* The following are licensed under the MIT License – see [LICENSE](LICENSE):
    * CSS in `src/styles.css`
    * PSD files and PNG files with the following names (not including file extension):
        + `redditname-2x`
        + `redditname`
        + `tags-check`
        + `tags-heroes`
        + `tags-maps`
        + `thumbnails`

#### 3rd Party Licenses

**Portions of `spritesheet` are licensed under the MIT License:**

```
The MIT License (MIT)

Copyright (c) 2016 Axel Schoterman

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

**`flags-all` and `flags-all-2x` are licensed under the MIT License:**

```
The MIT License (MIT)

Copyright (c) 2016 Bowtie AB

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```