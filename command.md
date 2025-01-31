# command to list s3 bucket
aws s3 ls
# command to list IAM user
 #  command to copy file to s3 bucket
aws iam list-users
# command to create iam users
aws iam create-user --user-name apple
# command to delete iam user
aws iam delete-user --user-name apple
# command to move file to s3 bucket
 aws s3 mv secret-file2 s3://clement18761234 --recursive
 # command to copy file to s3 bucket
 aws s3 cp efosa-file s3://clement18761234 --recursive
 # command to remove or delete
 aws s3 rm s3://clement18761234/letter1.txt
 # command to remove all the bucket
  aws s3 rm  s3://clement18761234 --recursive
