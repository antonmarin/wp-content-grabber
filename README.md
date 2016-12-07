# wp-content-grabber
Content grabber. From developer to developers

## Key features
### common
- easy code
- composer or plugins catalog
- documentation
- open-source
- test importing
- work by cron or manual run
- configurable grab source interval and number of source per run
- examples manual install and on plugin installation
- internationalization
- configurable temporary folder
- php time limit



### sources
- multiple sources
- grab rss feed
  - text from feed
  - text from page
- grab html feed
  - text from feed
  - text from page
  - excerpt from feed?
- grab facebook?
- grab vk?
- grab ok?
- enable/disable source
- source encoding
- reading direction (up-down or down-up)
- reading offset (start from n record)
- limit records count
- unique headings in category
- page parsing
  - start expression
  - end expression
  - page encoding

### posts
- category per source
- type per source and global
- select author?
- create in status(draft or published)
- pre/post processing
  - strip tags
  - select target: source, page(what is grabbed), record(what is parsed), title, excerpt
  - add any callback counts (what about translation?)

#### excerpt
- enable
- add read more
- length
- cut symbol(select or input?)

#### permanent-links
- enable
- translite?
- length

#### images
- grab enable
- skip source records without images
- make first image thumb
- move first image to the beginning of record
- save images on server
  - save path per source or global
  - relative or absolute path to images
- html template of images (in post)
- resize images
  - save proportions
  - crop
- quality
  - save source
  - quality %

#### translation (post process?)
- multiple steps
- yandex api
- google api
- select direction
- add any steps count
- api keys per callbacks or global

#### Unique (post process?)
- enable/disable global or for source
- shuffle paragraphs
- shuffle sentences

### http clients
- guzzle
- file_get_contents
- curl
- CURL-опция: CURLOPT_FOLLOWLOCATION
- connection timeout
