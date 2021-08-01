# hakgzsplit
split lines of text into multiple gzip files

# Install/update

```
go get -u github.com/hakluke/hakgzsplit
```

# Usage

The command below will take 10mhostnames.txt, which contains 10 million hostnames separated by lines, and split it into 10 gzip files called hosts1.gz, hosts2.gz, etc.

```
cat 10mhostnames.txt | hakgzsplit -b 1000000 -f hosts
```
