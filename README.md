# vipm-InstallPackage

use [lvcicd:InstallPackages](https://github.com/LV-APT/lvCICD/blob/main/docs/Operation-List.md#vipm_installpackages--install-vip-by-package-name) to install vipm package.

How to Use it:

```
      - name: vipm-InstallPackage
        uses: NEVSTOP-LAB/vipm-InstallPackage@main
        with:
          LabVIEW_Version: 2017
          # Package could be PackageName/PacakgeWithVersion/vipFilePath
          Package: "NI Tag Bus"
```
