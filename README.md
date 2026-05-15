# lsdb.io

Source code for the lsdb.io website.

Links:

- https://lsdb.io/
- https://data.lsdb.io/
- https://github.com/astronomy-commons/data.lsdb.io

### Deploying

To deploy the website, copy the contents of this repository to `/var/www/lsdb.io` on Epyc:

```
$ scp -r ./* <username>@epyc.astro.washington.edu:/var/www/lsdb.io/html
```
