# chrome-password-generator
Chrome Extension to generate relatively complex, yet easy to remember passwords.

A password generator built with security and password-memorability in mind.

Inspired by the xkcd Password Strength comic (https://xkcd.com/936) and is based on the Diceware proposal at http://world.std.com/~reinhold/diceware.html wherein six-sided virtual dice are rolled five times, and the resulting five digit number is then used against a lookup table of words. 

You can adjust the number of words and optionally include numbers or symbols for additional complexity (or to satisfy certain password requirements), make the words lower, mixed, or upper case 

Why should I use passwords like these?
* Using common words in your password aids memorability.
* Using multiple words ensures sufficient complexity to prevent guessing of the password.


For more information on Diceware:
	<a href="http://world.std.com/~reinhold/diceware.html">The Diceware Passphrase FAQ</a><br>
	<a href="http://world.std.com/~reinhold/diceware.wordlist.asc">Original Diceware word list</a> (This implementation uses a different <a href="https://www.eff.org/deeplinks/2016/07/new-wordlists-random-passphrases">wordlist...</a>)<br>
	<a href="http://world.std.com/~reinhold/diceware.txt">Diceware for Passphrase Generation and Other Cryptographic Applications</a><br>
