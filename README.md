# Aws

Aws
IAM (Identity and access Management):

IAM ensures the right people have the right access to the right resources at the right time.

OR

Identity and access Management is a web service that helps you securly access to aws resources.You use Iam to control who is authenticated (sign-in) and authorized (has permisiion) to use resources.

Limitation of IAM :

IAM user limits is 5000 per aws account.you can add 10 user at one time.
your are also limited to 1000 IAM roles under AWS account. 3)default limits of managed polices attaced to an IAM role and IAM user is 10. 4)IAM user can be member of 10 group(max). 5)we can assign two access key to an IAM user
Benefits of IAM :

1)shared access to you aws account.
2)Granular permissions. :you can grant diffrent permission to diffrent people for diffrent resources.
3)Secure access to Aws resources of application that run on amazon ec2. 
4)Multifactor Authrntication (MFA).
5)Identity fedration. :you can allow user who have alrady password elsewhere :facebook google then you can login



IAM Term: 1)Principle 2)Request 3)Authentication 4)Authorized 5)Action/Operation 6)Resources You can create a new IAM Policy in the Aws management console 3 ways.
1)json :you can create your own json syntax 
2)/visual editor : you can constract a new policy from scratch in the visual editor . 
3)Import: you can import a managed policy within your aws account.
