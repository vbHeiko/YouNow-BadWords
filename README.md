Crowdsourced list of words censored on YouNow
---------------------------------------------

* See [BadWords.txt](BadWords.txt) for an (incomplete) list of words censored
  on YouNow.
* See [SurprisinglyNotBadWords.txt](SurprisinglyNotBadWords.txt) for an (also
  incomplete) list of words that, surprisingly, are actually *not* censored,
  but maybe should have been.

On a Linux command line, you can use this list in conjunction with `grep` to
quickly figure out what part of your sentence will be censored by doing

```
 	echo 'Your sentence.' | grep -iFf BadWords.txt
```

Currently, we're not actually sure whether longer words are also censored if
they only contain any (and yes, *any*) part of a shorter word on the known
blacklist. Here is some evidence to support both cases:

### Longer words banned as part of shorter words
* kunstwerk (twerk)
* musik (sik)

### Allowed longer words which contain a part on the blacklist
* lesbitch (bitch)
* schmiernippel (nippel)
* warscheinlich (arsch)

Contributions are always welcome in order to make both lists a bit less
incomplete!

### Contributors
* Moneypenny
* [PeterHans_59149](https://www.younow.com/PeterHans_59149)
* Perzon5
* Spiegelverkehrt
* Versagerbernd
* Versagermaxi
