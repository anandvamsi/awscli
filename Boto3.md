
# Credentials:

The order in which boto3 searches for credentials:
- Passing the credentials in the boto.client() method.
- Passing the credentials when creating a Session obhect
- Environment variables
- Shared Credentials (~/.aws/credentials)
- AWS config
- Assume Role provider
- Boto2 config file.
- Instance metadata services
