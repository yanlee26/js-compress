# one simple tool to compress images by js

> get started

`
npm install js-compress --save-dev

import { CompressImage } from '@/components/utils/CompressImage.js'

let compressImage = new CompressImage()
let maxSize = 200*200
let quality = file.size > maxSize ? 0.5 : 0.9
compressImage.fileResizetoFile(file, quality, response => {
    //...
})
`

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2018-present, Li, Yan