# iohyve-windows
iohyve Windows installer to simplify installing of Windows in a bhyve-guest.

The installer uses iohyve and is mostly based on the examples in [this](http://pr1ntf.xyz/windowsunderbhyve.html) blog post by pr1ntf (creator of iohyve).

## Bootstrap
`iohyve-windows bootstrap [win2k8|win2k12|win2k16|all]`

Bootstrapping the environment

## Installing
`iohyve-windows install <win2k8|win2k12|win2k16> <path/to/iso>`
