xrpl
====

Redirectory storage for the Conan package `xrpl`.

```
# Some dependency packages cannot come from Conan Center.
conan remote add --insert 0 ripple http://18.143.149.228:8081/artifactory/api/conan/conan-non-prod
conan remote add github https://conan.jfreeman.dev
conan search --remote github xrpl
conan install --remote github --build missing xrpl/2.1.1@github/thejohnfreeman
```
