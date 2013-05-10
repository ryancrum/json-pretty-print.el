# json-pretty-print.el

#### NOTE: These changes have been merged into emacs trunk as part of json.el. If you have a recent build of Emacs, you might already possess (an improved version of) this code. If not, grab the [trunk version of json.el](http://git.savannah.gnu.org/cgit/emacs.git/plain/lisp/json.el?h=trunk) and use it instead. ####

This is a library for Emacs that assists in converting machine-generated JSON into human-readable JSON.

This library relies on a modified version of json.el that can be found here: [http://github.com/thorstadt/json.el](http://github.com/thorstadt/json.el).

## Functions

* `json-pretty-print`: Pretty-print formats the currently selection region.
* `json-pretty-print-buffer`: Replaces the entire buffer with a pretty-printed version.

