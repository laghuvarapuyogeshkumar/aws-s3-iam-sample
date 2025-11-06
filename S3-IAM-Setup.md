\# AWS S3 \& IAM Setup Documentation



\## 1. S3 Bucket Setup

\- Bucket Name: `secure-file-storage-yogesh`

\- Versioning: Enabled

\- Upload multiple file types (.txt, .csv, .jpg, .pdf)



\## 2. IAM Setup

\- Users: `data-engineer`

\- Group: `S3FileAdmins` (AmazonS3FullAccess)

\- Role: `S3ReadOnlyRole` (AmazonS3ReadOnlyAccess)

\- Roles can be assumed by services like Lambda or EC2



\## 3. Notes

\- Versioning helps track file changes.

\- IAM roles provide temporary secure access.



