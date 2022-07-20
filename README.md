# S3-CloudFront
Identity-based policy - applied to users role / IAM Group
AllowGroupToSeeBucket / AllowRootlevelOfCompanyBucket with ARN S3::* Aand S3:Prefix in ./*
edit S3 -> Bucket -> Bucket Policy to include User ARN and Resource ARN / Bucket Location

aws s3 mb s3://bucketname --region us-east-1
AWS S3 CP .PDF S3://bucket
aws s3 ls -la s3://bucket
aws s3 rb s3://bucket --force
cat ~/.aws/config
aws s3 mv source.json s3://tgsbucket
