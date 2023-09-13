# System Administration and IT Infrastructure Services | Week-5

## Planning for Data Recovery

### Question 1

How can you recover from an unexpected data loss event? Select all that apply.

Recover data from damaged devices ( Correct )

Restore data from backups ( Correct )

Write a post-mortem report

Design a disaster recovery plan

Answer - If a hard drive or device becomes damaged or fails, you can attempt to recover data using specialized software. If data becomes corrupt or gets deleted, you can also restore the data from backup.


### Question 2

What is it best to store backups, physically?

In a safe

On-site

Across multiple locations ( Correct )

Off-site

Answer - Ideally, backups should be stored in multiple physical locations to reduce the risk of a catastrophe causing you to lose your backups. Typically, data would be backed up somewhere locally, and the backups would be replicated and stored off-site.


### Question 3

Which of these should be included in your organization’s backups? Select all that apply.

Sales databases ( Correct )

Family vacation photos

A downloads folder

Firewall configurations ( Correct )

Answer - Critical data for an organization, like firewall configs and relevant databases, should be included in the backup plans.


### Question 4

What's magnetic tape backup media best suited for?

Long-term archival data ( Correct )

Cheap backup systems

Quick and efficient backups

Low-latency cached data

Answer - Magnetic tape media is very cheap, but it's also super slow and inconvenient to retrieve data from. This makes it a good option for archiving old data that won't be needed often.


### Question 5

Why is it important to test backups and restoration procedures? Select all that apply.

To reduce the size of backup data

To prove the system is flawless and the IT team deserves a pay raise.

To ensure backups work and data can be restored from them ( Correct )

To ensure that relevant data is included in the backups ( Correct )

Answer - It's super important to test backups and restore procedures to ensure that they actually work! Backup archives could be corrupt or inconsistent, preventing proper restoration. Restore procedures are just as important to test, to ensure that critical data can be extracted from backups if a disaster strikes. Disaster testing can also reveal any gaps in your backup coverage without risking real-world data loss.


### Question 6

Which of the following backup types are most space-efficient?

Full backups

Incremental backups ( Correct )

Differential backups

Answer - Incremental backups are the most efficient. While they start with a full backup, on subsequent runs, they only backup the parts of files that have changed since the last run.