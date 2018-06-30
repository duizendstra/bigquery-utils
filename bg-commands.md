bq show --schema --format=prettyjson [dataset.table]

remove whitespace
bq show --schema --format=prettyjson [dataset.table] |  xargs