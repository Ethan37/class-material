# Minilab 4

* Use `ssh` to access `eos01.cis.gvsu.edu`
* Run `last` and pipe the results into grep searching for your userid
* Count the number of times I've logged in recently using `last`, `grep`, and `wc`
  Try to do it in one command where all that is output is the count.  My
  userid is `carrieer`
* Repeat the same command with the user id `oboylela` (the id of the sysadmin)
* Use piping, `last`, `grep`, and `wc` to count the number of logins on Wednesday
* Look at the manpages to find an option that allows you to limit grep
  so it only prints the first specified number of matches.  Use piping,
  `last`, and `grep` to print up to the last 5 logins on a Thursday.
* We could have gotten the same output by not using the option to `grep`
  and instead piping the results of `grep` into a 3rd command (one
  we learned earlier this semester).  Think about what command
  we could combine it with to duplicate the results.
