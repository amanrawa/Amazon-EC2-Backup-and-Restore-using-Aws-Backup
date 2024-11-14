# Amazon-EC2-Backup-and-Restore-using-Aws-Backup

AWS Backup is a fully managed backup service that simplifies the management and automation of backups for various AWS services. It provides a centralized platform to configure, monitor, and manage backups across different AWS accounts and regions.   

Key Features and Benefits:

Centralized Management: Allows you to manage backups for multiple AWS resources from a single console.   
Automated Backups: Automatically schedules and executes backups based on defined policies.   
Policy-Based Backups: Create and enforce backup policies to meet compliance and data retention requirements.   
Cross-Account and Cross-Region Backups: Back up resources across different AWS accounts and regions.   
Immutable Backups: Provides protection against ransomware and accidental deletion by creating immutable backups.   
Cost-Effective: Offers flexible pricing based on the amount of data backed up and the duration of storage.   
Integration with Other AWS Services: Leverages AWS services like CloudWatch, CloudTrail, and IAM for monitoring, auditing, and security.   

! What We will accomplish

1 - Create an on- demand backup job of an Amazon EC2 instance

2- Use a backup plan to backup Amazon EC2 resources—using a backup plan within AWS Backup lets you automate your backups on a schedule   

3 -Add resources to an existing backup plan using tags


Implementation

Step 1: Go to the AWS Backup console
    a . Log in to the AWS Management Console and open the AWS Backup console


Step 2 : Configure an on-demand AWS Backup job of an Amazon EC2 instance

    2.1 -  Configure the service used with AWS Backup
    a: In the navigation pane on the left side of the AWS BAckup console, under My Account 
        choose setting


    b: On the Service-Opt-in page,  choose Configure resources
