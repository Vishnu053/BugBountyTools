# BugBountyTools
Tools written in Go for BugBounty from [Tomnomnom](https://github.com/tomnomnom), [OJ](https://github.com/OJ), [proabiral](https://github.com/proabiral) and others inside of a docker image. 

Thanks to [heywoodlh](https://github.com/heywoodlh) for his work on integrating this into our workflow!

## Examples:

### [assetfinder](https://github.com/tomnomnom/assetfinder):

```
assetfinder example.com
```

### [gf](https://github.com/tomnomnom/gf):

```
echo '192.168.1.135' | gf ip
```

### [gobuster](https://github.com/OJ/gobuster)
```
gobuster dir -u https://example.com -w /path/to/wordlist
```

### [gron](https://github.com/tomnomnom/gron): 
```
gron "https://api.github.com/repos/tomnomnom/gron/commits?per_page=1"
```

### [httprobe](https://github.com/tomnomnom/httprobe):
```
cat domains.txt | httprobe
```

### [inception](https://github.com/proabiral/inception):
```
inception -d /path/to/domainlist.txt
```

### [meg](https://github.com/tomnomnom/meg):
```
meg /robots.txt domains.txt outputDir

## OR 

meg pathsFile domains.txt outputDir
```


### [unfurl](https://github.com/tomnomnom/unfurl):
```
cat urls.txt | unfurl domains
```

### [waybackurls](https://github.com/tomnomnom/waybackurls):
```
cat domains.txt | waybackurls
```
