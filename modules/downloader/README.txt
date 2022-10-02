This module provides tools to download file from a URL using HTTP protocol.

* Flow of usage:
- Instantiate a Downloader with a Fetcher
- Use Downloader to download file

* Example:
- Using Fetcher `RequestFetcher`

from downloader import Downloader
from request_fetcher import RequestFetcher

my_downloader = Downloader(RequestFetcher())
my_downloader.download("https://file-to-download", "/tmp/file.downloaded")

- Using Fetcher `WgetFetcher`

from downloader import Downloader
from request_fetcher import WgetFetcher

my_downloader = Downloader(WgetFetcher())
my_downloader.download("https://file-to-download", "/tmp/file.downloaded")

* Exception:
Downloader throws exception, more details, see: class Downloader