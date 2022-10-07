### SPF String Support

This work is supported by GSoC 2022.

In addition to functions that are already supported, isEmpty(), valueOf(int) and valueOf(char) are newly added as fully supported functions.
ValueOf(long) may also be supported already, since there is no fundamental difference between it and valueOf(int).

startsWith() and endsWith were implemented incorrectly in Marlin's work and I have fixed them.

Integer AND, ParseInt() and trim() are partially supported/still in progress.

Read [this document](https://github.com/yanxx297/jpf-symbc/blob/mjr/dev_init_igen/doc/Z3str3-string-support.md) for more details.
