# Example Problem

A website records a log of user accesses.  
Each log entry consists of the **username** (a single word) and the **timestamp** when the user accessed the site, in **ISO 8601** format, separated by a space, as shown below.

Write a program that reads the access log from a file and then reports how many **distinct users** accessed the site.

---

## 📘 Example

### **input file:**
```
amanda 2018-08-26T20:45:08Z
alex86 2018-08-26T21:49:37Z
bobbrown 2018-08-27T03:19:13Z
amanda 2018-08-27T08:11:00Z
jeniffer3 2018-08-27T09:19:24Z
alex86 2018-08-27T22:39:52Z
amanda 2018-08-28T07:42:19Z
```

### **Execution:**
```
Enter file full path: c:\temp\in.txt
Total users: 4
```