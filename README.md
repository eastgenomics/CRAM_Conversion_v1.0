<!-- dx-header -->

# CRAM Conversion (DNAnexus Platform App)

## What does this app do?

Upload an array of VCF files from DNAnexus platform to OpenCGA - Project/Study.

## What are typical use cases for this app?

This app may be executed as a standalone app.

## What data are required for this app to run?

This app requires the following files:
- Config file (eg. Config.txt): This file must have OpenCGA account and project information mainly Username, Password, Project, Study, and Directory. 
Please note that Directory (eg. <STUDY_NAME>) should be exist in OpenCGA, if not create it. To crete directory in OpenCGA, use this command (eg. <PATH>/opencga.sh files create --study <STUDY_NAME> --path <STUDY_NAME>

- Array of VCF files (eg. Sample_1.vcf.tar.gz, Sample_2.vcf.tar.gz...)

## What does this app output?

This app upload an array of VCF files from DNAnexus platform to the OpenCGA and print output text file mentioning the last VCF file name and the project/study name. Uploaded VCF file needs to confirm in OpenCGA platform with tree command seperatly.

### This app was made by EMEE GLH
<!-- /dx-header -->

<!-- Insert a description of your app here -->

<!--
TODO: This app directory was automatically generated by dx-app-wizard;
please edit this Readme.md file to include essential documentation about
your app that would be helpful to users. (Also see the
Readme.developer.md.) Once you're done, you can remove these TODO
comments.

For more info, see https://documentation.dnanexus.com/developer.
-->

