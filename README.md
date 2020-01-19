# Create Pandas Layer For AWS Lambda

## How to get started

- Install Python libraries on a Docker image

`./get_layer_packages.sh`

- Zip the package folder

`zip -r my-Python37-Pandas23.zip .`

- Create a bucket in [AWS S3](https://s3.console.aws.amazon.com/s3/buckets)

- Upload the zip to AWS S3

`aws s3 cp my-Python37-Pandas23.zip s3://BUCKET_NAME/`

- Create a layer from AWS Lambda

## Reference

- [Creating New AWS Lambda Layer For Python Pandas Library](https://medium.com/@qtangs/creating-new-aws-lambda-layer-for-python-pandas-library-348b126e9f3e)

- [lambci/docker-lambda](https://github.com/lambci/docker-lambda)
