# GOAD-Mini (Game of Active Directory)

The smallest GOAD lab by [Orange Cyberdefense](https://github.com/Orange-Cyberdefense/GOAD): one
domain (sevenkingdoms.local) on one Windows Server 2019 domain controller, KINGSLANDING. This
repository runs it with [Isoloom](https://www.isoloom.com): [`isoloom.yml`](isoloom.yml) describes
the machine, and GOAD's own Ansible playbooks build the lab from a controller.

## Run it

```bash
isoloom generate
cd .isoloom/vagrant && vagrant up
```

About 3 GB of memory plus 1 GB for the controller. Lab guide: the
[GOAD documentation](https://orange-cyberdefense.github.io/GOAD/).

## Licence

GPL-3.0, as GOAD ([LICENSE](LICENSE)). This lab is deliberately vulnerable: keep it isolated.
