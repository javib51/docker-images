FROM dtzar/helm-kubectl:latest

# Add tools for 
RUN \
    curl -o /bin/aws-iam-authenticator https://amazon-eks.s3-us-west-2.amazonaws.com/1.15.10/2020-02-22/bin/linux/amd64/aws-iam-authenticator && \
    chmod +x /bin/aws-iam-authenticator

# # Command to run the executable
# ENTRYPOINT ["/bin/sh"]