# Security-Hardening-Checklist-CLI
Unix/Linux Security Hardening Checklist CLI
==========================================

This command line application generates a Unix/Linux security hardening checklist for IT professionals.

### Usage
-----

* Generate the checklist: `python security_hardening_checklist.py --generate`
* Update the status of a checklist item: `python security_hardening_checklist.py --update <item_number> --status <status>`

### Example
-------

* Generate the checklist:
```bash
$ python security_hardening_checklist.py --generate
Unix/Linux Security Hardening Checklist
---------------------------------------
[NOT_STARTED] Disable unnecessary network services
[NOT_STARTED] Configure firewall rules
...

* Update the checklist:


$ python security_hardening_checklist.py --update 1 --status COMPLETE
Unix/Linux Security Hardening Checklist
---------------------------------------
[COMPLETE] Disable unnecessary network services
[NOT_STARTED] Configure firewall rules
...
