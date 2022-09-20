---
ns: PED
---
## GET_PED_LAST_DAMAGE_BONE

```c
// 0xD75960F6BD9EA49C 0xAB933841
BOOL GET_PED_LAST_DAMAGE_BONE(Ped ped, int* outBone);
```

## Parameters
* **ped**: The ped handle

## Return value
* **retval**: Returns 1 if the ped has received damage, 0 if it has'nt.
* **outBone**: The bone ID of the ped.

For the bone type, you can check the corresponding ID here:
https://wiki.gtanet.work/index.php?title=Bones

