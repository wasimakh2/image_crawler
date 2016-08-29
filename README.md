Image Crawler
==========================

#### An image crawler with Python 2.7.
It's a forked project of [Bulk-Bing-Image-downloader](https://github.com/gadelat/Bulk-Bing-Image-downloader). With this tool, you can crawl *full-sized images*.

This tool supports the following search engines and databases
- Bing (default)
- Google (API key and search engine ID are necessary)
- ImageNet

Features
- UTF-8 support (tested on Linux env.)
- Multi-threaded downloads
- Check image headers and don't download corrupted files (e.g. HTML error messages)
- Keep source URLs (in a pickle file)


### Important
*Use of the crawled images must be abide by the license of the original URLs.*

### Usage
```
chmod +x downloader.py
./downloader.py [-h] [-s SEARCH_STRING] [-f SEARCH_FILE] [-o OUTPUT] [--no-filter] [-e SEARCH_ENGINE]
```
### Example
`./downloader.py -s earth`
