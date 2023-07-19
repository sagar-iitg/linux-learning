### Viewing Environment Variables

```
env
printenv
```

### Setting Environment Variables Temporarily
```
export MY_VARIABLE="My Value" 
printenv MY_VARIABLE 

```

### Setting Environment Variables Permanently

#### For system-wide environment variables, edit the /etc/environment file. This file contains a list of key-value pairs, one per line:
```

sudo nano /etc/environment

```

### User-specific Environment Variables

```
nano ~/.profile


```
