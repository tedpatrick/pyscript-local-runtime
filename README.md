# pyscript-local-runtime

This downloads PyScript and all runtime dependencies locally.

Download Runtime...
```shell
cd runtime
source setup.sh
```

Combined with a `<py-config>` as follows:
```html
<py-config>
      [[runtimes]]
      src = "runtime/pyodide.js"
      name = "pyodide-0.21.3"
      lang = "python"
</py-config>
```

And PyScript loaded locally like so:
```html
<link rel="stylesheet" href="runtime/pyscript.css" />
<script defer src="runtime/pyscript.js"></script>
```

Everything you need is now local. Perfect for Extensions, Offline, Environments where the Internet is not available.

Regards,

Ted :)