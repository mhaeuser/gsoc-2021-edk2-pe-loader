## GSoC 2021: Integration of a PE/COFF Loader designed with formal methods

For Google Summer of Code 2021, this project aims to introduce a new PE/COFF Image Loader library to the EDK II project maintained by TianoCore. The overall goal is to increase the reliability of UEFI platforms against malformed UEFI images, and to introduce additional security hardening. Detailed information, including a work-in-progress technical documentation, can be found in the [staging branch](https://github.com/tianocore/edk2-staging/tree/2021-gsoc-secure-loader) for the project. Said staging branch contains all changes required to integrate the new library. It still requires work as denoted in the [staging branch README](https://github.com/tianocore/edk2-staging/blob/2021-gsoc-secure-loader/README.md). It is gradually split into individual patches to submit, and is rebased onto the main EDK II branch.

There have been several patches posted that act as prerequisites for an overall successful the integration.

Merged:
* https://github.com/ipxe/ipxe/pull/313
* https://sourceforge.net/p/gnu-efi/code/merge-requests/18/

Staged for merging:
* https://edk2.groups.io/g/devel/message/79318?p=,,,20,0,0,0::recentpostdate%252Fsticky,,Marvin+H%C3%A4user,20,2,0,84909448
* https://edk2.groups.io/g/devel/message/78924?p=,,,20,0,0,0::recentpostdate%252Fsticky,,Marvin+H%C3%A4user,20,2,20,84762964

In discussion:
* https://edk2.groups.io/g/devel/message/78990?p=,,,20,0,0,0::recentpostdate%252Fsticky,,Marvin+H%C3%A4user,20,2,0,84779301
* https://edk2.groups.io/g/devel/message/78880?p=,,,20,0,0,0::recentpostdate%252Fsticky,,Marvin+H%C3%A4user,20,2,40,84754052

Additional changes around the closely related ecosystem, partially submitted, are available at:
* https://github.com/mhaeuser/edk2/branches/all
