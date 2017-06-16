# ipa_check_consistency
The tool checks consistency across FreeIPA servers.

It can also be used as a Nagios/Opsview plug-in (check -n, -w and -c  options).

The tool has been tested in FreeIPA 4.2/4.3/4.4 (Centos 7.2/7.3, Fedora 24) environments.

## Requirements:
* FreeIPA 4.2 or higher
* Python2.7 or Python3.5+
* python modules: pyYAML, tabular, six, pyldap

## Installation:
```
python setup.py install [--user]
```

Any comments and improvement ideas are welcome.

## Testing
Install and run `tox`

```
$ pip install tox
$ tox
