# aws_fundamentals

**IAM Policies**

{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "VisualEditor0",
            "Effect": "Allow",
            "Action": [
                "iam:CreateGroup",
                "iam:ListAccountAliases",
                "iam:GetUser",
                "iam:GetAccountSummary"
            ],
            "Resource": "*"
        }
    ]
}
