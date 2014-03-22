htt
===

HTTrack. `brew install httrack` or `apt-get install httrack` ...

Example: [http://bit.ly/WebDocs][1]

## Usage

### Download the script

```bash
git clone https://github.com/Neson/htt.git
cd htt/
```

### Clone a site

```bash
./htt clone http://somewebsite.com
```

### Browse offline sites

Just open `./index.html` in the browser.

### Update an offline site

```bash
./htt update somewebsite.com
```

### Remove an offline site

```bash
./htt rm somewebsite.com
```
### Edit HTTrack config of a site

```bash
./htt vi somewebsite.com
```

[1]: http://bit.ly/WebDocs