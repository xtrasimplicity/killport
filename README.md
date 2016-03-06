# killport
Simple bash script to kill a process which uses the specified port.

## Installation
Simply make a directory in which to store the script, i.e. ``/opt/scripts/killport``, clone this repository therein, set the script to executable, and add this path your $PATH environment variable, as follows:
```
mkdir -p /opt/scripts/killport && cd /opt/scripts/killport 
git clone https://github.com/xtrasimplicity/killport.git .
chmod +x killport
echo 'export PATH="$PATH:/opt/scripts/killport"' >> ~/.bashrc
source ~/.bashrc
```

## Usage
Simply run killport as follows:

```killport PORT_NUMBER```

i.e. ``killport 3000``

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
