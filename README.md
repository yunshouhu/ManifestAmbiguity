ManifestAmbiguity
=================

Parser and Modify AndroidManifest.xml to prevent APK from re-packege

1 make, then get an executable file manifestAmbiguity.


2 ./manifestAmbiguity, then you will get complete information of this project.


3 	----------------------------------------
	|==== Android Manifest Ambiguity ====  |
	----------------------------------------
manifestAmbiguity [options] file
-p, --parser=target_file            parser axml and print it
-m, --modify=target_file            modify axml. Up to now, we just provide a single function that inserting an useless attrbution in axml
-o, --out=output_file               the file to store modified axml. If not defined , the default outfile is out.xml
-h, --help                          show help
-v, --version                       show version
+++++++++++++++++++++++++
+ Learning And Sharing  +
+ Version: 1            +
+ From Wanchouchou ^-^! +
+++++++++++++++++++++++++
Parser an AXML:
      ./manifestAmbiguity -p filename;
      Or ./manifestAmbiguity --parser=filename
Modify an AXML:
      ./manifestAmbiguity -m target_filename -o output_filename;
      Or ./manifestAmbiguity --modify=target_filename --out=output_filename
