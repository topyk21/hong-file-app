This project contains helper tools for File and FTP.

The features are shown below.

- File logger(developing...)
- File router through file logger (Not yet)
- Ftp executor(Not yet)
- File upload / download endpoint(Not yet)

---

**Simple example**
When the file arrives at the specified path,

1. The file logger will log the file state.
2. The file router looks this status of the file and records the file that needs to be sent to the ftp executor.
3. The FTP executor performs Ftp transfer.