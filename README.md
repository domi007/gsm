gsm
===

Stuff that I created while doing my GSM-security research


Currently contains:
- MD5 hashes of the a51_table files (distributed via torrent) in a format which could be interpreted by md5sums  
  Use it like this:  
```md5sum -c a51_table_md5_hashes```  
Note: it takes quite some time to run MD5 on such large files, so be prepared that it is possible it takes 12-15 hours

- List of the exact sizes of all tables so you can check if you have the right files via  
```ls -l```

- SilentSMS as a submodule - an Android app that can send silent text messages
