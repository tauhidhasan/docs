Connect to a running instance of the current app.

## Usage
~~~
flyctl ssh console [flags]
~~~

## Options

~~~
  -A, --address string   Address of VM to connect to
  -a, --app string       Application name
  -C, --command string   command to run on SSH session
  -c, --config string    Path to application configuration file
  -h, --help             help for console
  -o, --org string       The organization to operate on
  -q, --quiet            Don't print progress indicators for WireGuard
  -r, --region string    Region to create WireGuard connection in
  -s, --select           select available instances
~~~

## Global Options

~~~
  -t, --access-token string   Fly API Access Token
  -j, --json                  json output
      --verbose               verbose output
~~~

## See Also

* [flyctl ssh](/docs/flyctl/ssh/)	 - Use SSH to login to or run commands on VMs

