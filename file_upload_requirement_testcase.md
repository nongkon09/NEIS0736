# File upload requirement test case
**Pre-condition**
* Specific file type in JPEG or png format 
* Identify user 
* Limit file size per user (Maximum: 5MB per image)
* Limit 10 files per user
* Disk quota 100M per user
* System capacity

**Inputs**
* Files 100MB size upload
* Files 5MB size upload
* Zip bombs upload 
* 20 files upload
* 10 files upload
* 100 users upload at the same time

**Outputs**
* Upload Success
* Upload Failed 
* Error 

**Post-condition**
