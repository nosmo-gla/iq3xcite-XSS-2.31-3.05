# iq3xcite-XSS-2.31-3.05 - [CVE-2024-46453](https://www.cve.org/CVERecord?id=CVE-2024-46453)

XSS Vulnerability discovered in Trend iq3xcite v2.31-3.05. Fixed in 3.11.

When accessing an arbitrary directory e.g. `/test/`, this will trigger the 404 error page to be returned.
Any data put after the directory is not sanitized by the application and is returned verbose, allowing for injection of JavaScript.

e.g. `/test/<script>alert(1)</script>`


## Version 2.31
![2 31 page](https://github.com/user-attachments/assets/bdf4547e-fe26-40b2-8438-ea98b701fdd1)
![2 31 exploit](https://github.com/user-attachments/assets/747c47c9-6206-49f8-a05b-556d757cdc58)


## Version 3.05
![3 05 page](https://github.com/user-attachments/assets/2583e026-31f6-4d86-9ee3-ffeacff72b96)
![3 05 exploit](https://github.com/user-attachments/assets/c046203c-00ee-49d3-8b94-b56178ff967b)
