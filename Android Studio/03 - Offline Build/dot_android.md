# Directory structure of .android folder

DIRECTORY STRUCTURE
-------------------

```
.android
|   adbkey
|   adbkey.pub
|   analytics.settings
|   build-cache.lock
|   debug.keystore
|   debug.keystore.lock
|   emu-last-feature-flags.protobuf
|   emu-update-last-check.ini
|   maps.key
|   modem-nv-ram-5554
|   Resultant.txt
|   
+---avd
|   |   Nexus_5X_API_27.ini
|   |   
|   \---Nexus_5X_API_27.avd
|       |   AVD.conf
|       |   cache.img
|       |   cache.img.qcow2
|       |   config.ini
|       |   emu-launch-params.txt
|       |   emulator-user.ini
|       |   encryptionkey.img
|       |   encryptionkey.img.qcow2
|       |   hardware-qemu.ini
|       |   multiinstance.lock
|       |   quickbootChoice.ini
|       |   read-snapshot.txt
|       |   sdcard.img
|       |   sdcard.img.qcow2
|       |   userdata-qemu.img
|       |   userdata-qemu.img.qcow2
|       |   userdata.img
|       |   version_num.cache
|       |   
|       +---data
|       |   \---misc
|       |       \---pstore
|       |               pstore.bin
|       |               
|       +---snapshots
|       |   \---default_boot
|       |           ram.img
|       |           snapshot.pb
|       |           
|       \---tmpAdbCmds
|               adbcommand2200bdcd-eedb-4fe2-86cc-e028e1ca68b1
|               adbcommandc3986bf6-3934-4523-83d2-79fc6a193162
|               
+---breakpad
+---build-cache
|   |   3.5.0.lock
|   |   
|   \---3.5.0
|           .cache-eviction-marker
|           .cache-use-marker
|           
+---cache
|       sdkbin-1_027553a3-sys-img2-1_xml
|       sdkbin-1_21774538-addon2-1_xml
|       sdkbin-1_48262a29-sys-img2-1_xml
|       sdkbin-1_53d0da2b-addon2-1_xml
|       sdkbin-1_6dabee33-sys-img2-1_xml
|       sdkbin-1_70436d91-sys-img2-1_xml
|       sdkbin-1_725a2f81-sys-img2-1_xml
|       sdkbin-1_754d6006-sys-img2-1_xml
|       sdkbin-1_b735609c-repository2-1_xml
|       sdkbin-1_d1bcd755-sys-img2-1_xml
|       sdkbin-1_d29da320-addons_list-3_xml
|       sdkbin-1_d79225ab-addon2-1_xml
|       sdkinf-1_027553a3-sys-img2-1_xml
|       sdkinf-1_21774538-addon2-1_xml
|       sdkinf-1_48262a29-sys-img2-1_xml
|       sdkinf-1_53d0da2b-addon2-1_xml
|       sdkinf-1_6dabee33-sys-img2-1_xml
|       sdkinf-1_70436d91-sys-img2-1_xml
|       sdkinf-1_725a2f81-sys-img2-1_xml
|       sdkinf-1_754d6006-sys-img2-1_xml
|       sdkinf-1_b735609c-repository2-1_xml
|       sdkinf-1_d1bcd755-sys-img2-1_xml
|       sdkinf-1_d29da320-addons_list-3_xml
|       sdkinf-1_d79225ab-addon2-1_xml
|       
+---manual-offline-m2
|   |   README
|   |   
|   +---androidx
|   |   \---databinding
|   |       +---databinding-common
|   |       |   \---3.5.0-beta01
|   |       |           databinding-common-3.5.0-beta01-javadoc.jar
|   |       |           databinding-common-3.5.0-beta01-sources.jar
|   |       |           databinding-common-3.5.0-beta01.jar
|   |       |           databinding-common-3.5.0-beta01.pom
|   |       |           
|   |       +---databinding-compiler
|   |       |   \---3.5.0-beta01
|   |       |           databinding-compiler-3.5.0-beta01-javadoc.jar
|   |       |           databinding-compiler-3.5.0-beta01-sources.jar
|   |       |           databinding-compiler-3.5.0-beta01.jar
|   |       |           databinding-compiler-3.5.0-beta01.pom
|   |       |           
|   |       \---databinding-compiler-common
|   |           \---3.5.0-beta01
|   |                   databinding-compiler-common-3.5.0-beta01-javadoc.jar
|   |                   databinding-compiler-common-3.5.0-beta01-sources.jar
|   |                   databinding-compiler-common-3.5.0-beta01.jar
|   |                   databinding-compiler-common-3.5.0-beta01.pom
|   |                   
|   +---com
|   |   +---android
|   |   |   +---databinding
|   |   |   |   \---baseLibrary
|   |   |   |       \---3.5.0-beta01
|   |   |   |               baseLibrary-3.5.0-beta01-javadoc.jar
|   |   |   |               baseLibrary-3.5.0-beta01-sources.jar
|   |   |   |               baseLibrary-3.5.0-beta01.jar
|   |   |   |               baseLibrary-3.5.0-beta01.pom
|   |   |   |               
|   |   |   +---java
|   |   |   |   \---tools
|   |   |   |       \---build
|   |   |   |           +---java-lib-model
|   |   |   |           |   \---3.5.0-beta01
|   |   |   |           |           java-lib-model-3.5.0-beta01-javadoc.jar
|   |   |   |           |           java-lib-model-3.5.0-beta01-sources.jar
|   |   |   |           |           java-lib-model-3.5.0-beta01.jar
|   |   |   |           |           java-lib-model-3.5.0-beta01.pom
|   |   |   |           |           
|   |   |   |           \---java-lib-model-builder
|   |   |   |               \---3.5.0-beta01
|   |   |   |                       java-lib-model-builder-3.5.0-beta01-javadoc.jar
|   |   |   |                       java-lib-model-builder-3.5.0-beta01-sources.jar
|   |   |   |                       java-lib-model-builder-3.5.0-beta01.jar
|   |   |   |                       java-lib-model-builder-3.5.0-beta01.pom
|   |   |   |                       
|   |   |   \---tools
|   |   |       +---analytics-library
|   |   |       |   +---crash
|   |   |       |   |   \---26.5.0-beta01
|   |   |       |   |           crash-26.5.0-beta01-javadoc.jar
|   |   |       |   |           crash-26.5.0-beta01-sources.jar
|   |   |       |   |           crash-26.5.0-beta01.jar
|   |   |       |   |           crash-26.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   +---protos
|   |   |       |   |   \---26.5.0-beta01
|   |   |       |   |           protos-26.5.0-beta01-javadoc.jar
|   |   |       |   |           protos-26.5.0-beta01-sources.jar
|   |   |       |   |           protos-26.5.0-beta01.jar
|   |   |       |   |           protos-26.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   +---shared
|   |   |       |   |   \---26.5.0-beta01
|   |   |       |   |           shared-26.5.0-beta01-javadoc.jar
|   |   |       |   |           shared-26.5.0-beta01-sources.jar
|   |   |       |   |           shared-26.5.0-beta01.jar
|   |   |       |   |           shared-26.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   \---tracker
|   |   |       |       \---26.5.0-beta01
|   |   |       |               tracker-26.5.0-beta01-javadoc.jar
|   |   |       |               tracker-26.5.0-beta01-sources.jar
|   |   |       |               tracker-26.5.0-beta01.jar
|   |   |       |               tracker-26.5.0-beta01.pom
|   |   |       |               
|   |   |       +---annotations
|   |   |       |   \---26.5.0-beta01
|   |   |       |           annotations-26.5.0-beta01-javadoc.jar
|   |   |       |           annotations-26.5.0-beta01-sources.jar
|   |   |       |           annotations-26.5.0-beta01.jar
|   |   |       |           annotations-26.5.0-beta01.pom
|   |   |       |           
|   |   |       +---build
|   |   |       |   +---aapt2
|   |   |       |   |   \---3.5.0-beta01-5435860
|   |   |       |   |           aapt2-3.5.0-beta01-5435860-linux.jar
|   |   |       |   |           aapt2-3.5.0-beta01-5435860-osx.jar
|   |   |       |   |           aapt2-3.5.0-beta01-5435860-windows.jar
|   |   |       |   |           
|   |   |       |   +---aapt2-proto
|   |   |       |   |   \---0.4.0
|   |   |       |   |           aapt2-proto-0.4.0.jar
|   |   |       |   |           aapt2-proto-0.4.0.pom
|   |   |       |   |           NOTICE
|   |   |       |   |           
|   |   |       |   +---apksig
|   |   |       |   |   \---3.5.0-beta01
|   |   |       |   |           apksig-3.5.0-beta01-javadoc.jar
|   |   |       |   |           apksig-3.5.0-beta01-sources.jar
|   |   |       |   |           apksig-3.5.0-beta01.jar
|   |   |       |   |           apksig-3.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   +---apkzlib
|   |   |       |   |   \---3.5.0-beta01
|   |   |       |   |           apkzlib-3.5.0-beta01-javadoc.jar
|   |   |       |   |           apkzlib-3.5.0-beta01-sources.jar
|   |   |       |   |           apkzlib-3.5.0-beta01.jar
|   |   |       |   |           apkzlib-3.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   +---builder
|   |   |       |   |   \---3.5.0-beta01
|   |   |       |   |           builder-3.5.0-beta01-javadoc.jar
|   |   |       |   |           builder-3.5.0-beta01-sources.jar
|   |   |       |   |           builder-3.5.0-beta01.jar
|   |   |       |   |           builder-3.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   +---builder-model
|   |   |       |   |   \---3.5.0-beta01
|   |   |       |   |           builder-model-3.5.0-beta01-javadoc.jar
|   |   |       |   |           builder-model-3.5.0-beta01-sources.jar
|   |   |       |   |           builder-model-3.5.0-beta01.jar
|   |   |       |   |           builder-model-3.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   +---builder-test-api
|   |   |       |   |   \---3.5.0-beta01
|   |   |       |   |           builder-test-api-3.5.0-beta01-javadoc.jar
|   |   |       |   |           builder-test-api-3.5.0-beta01-sources.jar
|   |   |       |   |           builder-test-api-3.5.0-beta01.jar
|   |   |       |   |           builder-test-api-3.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   +---bundletool
|   |   |       |   |   \---0.9.0
|   |   |       |   |           bundletool-0.9.0.jar
|   |   |       |   |           bundletool-0.9.0.pom
|   |   |       |   |           NOTICE
|   |   |       |   |           
|   |   |       |   +---gradle
|   |   |       |   |   \---3.5.0-beta01
|   |   |       |   |           gradle-3.5.0-beta01-javadoc.jar
|   |   |       |   |           gradle-3.5.0-beta01-sources.jar
|   |   |       |   |           gradle-3.5.0-beta01.jar
|   |   |       |   |           gradle-3.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   +---gradle-api
|   |   |       |   |   \---3.5.0-beta01
|   |   |       |   |           gradle-api-3.5.0-beta01-javadoc.jar
|   |   |       |   |           gradle-api-3.5.0-beta01-sources.jar
|   |   |       |   |           gradle-api-3.5.0-beta01.jar
|   |   |       |   |           gradle-api-3.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   +---jetifier
|   |   |       |   |   +---jetifier-core
|   |   |       |   |   |   \---1.0.0-beta04
|   |   |       |   |   |           jetifier-core-1.0.0-beta04.jar
|   |   |       |   |   |           jetifier-core-1.0.0-beta04.pom
|   |   |       |   |   |           NOTICE
|   |   |       |   |   |           
|   |   |       |   |   \---jetifier-processor
|   |   |       |   |       \---1.0.0-beta04
|   |   |       |   |               jetifier-processor-1.0.0-beta04.jar
|   |   |       |   |               jetifier-processor-1.0.0-beta04.pom
|   |   |       |   |               NOTICE
|   |   |       |   |               
|   |   |       |   +---manifest-merger
|   |   |       |   |   \---26.5.0-beta01
|   |   |       |   |           manifest-merger-26.5.0-beta01-javadoc.jar
|   |   |       |   |           manifest-merger-26.5.0-beta01-sources.jar
|   |   |       |   |           manifest-merger-26.5.0-beta01.jar
|   |   |       |   |           manifest-merger-26.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   \---transform-api
|   |   |       |       \---2.0.0-deprecated-use-gradle-api
|   |   |       |               NOTICE
|   |   |       |               transform-api-2.0.0-deprecated-use-gradle-api.jar
|   |   |       |               transform-api-2.0.0-deprecated-use-gradle-api.pom
|   |   |       |               
|   |   |       +---common
|   |   |       |   \---26.5.0-beta01
|   |   |       |           common-26.5.0-beta01-javadoc.jar
|   |   |       |           common-26.5.0-beta01-sources.jar
|   |   |       |           common-26.5.0-beta01.jar
|   |   |       |           common-26.5.0-beta01.pom
|   |   |       |           
|   |   |       +---ddms
|   |   |       |   \---ddmlib
|   |   |       |       \---26.5.0-beta01
|   |   |       |               ddmlib-26.5.0-beta01-javadoc.jar
|   |   |       |               ddmlib-26.5.0-beta01-sources.jar
|   |   |       |               ddmlib-26.5.0-beta01.jar
|   |   |       |               ddmlib-26.5.0-beta01.pom
|   |   |       |               
|   |   |       +---dvlib
|   |   |       |   \---26.5.0-beta01
|   |   |       |           dvlib-26.5.0-beta01-javadoc.jar
|   |   |       |           dvlib-26.5.0-beta01-sources.jar
|   |   |       |           dvlib-26.5.0-beta01.jar
|   |   |       |           dvlib-26.5.0-beta01.pom
|   |   |       |           
|   |   |       +---external
|   |   |       |   +---com-intellij
|   |   |       |   |   +---intellij-core
|   |   |       |   |   |   \---26.5.0-beta01
|   |   |       |   |   |           intellij-core-26.5.0-beta01-javadoc.jar
|   |   |       |   |   |           intellij-core-26.5.0-beta01-sources.jar
|   |   |       |   |   |           intellij-core-26.5.0-beta01.jar
|   |   |       |   |   |           intellij-core-26.5.0-beta01.pom
|   |   |       |   |   |           
|   |   |       |   |   \---kotlin-compiler
|   |   |       |   |       \---26.5.0-beta01
|   |   |       |   |               kotlin-compiler-26.5.0-beta01-javadoc.jar
|   |   |       |   |               kotlin-compiler-26.5.0-beta01-sources.jar
|   |   |       |   |               kotlin-compiler-26.5.0-beta01.jar
|   |   |       |   |               kotlin-compiler-26.5.0-beta01.pom
|   |   |       |   |               
|   |   |       |   \---org-jetbrains
|   |   |       |       \---uast
|   |   |       |           \---26.5.0-beta01
|   |   |       |                   uast-26.5.0-beta01-javadoc.jar
|   |   |       |                   uast-26.5.0-beta01-sources.jar
|   |   |       |                   uast-26.5.0-beta01.jar
|   |   |       |                   uast-26.5.0-beta01.pom
|   |   |       |                   
|   |   |       +---layoutlib
|   |   |       |   \---layoutlib-api
|   |   |       |       \---26.5.0-beta01
|   |   |       |               layoutlib-api-26.5.0-beta01-javadoc.jar
|   |   |       |               layoutlib-api-26.5.0-beta01-sources.jar
|   |   |       |               layoutlib-api-26.5.0-beta01.jar
|   |   |       |               layoutlib-api-26.5.0-beta01.pom
|   |   |       |               
|   |   |       +---lint
|   |   |       |   +---lint
|   |   |       |   |   \---26.5.0-beta01
|   |   |       |   |           lint-26.5.0-beta01-javadoc.jar
|   |   |       |   |           lint-26.5.0-beta01-sources.jar
|   |   |       |   |           lint-26.5.0-beta01.jar
|   |   |       |   |           lint-26.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   +---lint-api
|   |   |       |   |   \---26.5.0-beta01
|   |   |       |   |           lint-api-26.5.0-beta01-javadoc.jar
|   |   |       |   |           lint-api-26.5.0-beta01-sources.jar
|   |   |       |   |           lint-api-26.5.0-beta01.jar
|   |   |       |   |           lint-api-26.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   +---lint-checks
|   |   |       |   |   \---26.5.0-beta01
|   |   |       |   |           lint-checks-26.5.0-beta01-javadoc.jar
|   |   |       |   |           lint-checks-26.5.0-beta01-sources.jar
|   |   |       |   |           lint-checks-26.5.0-beta01.jar
|   |   |       |   |           lint-checks-26.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   +---lint-gradle
|   |   |       |   |   \---26.5.0-beta01
|   |   |       |   |           lint-gradle-26.5.0-beta01-javadoc.jar
|   |   |       |   |           lint-gradle-26.5.0-beta01-sources.jar
|   |   |       |   |           lint-gradle-26.5.0-beta01.jar
|   |   |       |   |           lint-gradle-26.5.0-beta01.pom
|   |   |       |   |           
|   |   |       |   \---lint-gradle-api
|   |   |       |       \---26.5.0-beta01
|   |   |       |               lint-gradle-api-26.5.0-beta01-javadoc.jar
|   |   |       |               lint-gradle-api-26.5.0-beta01-sources.jar
|   |   |       |               lint-gradle-api-26.5.0-beta01.jar
|   |   |       |               lint-gradle-api-26.5.0-beta01.pom
|   |   |       |               
|   |   |       +---repository
|   |   |       |   \---26.5.0-beta01
|   |   |       |           repository-26.5.0-beta01-javadoc.jar
|   |   |       |           repository-26.5.0-beta01-sources.jar
|   |   |       |           repository-26.5.0-beta01.jar
|   |   |       |           repository-26.5.0-beta01.pom
|   |   |       |           
|   |   |       +---sdk-common
|   |   |       |   \---26.5.0-beta01
|   |   |       |           sdk-common-26.5.0-beta01-javadoc.jar
|   |   |       |           sdk-common-26.5.0-beta01-sources.jar
|   |   |       |           sdk-common-26.5.0-beta01.jar
|   |   |       |           sdk-common-26.5.0-beta01.pom
|   |   |       |           
|   |   |       \---sdklib
|   |   |           \---26.5.0-beta01
|   |   |                   sdklib-26.5.0-beta01-javadoc.jar
|   |   |                   sdklib-26.5.0-beta01-sources.jar
|   |   |                   sdklib-26.5.0-beta01.jar
|   |   |                   sdklib-26.5.0-beta01.pom
|   |   |                   
|   |   +---google
|   |   |   +---auto
|   |   |   |   +---auto-parent
|   |   |   |   |   \---3
|   |   |   |   |           auto-parent-3.pom
|   |   |   |   |           
|   |   |   |   \---value
|   |   |   |       \---auto-value
|   |   |   |           \---1.5.2
|   |   |   |                   auto-value-1.5.2.jar
|   |   |   |                   auto-value-1.5.2.pom
|   |   |   |                   NOTICE
|   |   |   |                   
|   |   |   +---code
|   |   |   |   +---findbugs
|   |   |   |   |   \---jsr305
|   |   |   |   |       \---3.0.2
|   |   |   |   |               jsr305-3.0.2.jar
|   |   |   |   |               jsr305-3.0.2.pom
|   |   |   |   |               NOTICE
|   |   |   |   |               
|   |   |   |   \---gson
|   |   |   |       +---gson
|   |   |   |       |   \---2.8.0
|   |   |   |       |           gson-2.8.0.jar
|   |   |   |       |           gson-2.8.0.pom
|   |   |   |       |           NOTICE
|   |   |   |       |           
|   |   |   |       \---gson-parent
|   |   |   |           \---2.8.0
|   |   |   |                   gson-parent-2.8.0.pom
|   |   |   |                   
|   |   |   +---errorprone
|   |   |   |   +---error_prone_annotations
|   |   |   |   |   +---2.2.0
|   |   |   |   |   |       error_prone_annotations-2.2.0.jar
|   |   |   |   |   |       error_prone_annotations-2.2.0.pom
|   |   |   |   |   |       NOTICE
|   |   |   |   |   |       
|   |   |   |   |   \---2.3.1
|   |   |   |   |           error_prone_annotations-2.3.1.jar
|   |   |   |   |           error_prone_annotations-2.3.1.pom
|   |   |   |   |           NOTICE
|   |   |   |   |           
|   |   |   |   \---error_prone_parent
|   |   |   |       +---2.2.0
|   |   |   |       |       error_prone_parent-2.2.0.pom
|   |   |   |       |       
|   |   |   |       \---2.3.1
|   |   |   |               error_prone_parent-2.3.1.pom
|   |   |   |               
|   |   |   +---google
|   |   |   |   \---1
|   |   |   |           google-1.pom
|   |   |   |           
|   |   |   +---guava
|   |   |   |   +---failureaccess
|   |   |   |   |   \---1.0.1
|   |   |   |   |           failureaccess-1.0.1.jar
|   |   |   |   |           failureaccess-1.0.1.pom
|   |   |   |   |           NOTICE
|   |   |   |   |           
|   |   |   |   +---guava
|   |   |   |   |   \---27.0.1-jre
|   |   |   |   |           guava-27.0.1-jre.jar
|   |   |   |   |           guava-27.0.1-jre.pom
|   |   |   |   |           NOTICE
|   |   |   |   |           
|   |   |   |   +---guava-parent
|   |   |   |   |   +---26.0-android
|   |   |   |   |   |       guava-parent-26.0-android.pom
|   |   |   |   |   |       
|   |   |   |   |   \---27.0.1-jre
|   |   |   |   |           guava-parent-27.0.1-jre.pom
|   |   |   |   |           
|   |   |   |   \---listenablefuture
|   |   |   |       \---9999.0-empty-to-avoid-conflict-with-guava
|   |   |   |               listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.jar
|   |   |   |               listenablefuture-9999.0-empty-to-avoid-conflict-with-guava.pom
|   |   |   |               NOTICE
|   |   |   |               
|   |   |   +---j2objc
|   |   |   |   \---j2objc-annotations
|   |   |   |       \---1.1
|   |   |   |               j2objc-annotations-1.1.jar
|   |   |   |               j2objc-annotations-1.1.pom
|   |   |   |               NOTICE
|   |   |   |               
|   |   |   +---jimfs
|   |   |   |   +---jimfs
|   |   |   |   |   \---1.1
|   |   |   |   |           jimfs-1.1.jar
|   |   |   |   |           jimfs-1.1.pom
|   |   |   |   |           NOTICE
|   |   |   |   |           
|   |   |   |   \---jimfs-parent
|   |   |   |       \---1.1
|   |   |   |               jimfs-parent-1.1.pom
|   |   |   |               
|   |   |   \---protobuf
|   |   |       +---protobuf-java
|   |   |       |   \---3.4.0
|   |   |       |           NOTICE
|   |   |       |           protobuf-java-3.4.0.jar
|   |   |       |           protobuf-java-3.4.0.pom
|   |   |       |           
|   |   |       +---protobuf-java-util
|   |   |       |   \---3.4.0
|   |   |       |           NOTICE
|   |   |       |           protobuf-java-util-3.4.0.jar
|   |   |       |           protobuf-java-util-3.4.0.pom
|   |   |       |           
|   |   |       \---protobuf-parent
|   |   |           \---3.4.0
|   |   |                   protobuf-parent-3.4.0.pom
|   |   |                   
|   |   +---googlecode
|   |   |   +---json-simple
|   |   |   |   \---json-simple
|   |   |   |       \---1.1
|   |   |   |               json-simple-1.1.jar
|   |   |   |               json-simple-1.1.pom
|   |   |   |               NOTICE
|   |   |   |               
|   |   |   \---juniversalchardet
|   |   |       \---juniversalchardet
|   |   |           \---1.0.3
|   |   |                   juniversalchardet-1.0.3.jar
|   |   |                   juniversalchardet-1.0.3.pom
|   |   |                   NOTICE
|   |   |                   
|   |   +---squareup
|   |   |   +---javapoet
|   |   |   |   \---1.8.0
|   |   |   |           javapoet-1.8.0.jar
|   |   |   |           javapoet-1.8.0.pom
|   |   |   |           NOTICE
|   |   |   |           
|   |   |   \---javawriter
|   |   |       \---2.5.0
|   |   |               javawriter-2.5.0.jar
|   |   |               javawriter-2.5.0.pom
|   |   |               NOTICE
|   |   |               
|   |   \---sun
|   |       +---activation
|   |       |   +---all
|   |       |   |   \---1.2.0
|   |       |   |           all-1.2.0.pom
|   |       |   |           
|   |       |   \---javax.activation
|   |       |       \---1.2.0
|   |       |               javax.activation-1.2.0.jar
|   |       |               javax.activation-1.2.0.pom
|   |       |               NOTICE
|   |       |               
|   |       +---istack
|   |       |   +---istack-commons
|   |       |   |   \---2.21
|   |       |   |           istack-commons-2.21.pom
|   |       |   |           
|   |       |   \---istack-commons-runtime
|   |       |       \---2.21
|   |       |               istack-commons-runtime-2.21.jar
|   |       |               istack-commons-runtime-2.21.pom
|   |       |               NOTICE
|   |       |               
|   |       \---xml
|   |           +---bind
|   |           |   +---jaxb-bom-ext
|   |           |   |   \---2.2.11
|   |           |   |           jaxb-bom-ext-2.2.11.pom
|   |           |   |           
|   |           |   \---mvn
|   |           |       +---jaxb-parent
|   |           |       |   \---2.2.11
|   |           |       |           jaxb-parent-2.2.11.pom
|   |           |       |           
|   |           |       +---jaxb-runtime-parent
|   |           |       |   \---2.2.11
|   |           |       |           jaxb-runtime-parent-2.2.11.pom
|   |           |       |           
|   |           |       \---jaxb-txw-parent
|   |           |           \---2.2.11
|   |           |                   jaxb-txw-parent-2.2.11.pom
|   |           |                   
|   |           \---fastinfoset
|   |               +---FastInfoset
|   |               |   \---1.2.13
|   |               |           FastInfoset-1.2.13.jar
|   |               |           FastInfoset-1.2.13.pom
|   |               |           NOTICE
|   |               |           
|   |               \---fastinfoset-project
|   |                   \---1.2.13
|   |                           fastinfoset-project-1.2.13.pom
|   |                           
|   +---commons-codec
|   |   \---commons-codec
|   |       \---1.10
|   |               commons-codec-1.10.jar
|   |               commons-codec-1.10.pom
|   |               NOTICE
|   |               
|   +---commons-io
|   |   \---commons-io
|   |       \---2.4
|   |               commons-io-2.4.jar
|   |               commons-io-2.4.pom
|   |               NOTICE
|   |               
|   +---commons-logging
|   |   \---commons-logging
|   |       \---1.2
|   |               commons-logging-1.2.jar
|   |               commons-logging-1.2.pom
|   |               NOTICE
|   |               
|   +---it
|   |   \---unimi
|   |       \---dsi
|   |           \---fastutil
|   |               \---7.2.0
|   |                       fastutil-7.2.0.jar
|   |                       fastutil-7.2.0.pom
|   |                       NOTICE
|   |                       
|   +---javax
|   |   +---inject
|   |   |   \---javax.inject
|   |   |       \---1
|   |   |               javax.inject-1.jar
|   |   |               javax.inject-1.pom
|   |   |               NOTICE
|   |   |               
|   |   \---xml
|   |       \---bind
|   |           \---jaxb-api
|   |               \---2.2.12-b140109.1041
|   |                       jaxb-api-2.2.12-b140109.1041.jar
|   |                       jaxb-api-2.2.12-b140109.1041.pom
|   |                       NOTICE
|   |                       
|   +---net
|   |   +---java
|   |   |   \---jvnet-parent
|   |   |       +---1
|   |   |       |       jvnet-parent-1.pom
|   |   |       |       
|   |   |       +---3
|   |   |       |       jvnet-parent-3.pom
|   |   |       |       
|   |   |       \---4
|   |   |               jvnet-parent-4.pom
|   |   |               
|   |   \---sf
|   |       +---jopt-simple
|   |       |   \---jopt-simple
|   |       |       \---4.9
|   |       |               jopt-simple-4.9.jar
|   |       |               jopt-simple-4.9.pom
|   |       |               NOTICE
|   |       |               
|   |       +---kxml
|   |       |   \---kxml2
|   |       |       \---2.3.0
|   |       |               kxml2-2.3.0.jar
|   |       |               kxml2-2.3.0.pom
|   |       |               NOTICE
|   |       |               
|   |       \---proguard
|   |           +---proguard-base
|   |           |   \---6.0.3
|   |           |           NOTICE
|   |           |           proguard-base-6.0.3.jar
|   |           |           proguard-base-6.0.3.pom
|   |           |           
|   |           +---proguard-gradle
|   |           |   \---6.0.3
|   |           |           NOTICE
|   |           |           proguard-gradle-6.0.3.jar
|   |           |           proguard-gradle-6.0.3.pom
|   |           |           
|   |           \---proguard-parent
|   |               \---6.0.3
|   |                       proguard-parent-6.0.3.pom
|   |                       
|   \---org
|       +---antlr
|       |   +---antlr4
|       |   |   \---4.5.3
|       |   |           antlr4-4.5.3.jar
|       |   |           antlr4-4.5.3.pom
|       |   |           NOTICE
|       |   |           
|       |   \---antlr4-master
|       |       \---4.5.3
|       |               antlr4-master-4.5.3.pom
|       |               
|       +---apache
|       |   +---apache
|       |   |   +---13
|       |   |   |       apache-13.pom
|       |   |   |       
|       |   |   +---15
|       |   |   |       apache-15.pom
|       |   |   |       
|       |   |   +---16
|       |   |   |       apache-16.pom
|       |   |   |       
|       |   |   +---18
|       |   |   |       apache-18.pom
|       |   |   |       
|       |   |   \---9
|       |   |           apache-9.pom
|       |   |           
|       |   +---commons
|       |   |   +---commons-compress
|       |   |   |   \---1.12
|       |   |   |           commons-compress-1.12.jar
|       |   |   |           commons-compress-1.12.pom
|       |   |   |           NOTICE
|       |   |   |           
|       |   |   \---commons-parent
|       |   |       +---25
|       |   |       |       commons-parent-25.pom
|       |   |       |       
|       |   |       +---34
|       |   |       |       commons-parent-34.pom
|       |   |       |       
|       |   |       +---35
|       |   |       |       commons-parent-35.pom
|       |   |       |       
|       |   |       \---39
|       |   |               commons-parent-39.pom
|       |   |               
|       |   \---httpcomponents
|       |       +---httpclient
|       |       |   \---4.5.6
|       |       |           httpclient-4.5.6.jar
|       |       |           httpclient-4.5.6.pom
|       |       |           NOTICE
|       |       |           
|       |       +---httpcomponents-client
|       |       |   \---4.5.6
|       |       |           httpcomponents-client-4.5.6.pom
|       |       |           
|       |       +---httpcomponents-core
|       |       |   \---4.4.10
|       |       |           httpcomponents-core-4.4.10.pom
|       |       |           
|       |       +---httpcomponents-parent
|       |       |   \---10
|       |       |           httpcomponents-parent-10.pom
|       |       |           
|       |       +---httpcore
|       |       |   \---4.4.10
|       |       |           httpcore-4.4.10.jar
|       |       |           httpcore-4.4.10.pom
|       |       |           NOTICE
|       |       |           
|       |       \---httpmime
|       |           \---4.5.6
|       |                   httpmime-4.5.6.jar
|       |                   httpmime-4.5.6.pom
|       |                   NOTICE
|       |                   
|       +---bouncycastle
|       |   +---bcpkix-jdk15on
|       |   |   \---1.56
|       |   |           bcpkix-jdk15on-1.56.jar
|       |   |           bcpkix-jdk15on-1.56.pom
|       |   |           NOTICE
|       |   |           
|       |   \---bcprov-jdk15on
|       |       \---1.56
|       |               bcprov-jdk15on-1.56.jar
|       |               bcprov-jdk15on-1.56.pom
|       |               NOTICE
|       |               
|       +---checkerframework
|       |   \---checker-qual
|       |       \---2.5.2
|       |               checker-qual-2.5.2.jar
|       |               checker-qual-2.5.2.pom
|       |               NOTICE
|       |               
|       +---codehaus
|       |   +---groovy
|       |   |   \---groovy-all
|       |   |       \---2.4.15
|       |   |               groovy-all-2.4.15.jar
|       |   |               groovy-all-2.4.15.pom
|       |   |               NOTICE
|       |   |               
|       |   \---mojo
|       |       +---animal-sniffer-annotations
|       |       |   \---1.17
|       |       |           animal-sniffer-annotations-1.17.jar
|       |       |           animal-sniffer-annotations-1.17.pom
|       |       |           NOTICE
|       |       |           
|       |       +---animal-sniffer-parent
|       |       |   \---1.17
|       |       |           animal-sniffer-parent-1.17.pom
|       |       |           
|       |       \---mojo-parent
|       |           \---40
|       |                   mojo-parent-40.pom
|       |                   
|       +---glassfish
|       |   \---jaxb
|       |       +---jaxb-bom
|       |       |   \---2.2.11
|       |       |           jaxb-bom-2.2.11.pom
|       |       |           
|       |       +---jaxb-core
|       |       |   \---2.2.11
|       |       |           jaxb-core-2.2.11.jar
|       |       |           jaxb-core-2.2.11.pom
|       |       |           NOTICE
|       |       |           
|       |       +---jaxb-runtime
|       |       |   \---2.2.11
|       |       |           jaxb-runtime-2.2.11.jar
|       |       |           jaxb-runtime-2.2.11.pom
|       |       |           NOTICE
|       |       |           
|       |       \---txw2
|       |           \---2.2.11
|       |                   NOTICE
|       |                   txw2-2.2.11.jar
|       |                   txw2-2.2.11.pom
|       |                   
|       +---jdom
|       |   \---jdom2
|       |       \---2.0.6
|       |               jdom2-2.0.6.jar
|       |               jdom2-2.0.6.pom
|       |               NOTICE
|       |               
|       +---jetbrains
|       |   +---annotations
|       |   |   \---13.0
|       |   |           annotations-13.0.jar
|       |   |           annotations-13.0.pom
|       |   |           NOTICE
|       |   |           
|       |   +---kotlin
|       |   |   +---kotlin-reflect
|       |   |   |   \---1.3.31
|       |   |   |           kotlin-reflect-1.3.31.jar
|       |   |   |           kotlin-reflect-1.3.31.pom
|       |   |   |           NOTICE
|       |   |   |           
|       |   |   +---kotlin-stdlib
|       |   |   |   \---1.3.31
|       |   |   |           kotlin-stdlib-1.3.31.jar
|       |   |   |           kotlin-stdlib-1.3.31.pom
|       |   |   |           NOTICE
|       |   |   |           
|       |   |   +---kotlin-stdlib-common
|       |   |   |   \---1.3.31
|       |   |   |           kotlin-stdlib-common-1.3.31.jar
|       |   |   |           kotlin-stdlib-common-1.3.31.pom
|       |   |   |           NOTICE
|       |   |   |           
|       |   |   +---kotlin-stdlib-jdk7
|       |   |   |   \---1.3.31
|       |   |   |           kotlin-stdlib-jdk7-1.3.31.jar
|       |   |   |           kotlin-stdlib-jdk7-1.3.31.pom
|       |   |   |           NOTICE
|       |   |   |           
|       |   |   \---kotlin-stdlib-jdk8
|       |   |       \---1.3.31
|       |   |               kotlin-stdlib-jdk8-1.3.31.jar
|       |   |               kotlin-stdlib-jdk8-1.3.31.pom
|       |   |               NOTICE
|       |   |               
|       |   \---trove4j
|       |       \---trove4j
|       |           \---20160824
|       |                   NOTICE
|       |                   trove4j-20160824.jar
|       |                   trove4j-20160824.pom
|       |                   
|       +---jvnet
|       |   \---staxex
|       |       \---stax-ex
|       |           \---1.7.7
|       |                   NOTICE
|       |                   stax-ex-1.7.7.jar
|       |                   stax-ex-1.7.7.pom
|       |                   
|       +---ow2
|       |   +---asm
|       |   |   +---asm
|       |   |   |   \---6.0
|       |   |   |           asm-6.0.jar
|       |   |   |           asm-6.0.pom
|       |   |   |           NOTICE
|       |   |   |           
|       |   |   +---asm-analysis
|       |   |   |   \---6.0
|       |   |   |           asm-analysis-6.0.jar
|       |   |   |           asm-analysis-6.0.pom
|       |   |   |           NOTICE
|       |   |   |           
|       |   |   +---asm-commons
|       |   |   |   \---6.0
|       |   |   |           asm-commons-6.0.jar
|       |   |   |           asm-commons-6.0.pom
|       |   |   |           NOTICE
|       |   |   |           
|       |   |   +---asm-parent
|       |   |   |   \---6.0
|       |   |   |           asm-parent-6.0.pom
|       |   |   |           
|       |   |   +---asm-tree
|       |   |   |   \---6.0
|       |   |   |           asm-tree-6.0.jar
|       |   |   |           asm-tree-6.0.pom
|       |   |   |           NOTICE
|       |   |   |           
|       |   |   \---asm-util
|       |   |       \---6.0
|       |   |               asm-util-6.0.jar
|       |   |               asm-util-6.0.pom
|       |   |               NOTICE
|       |   |               
|       |   \---ow2
|       |       \---1.3
|       |               ow2-1.3.pom
|       |               
|       \---sonatype
|           \---oss
|               \---oss-parent
|                   +---7
|                   |       oss-parent-7.pom
|                   |       
|                   \---9
|                           oss-parent-9.pom
|                           
\---studio
    \---installer
            firstrun.data
```
