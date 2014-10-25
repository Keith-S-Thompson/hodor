Hodor is a special-purpose language specifically created to support a
solution of the FizzBuzz problem.  There are probably other programming
languages called Hodor.  This one is mine.

References:

* [http://imranontech.com/2007/01/24/using-fizzbuzz-to-find-developers-who-grok-coding/](Using FizzBuzz to Find Developers who Grok Coding) by Imran Ghory
* [http://www.codinghorror.com/blog/2007/02/why-cant-programmers-program.html](Why Can't Programmers.. Program?) by Jeff Atwood

There are currently 24 valid tokens in the language, each of them a
variant of the word "hodor" with variations in case.

Each token is translated to a particular string, and the result is
fed to a Ruby interpreter.  The set of supported tokens was chosen
specifically to support a single Ruby program that implements FizzBuzz.
Other Hodor programs can also be written, but only if they happen to
use only the 24 supported tokens.  (The language could be extended
to support up to 32 tokens.)

The interpreter is implemented as a Perl script, which also serves
as the language definition.

More references:

- https://github.com/Keith-S-Thompson/fizzbuzz
- https://github.com/Keith-S-Thompson/fizzbuzz-polyglot
- https://github.com/Keith-S-Thompson/fizzbuzz-c

   -- [Keith Thompson](mailto:Keith.S.Thompson@gmail.com) Fri 2014-10-24
