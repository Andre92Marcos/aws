# Cookbook

## List S3 buckets

	aws --endpoint=http://s3.<hostname> s3 ls

## List S3 buckets contents

	aws --endpoint=http://s3<hostname> s3 ls s3://<bucketname>

## Copy files to a S3 bucket

	aws --endpoint=http://<hostname> s3 cp shell.php s3://<hostname>
