# Log file syntax highlighting in Atom

Adds syntax highlighting color for common log formats in Atom.

### Use Case

I often get random logs sent to me for analyzing system behavior. These include crash reports, stack traces, system logs and ad-hoc loggings from different IDEs using dissimilar logging formats. Every time I look for the same keywords (error, exception, exit), check previous line's logging level (info, warning, error) and compare time stamps.

This Atom grammar helps you quickly extract the log information that is important.

### Supported formats

 * [x] Android LogCat
 * [x] Nabto Log
 * [x] iOS Log / Stack trace
 * [x] Firefox crash log (use json raw dump)
 * [x] IDEA log
 * [x] Apache
 * [x] Syslog
 * [x] Common crash logs
 * [x] Common system logs from e.g. ~/Library/Logs/

There are a whole bunch of standard and non-standard log formats out there. This is an attempt to reach the most common I run in to on a daily basis.

> Contributions, bug reports and feature requests are very welcome.

> &nbsp; &nbsp; _- Martin_
