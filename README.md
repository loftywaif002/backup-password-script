# Coursera: Backup shell script project, a course by IBM
Coursera final project for Hands-on Introduction to Linux Commands and Shell Scripting


## Scenario
You are a lead linux developer at the top-tech company “ABC International INC.” ABC currently suffers from a huge bottleneck - each day, interns must painstakingly access encrypted password files on core servers, and backup those that were updated within the last 24-hours. This introduces human error, lowers security, and takes an unreasonable amount of work.</br>

As ABC INC’s most trusted linux developer, you have been tasked with creating a script backup.sh which automatically backs up any of these files that have been updated within the past 24 hours. </br>

## Cron

Type 'crontab -e' in terminal</br>
add this line to it</br>
0 0 * * * /usr/local/bin/backup.sh <your-dir>/important-documents <your-dir></br>
</br>
See the cron listed with 'crontab -l'</br>