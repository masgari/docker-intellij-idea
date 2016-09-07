## Installation
Copy `Dockerfile.xml` to `<YOURIDE_config_folder>/filetypes` and restart your IDE (IDEA / PhpStorm).


#### OS X
```bash
curl --create-dirs -so ~/Library/Preferences/<PRODUCT><VERSION>/filetypes/Dockerfile.xml https://raw.githubusercontent.com/masgari/docker-intellij-idea/master/Dockerfile.xml
```
For *IntelliJIdea2016.2* :
```bash
curl --create-dirs -so ~/Library/Preferences/IntelliJIdea2016.2/filetypes/Dockerfile.xml https://raw.githubusercontent.com/masgari/docker-intellij-idea/master/Dockerfile.xml
```

#### Linux
```bash
wget -O ~/.<PRODUCT><VERSION>/config/filetypes/Dockerfile.xml https://raw.githubusercontent.com/masgari/docker-intellij-idea/master/Dockerfile.xml
```

See https://www.jetbrains.com/help/idea/2016.1/directories-used-by-intellij-idea-to-store-settings-caches-plugins-and-logs.html

## Other products / older versions
### PhpStorm 10
#### Linux
```wget -O ~/.WebIde10/config/filetypes/Dockerfile.xml https://raw.githubusercontent.com/masgari/docker-intellij-idea/master/Dockerfile.xml```
https://raw.githubusercontent.com/masgari/docker-intellij-idea/master/Dockerfile.xml

#### OS X
```bash
curl --create-dirs -so ~/Library/Preferences/WebIde100/filetypes/Dockerfile.xml https://raw.githubusercontent.com/masgari/docker-intellij-idea/master/Dockerfile.xml
```

#### Windows
Download `https://raw.githubusercontent.com/masgari/docker-intellij-idea/master/Dockerfile.xml` and copy it to:
`<User home>\.WebIdeXX\config\filetypes\` folder (you may have to create the filetypes folder)
