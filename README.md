# docker-desk

Desk for working with docker. It offers command-line shortcuts for working with docker.
For mor information about Desk visit https://github.com/jamesob/desk

## Instalation
Copy the docker.sh to your desk folder.

```
cp docker.sh $HOME/.desk/desks/
```

## Usage
#### 1. Docker Machine

Start the docker machine. Additionally pass a name of machine parameter if different than "default"

```
mstart [name]
```

Get ip of the docker machine.

```
mip [name]
```

Recreate the docker machine.

```
mredo [name]
```

Remove/Destroy the docker machine.

```
mdestroy [name]
```

SSH into the docker machine.

```
mssh [name]
```

List docker machines.

```
mls
```
