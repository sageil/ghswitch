# ghswitch

---

## Switch github accounts using **ssh** anywhere on your machine.

---

## Requirements

For ghswitch to function, your ssh private key **must have a comment**.
You can add a comment to an ssh private using using `ssh-keygen -c -f path_to_private_key`

## Usage (using an email address as the comment):

### Using short form:

- ghswitch -f=me@host.com -t=me@otherhost.com

### Using long form:

- ghswitch --from=me@host.com --to=me@otherhost.com

### Help

- ghswitch -h

## Compatibility:

ghswitch was tested on macOS ventura, Ubuntu and Almalinux using stand-alone Terminal Emulators and Visual Studio Code terminal emulator.