# Australian Women's Weekly data

This dataset includes information about the Australian Women's Weekly harvested from Trove. It was compiled [using this notebook](https://glam-workbench.net/trove-newspapers/harvest-aww-covers-and-newspaper-front-pages/).

## aww-issues.csv

This file includes metadata for 2,566 issues of the Australian Women's Weekly from 1933 to 1982. It contains the following columns:

| Column | Contents |
|--------|----------|
`issue_id` | issue identifier
`date` | issue date (YYYY-MM-DD)
`url` | issue url
`page_id` | identifier of the first page in this issue
`image_file` | file name of downloaded image of front page.


## aww-covers.tar.gz

This file contains images of the covers of all digitised issues of the Australian Women's Weekly in Trove. It can [downloaded from AWS (1.5 GB)](https://glam-workbench.s3.ap-southeast-2.amazonaws.com/aww-covers.tar.gz).