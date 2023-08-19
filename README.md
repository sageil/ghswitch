# ghswitch

---

## Switch github accounts using **ssh** anywhere on your machine.

---

## Requirements

For ghswitch to function, your ssh private key **must have a comment**.
You can add a comment to an existing ssh private key using using

```sh
ssh-keygen -c -f ~/.ssh/private_key
```

### Installation

#### The installation instruction assumes `/usr/local/bin/` is part of your shell's `$PATH` environment variable.

Using curl:

```sh
sudo curl -L -o /usr/local/bin/ghswitch https://raw.githubusercontent.com/sageil/ghswitch/main/ghswitch && sudo chmod +x /usr/local/bin/ghswitch
```

Using wget:

```sh
sudo wget -O /usr/local/bin/ghswitch https://raw.githubusercontent.com/sageil/ghswitch/main/ghswitch && sudo chmod +x /usr/local/bin/ghswitch
```

## Usage (using an email address as the comment):

### Using short form:

- ghswitch -f=me@host.com -t=me@otherhost.com

### Using long form:

- ghswitch --from=me@host.com --to=me@otherhost.com

### Help

- ghswitch -h

## Compatibility:

ghswitch was tested on macOS ventura, Ubuntu and Almalinux using stand-alone Terminal Emulators and Visual Studio Code terminal.
