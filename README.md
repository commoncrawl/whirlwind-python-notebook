# A notebook whirlwind tour of Common Crawl's datasets on AWS

This repo provides an example Amazon Sagemaker notebook showcasing the
Common Crawl Dataset on AWS.

All Common Crawl datasets are hosted on AWS s3 buckets and are
publicly available through `s3` and `https` protocols. To read more
about the data and how to use it, visit
https://commoncrawl.org/get-started. For the command-line version of
this notebook, see https://github.com/commoncrawl/whirlwind-python/

NB: The current version of warcio library (v1.7.5) does not support
direct s3 access. In the meantime, this notebook downloads example
filesets from Common Crawl github repository and works on them
locally.



