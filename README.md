Bulk email-extractor-based-on-imap

email extractor based on imap bulk email extractor based on your list.txt 

A simple Python script that logs into a user's IMAP email account and removes any duplicates from the inbox. The script takes a list of email addresses and passwords and stores them in a queue. A function is then called to iterate over the queue, log into each email account, and search for duplicates. If duplicates are found, they are marked for deletion and the mailbox is expunged.

pip install -r requirements.txt