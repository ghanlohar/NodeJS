# NodeJS
Node Architecture
-------------------

NPM
----------------
package.json
-------------------
1. This will hold the dependency package details like name, version

Semanic versioning
---------------------
A.B.C
1. A  ==> major vesion    ===> Breaking changes
2. B  ==> minor version   ===> Backward compatiblity
3. C  ==> Patch           ===> Bug fixes

4. ^ means --- update can install recent minor version (^1.3.2 -- update will intstall minor version greater or equal to 3 in this case)
5. ~ means --- update can install recent patch (~1.3.2 -- update will intstall patch version greater or equal to 2 in this case)
6. To check matching version (https://semver.npmjs.com)

package-lock.json
------------------------
help tracking the hierarchy of the package used with the exact version.



