    #     ___  ____     _    ____ _     _____
    #    / _ \|  _ \   / \  / ___| |   | ____|
    #   | | | | |_) | / _ \| |   | |   |  _|
    #   | |_| |  _ < / ___ | |___| |___| |___
    #    \___/|_| \_/_/   \_\____|_____|_____|
***

# Autonomous Transaction Processing Backup Example
[Managing Autonomous Transaction Processing Backups and Restores](https://docs.cloud.oracle.com/iaas/Content/Database/Tasks/atpbackingup.htm)

## Managing Backups
You do not have to do any manual backups for your database as Autonomous Transaction Processing backs up your database automatically. The retention period for backups is 60 days.

You can also do manual backups using the Oracle Cloud Infrastructure Terraform Provider if you want to take backups before any major changes. Manual backups are stored in Object Storage.

## Creating a Bucket to Store Manual Backups
You must create and configure an Oracle Cloud Infrastructure Object Storage bucket to hold your Autonomous Transaction Processing manual backups. This is a one-time operation.
