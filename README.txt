# MNG-7852

Steps to reproduce:
cd bom1 && mvn install
cd ..
mvn help:effective-pom

Jupiter 5.10.0 is being used, despite there is latter a BOM import for 5.9.3.

Simply put: latter import is fully IGNORED as same keyed depMgt already exists.

