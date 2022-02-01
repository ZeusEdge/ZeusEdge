# PERMISSIONS ON A FILE
Permissions can be applied on User, Groups or Others

Permissions can be of Read, Write, Execute or No Permission types

## Numerical representation of the different permissions
Read: 4 | Write: 2 | Execute: 1 | No Permission: 0

## Combination of Different permissions
User: 4+2+1 = 7; Groups: 4+1 = 5; Others: 0

## Encryption of Files
Creating the archive - $ tar -cvf <archive_folder.tar> <file_names>

Zipping the archive - $ bzip2 <archived_folder.tar>

Encrypting the archive - $ sudo apt-get install mcrypt

mcrypt -z <zipped_archived_folder>

Enter password & Verify password

Decrypting - $ mcrypt -d <zipped_archived_folder.tar.bz2.gz.nc>
