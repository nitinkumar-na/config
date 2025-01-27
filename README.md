# config

### New
```bash
curl -fsSL \
https://raw.githubusercontent.com/nitinkumar-na/config/refs/heads/main/bash/.useful_commands \
-o .n
```

###
```
curl -fsSL \
https://raw.githubusercontent.com/nitinkumar-na/config/refs/heads/main/bash/.useful_commands \
-o .bash_aliases && \
grep -qxF 'source $(pwd)/.bash_aliases' .bashrc || \
echo 'source $(pwd)/.bash_aliases' >> .bashrc
```

### Old
```bash
curl -fsSL https://raw.githubusercontent.com/nitinkumar-na/config/refs/heads/main/bash/.useful_commands -o .useful_commands && source ~/.useful_commands
```
