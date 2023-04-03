# uberspace

common uberspace tasks

## Mail

`uberspace mail domain list`

`uberspace mail domain add domain.de`

`uberspace mail domain del domain.de`

### Mail Adressen erstellen

`uberspace mail user add info`

`uberspace mail user list`

---

## Multiple Domains

### 1. Domain Setup

`uberspace web domain add domain.de`
`uberspace web domain add www.domain.de`

`uberspace web domain list`
`uberspace web domain remove domain.de`

### 2. Create Folder

```
cd /var/www/virtual/USERNAME/html
mkdir domain.de
```

### 3. Create Links

```
cd /var/www/virtual/USERNAME
ln -s html/domain.de domain.de
ln -s html/domain.de www.domain.de
```

---

## For Kirby CMS

set ln to "public" folder
check .htaccess in public folder if RewriteBase / is correct
