# phy-driver-example
Example code of howto add a PHY driver to MEPA (Microchip Ethernet Phy API).
If you have the source code for one of the WebStaX releases, i.e., WebStaX, SMBStaX or IStaX,
then apply the patch. It is suggested that you make a git repo of your source code first:
```
 $ cd path-to-the-root-of-the-source-tree
 $ git init
 $ git add *
 $ git commit -m"Initial version"
```
Then apply the patch
```
 $ patch -p1 < path-to-the-patch/phy_driver_example.patch
```
You can now easily see what and where changes has been made by running:
```
 $ git status
```
and
```
 $ git diff
```
That should give you am idea of where you need to edit when adding a new PHY driver.
