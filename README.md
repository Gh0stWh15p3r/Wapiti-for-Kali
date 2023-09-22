Wapiti allows you to audit the security of your web applications. It performs “black-box” scans, i.e. it does not study the source code of the application but will scan the web pages of the deployed web applications, looking for scripts and forms where it can inject data. Once it gets this list, Wapiti acts like a fuzzer, injecting payloads to see if a script is vulnerable.

Wapiti can detect the following vulnerabilities:

Database Injection (PHP/ASP/JSP SQL Injections and XPath Injections)
Cross Site Scripting (XSS) reflected and permanent
File disclosure detection (local and remote include, require, fopen, readfile…)
Command Execution detection (eval(), system(), passtru()…)
XXE (Xml eXternal Entity) injection
CRLF Injection
Search for potentially dangerous files on the server (thank to the Nikto db)
Bypass of weak htaccess configurations
Search for copies (backup) of scripts on the server
Shellshock
DirBuster like
Server Side Request Forgery (through use of an external Wapiti website)
Installed size: 1.54 MB
How to install: sudo apt install wapiti# Wapiti-for-Kali
