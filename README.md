# killport
Simple bash script to kill a process which uses the specified port.

## Installation
Simply copy ``killport`` to a directory of your choice, say, ``/opt/scripts/killport``, and then add this path to your $PATH. i.e.
```
mkdir -p /opt/scripts/killport && cd /opt/scripts/killport 
git clone https://github.com/xtrasimplicity/killport.git .
echo 'export PATH="$PATH:/opt/scripts/killport"' >> ~/.bashrc
source ~/.bashrc
```

## Usage
Simply run killport as follows:

```killport PORT_NUMBER```

i.e. ``killport 3000``

## Limitations
- Simultaneously terminating multiple processes with the same port number is currently not supported.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
