# Dirb

DIRB is a Web Content Scanner. It looks for existing (and/or hidden) Web Objects.
It basically works by launching a dictionary based attack against a web server and analyzing the response.

DIRB comes with a set of preconfigured attack wordlists for easy usage but you can use your custom wordlists.
Also DIRB sometimes can be used as a classic CGI scanner, but remember is a content scanner not a vulnerability scanner.

DIRB main purpose is to help in professional web application auditing. Specially in security related testing.
It covers some holes not covered by classic web vulnerability scanners. DIRB looks for specific web objects that other generic CGI scanners can’t look for. 
It doesn’t search vulnerabilities nor does it look for web contents that can be vulnerables.

**Syntax**

> # dirb <url_base> [<wordlist_file(s)>] [options]

* <url_base> : Base URL to scan

* <wordlist_file(s)> : List of wordfiles

**Options**

*  -X <extensions> / -x <exts_file> : Append each word with this extensions 
  
*  -w : Don't stop on WARNING messages

*  -u <username:password> : HTTP Authentication

*  -R : Interactive recursion

