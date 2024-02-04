# Description

ultimate-discovery.txt -> The Ultimate Wordlist for Web Content Discovery

This wordlist contains common file paths and mainly sensitive file paths for specific frameworks, web languages, web servers and CMS', such as:
Nginx, Apache, IIS, Wordpress, Drupal, Django, .NET, symfony, Domino, Lotus, AdobeXML, Apache, CGIs, Common DB backups, Common PHP filenames, Hyperion, JS Miners, Java Servlets, Logins, Oracle App Server, Unix DotFiles, Confluence, Graphql & REST API endpoints, jBoss, PulseSecure, SAP, WebSphere and many more

# Installation & Usage
```
git clone https://github.com/ViktorMares/ultimate_discovery.git
```

## Best used with a tool like dirsearch
```
sudo apt-get install dirsearch
```
```
dirsearch -u https://example.com --exclude-status=404 -w ~/ultimate_discovery.txt
```
![ultimate](https://github.com/ViktorMares/ultimate_discovery/assets/80492489/8c6a6442-0217-4ccc-ab83-4a1afa7ecc03)
