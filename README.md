# jcorum_delegate_to

```
PLAY [Call a role with delegate] ***********************************************

TASK [include role] ************************************************************
skipping: [node1]
skipping: [node3]

TASK [common : Delegated block of code] ****************************************
ok: [node2] => {
    "msg": "My var is 2222 and this executed on node2"
}

PLAY RECAP *********************************************************************
node1                      : ok=0    changed=0    unreachable=0    failed=0    skipped=1    rescued=0    ignored=0
node2                      : ok=1    changed=0    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
node3                      : ok=0    changed=0    unreachable=0    failed=0    skipped=1    rescued=0    ignored=0
```
