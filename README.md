# MagentoPatches
Makes easy clone and apply a a Magento Patches


To apply a Patch, please upload the patch into your Magento root directory and run the appropriate SSH command:

For patch files with the file extension .sh:
sh patch_file_name.sh

Example: sh PATCH_SUPEE-1868_CE_1.7.0.2_v1.sh
For patch files with the file extension .patch:
patch –p0 < patch_file_name.patch

Once that is done, refresh the cache in the Admin under "System > Cache Management" so that the changes will be reflected. We highly recommend you test all patches in a test environment before taking them live.
For further instructions, see our gide: [HowToInstall](https://github.com/rockdrigo/MagentoPatches/tree/master/HowToInstall)