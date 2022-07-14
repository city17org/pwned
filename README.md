PWNED(8) - System Manager's Manual

# NAME

**pwned** - query the Have I Been Pwned password database

# SYNOPSIS

**pwned**

# DESCRIPTION

**pwned**
is a utility that checks if a password has been exposed in a known data
breach by querying the
[https://haveibeenpwned.com](https://haveibeenpwned.com)
database.

When run, the user will be prompted to enter the password to query.
The input will not be echoed to the screen.

# EXIT STATUS

The **pwned** utility exits&#160;0 on success, and&#160;&gt;0 if an error occurs.

# EXAMPLES

	$ ./pwned
	Password:
	Oh no - pwned!
	This password has been seen 24077 times before

# SEE ALSO

[https://haveibeenpwned.com/API/V3#PwnedPasswords](https://haveibeenpwned.com/API/V3#PwnedPasswords)

# AUTHORS

Sean Davies &lt;[sean@city17.org](mailto:sean@city17.org)&gt;

# CAVEATS

Depends on
curl(1).
