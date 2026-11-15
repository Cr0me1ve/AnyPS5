# libSceAppContent

## add Functional

- [sceAppContentGetAddcontInfoListByIroTag and sceAppContentGetPftFlag](../../../core/libs/prx/libSceAppContent/Export.cpp) (libSceAppContent) - console behavior for unmapped guest output memory is unmeasured; the `hitNum` and PFT flag outputs use `GuestCopyOut_nid_no_patch`, return `PARAMETER` when unwritable, and preserve host `errno`.
