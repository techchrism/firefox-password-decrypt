# Firefox Password Decrypt
### A Powershell script designed to load the nss3 dll and decrypt saved Firefox passwords without writing to disk

This collection of scripts finds Firefox profile data, loads encrypted saved passwords (and associated metadata), decrypts the passwords, and returns the data.

It uses Matt Graeber's technique of reflectively defining managed structs and functions corresponding to unmanaged dll functions: https://devblogs.microsoft.com/scripting/use-powershell-to-interact-with-the-windows-api-part-3/