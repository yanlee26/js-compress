# one simple tool to compress files by js

> get started

```//js

npm install js-compress --save-dev

import { jsCompress } from 'JsCompress'

let jsCompress = new jsCompress()
let maxSize = 200*200
let quality = file.size > maxSize ? 0.5 : 0.9
jsCompress.fileResizetoFile(file, quality, response => {
    //...
})

```


## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2018-present, Li, Yan
