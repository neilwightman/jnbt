JNBT : The Java NBT Library
-----

What is NBT?
----

NBT, or Named Binary Tag, is a file format created by Markus Persson for use with Minecraft
levels. Although originally designed for Minecraft levels, it is appropriate for the vast
majority of use cases.

What is JNBT?
-----

JNBT is a library that can read and write NBT files, originally written in Java by
Graham Edgecombe and available open-source under the BSD license (http://jnbt.sf.net/)
Neil Wightman extended the API to support NBT 19133, TAG_Int_Array.

License
-----

For more information about the license, see LICENSE.TXT.

Building
-----

```bash
git clone git@github.com:neilwightman/jnbt.git
cd jnbt/
mvn clean package
```
