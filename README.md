# rotate scripts provides mechanism to move a file from certain directory in case it's filled up.
* Destination directory must have enough space to receive a "Moved" file
* Directories must exist
* Moved file will be moved ONLY if it's size is larger then specified in MAX_SIZE variable
* Script must me ready to be moved in cron.hourly
* All incedents and successfull transitions must be reported to the log file
