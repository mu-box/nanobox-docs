In Windows, Nanobox uses the Common Internet File System (CIFS) to mount your codebase into your Nanobox VM when `netfs` is specified as the `mount-type` in your [config.yml](/local-dev/nanobox-config-yml/). CIFS doesn't use an exports file, so you shouldn't run across this problem.