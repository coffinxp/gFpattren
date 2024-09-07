## [GF](https://github.com/tomnomnom/gf) By [![Twitter](https://img.shields.io/badge/twitter-@TomNomNom-blue.svg)](https://twitter.com/TomNomNom) 

A wrapper around grep, to help you grep for things 

# installation

[Go Path Setup](https://github.com/golang/go/wiki/SettingGOPATH)

If you've got Go installed and configured you can install `waybackurls & Gf` with:

```bash 

▶ go get -u github.com/tomnomnom/waybackurls
```
```bash
▶ go get -u github.com/tomnomnom/gf
```

If you've installed using `go get`, you can enable auto-completion to your `.bashrc` like this:

```bash
▶ echo 'source $GOPATH/src/github.com/tomnomnom/gf/gf-completion.bash' >> ~/.bashrc
```

Note that you'll have to restart your terminal, or run `source ~/.bashrc` for the changes to
take effect.

To get started quickly, you can copy the example pattern files to `~/.gf` like this:
```bash
▶ mkdir .gf
```
```bash
▶ cp -r $GOPATH/src/github.com/tomnomnom/gf/examples ~/.gf
```
**MY Gf Patterns installation**
```bash
▶ git clone https://github.com/1ndianl33t/Gf-Patterns
```

To get started quickly, you can copy the example pattern files to `~/.gf` like this:
```bash
▶ mkdir .gf
```
```bash
▶ mv ~/GFPattern/*.json ~/.gf
```
**Use example**
```bash

▶ cat subdomains.txt | waybackurls | gf sqli 

▶ cat waybackdata | gau | gf lfi 
```
### Pattern Files

The pattern definitions are stored in `~/.gf` as little JSON files that can be kept under version control:

