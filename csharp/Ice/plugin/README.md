This demo illustrates how to write and configure a simple Ice [plug-in][1]
as well as an Ice [Logger plug-in][2].

To run the demo, first start the server:

| .NET Framework 4.5 | .NET Core 2.0        |
| ------------------ | -------------------- |
| `server`           | `dotnet server.dll`  |

In a separate window, start the client:

| .NET Framework 4.5 | .NET Core 2.0       |
| ------------------ | ------------------- |
| `client`           | `dotnet client.dll` |

Both the client and server use a custom logger that is loaded as
a logger plug-in. The server also uses a plug-in to implement the
servant for this demo.

Please review the client and server configuration files to see the
plug-in configuration.

[1]: https://doc.zeroc.com/display/Ice37/Plug-in+Facility
[2]: https://doc.zeroc.com/display/Ice37/Logger+Plug-ins
