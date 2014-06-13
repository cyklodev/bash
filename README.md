Bash scripts
====

Simple reversible encryption
----

./2enc loop string

Process :
- string to hexadecimal
- hexadecimal to base64
- remove trailing ==
- result to gzip to base64
- remove trailing ==


`./2enc 2 www.cyklodev.com`

Then decrypt 

`./2dec 2 'H4sIAFC+mlMAA02PSwrDMAxEr9QmzgWKVgUtbHDB3roC59N1056+o0iFLAbL1puRJRSDEF+E2lcoTtAODRDu91mortAilFbvQfwGDw+jzuAy6kcH8xIqyMuj1Q05dbO8g0OvTZZdlQXHH6Fnt4wMLnVjta9vBXxaLE9nHyc8xRmdqzkRbLza/Dob04LtpPtleMvuveD/BJ829/tuZbA3nc2j+eJJt/6vf7vaQxQ8AQAA'`
 


