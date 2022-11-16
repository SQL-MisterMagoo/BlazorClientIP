# BlazorClientIP

Demonstrates two ways to get the client IP address

`_Host.cshtml` uses HttpContext to retrieve the request remote address and pass it to the `App`

`Index.razor` displays that IP address and additionally makes a call to the browser to `fetch` the IP address

You would normally not use `eval` but this is just a demo.