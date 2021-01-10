## pwned
**pwned** is a simple script that checks if a password is exposed in a
known data breach by querying the
[Have I Been Pwned](https://haveibeenpwned.com) database.

Uses the HIBP [API v3](https://haveibeenpwned.com/API/v3#PwnedPasswords)
and has had [padding](https://haveibeenpwned.com/API/v3#PwnedPasswordsPadding)
enabled to obfuscate the returned response size.

### Dependencies
Requires [curl](https://curl.se).

### Usage
**pwned** has no options.

	$ ./pwned
	Password: 
	Oh no - pwned!
	This password has been seen 24077 times before
