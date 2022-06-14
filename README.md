# COMMON ATTACKS ON WEB APPLICATIONS

## Background
### Codey's Confectionery: Preventing Cross-Site Request Forgery (CSRF) Attacks

A bakery owner uses a website to let customers make orders on desserts. Recently there have been kids pranking the website and taking advantage of CSRF’s, tricking adults into ordering big batches.

Fix the CSRF vulnerabilities on the Ordering form and the Contact form.

## Project

This project uses the libraries `csurf`  and `cookie-parser` to fix CSRF vulnerabilities by introducing `input[type=hidden]` tags with `csrfToken` values into Ordering form and the Contact form html from the site.