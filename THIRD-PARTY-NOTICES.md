# Third-Party Notices

PC Manager is licensed under the [MIT License](LICENSE). It redistributes the third-party
components listed below, each under its own license. This file is provided to satisfy those
licenses' attribution / notice requirements; the copyright and license of each component remain
with its respective authors.

## Bundled runtime components

| Component | License | Project |
|-----------|---------|---------|
| CommunityToolkit.Mvvm | MIT | https://github.com/CommunityToolkit/dotnet |
| ComputeSharp | MIT | https://github.com/Sergio0694/ComputeSharp |
| Hardcodet.NotifyIcon.Wpf | MIT | https://github.com/hardcodet/wpf-notifyicon |
| ModernWpfUI | MIT | https://github.com/Kinnara/ModernWpf |
| SharpCompress | MIT | https://github.com/adamhathcock/sharpcompress |
| Microsoft.Data.Sqlite | MIT | https://github.com/dotnet/efcore |
| Microsoft.Diagnostics.Tracing.TraceEvent | MIT | https://github.com/microsoft/perfview |
| Microsoft.Extensions.Hosting | MIT | https://github.com/dotnet/runtime |
| System.Management | MIT | https://github.com/dotnet/runtime |
| System.ServiceProcess.ServiceController | MIT | https://github.com/dotnet/runtime |
| Serilog | Apache-2.0 | https://github.com/serilog/serilog |
| Serilog.Sinks.File | Apache-2.0 | https://github.com/serilog/serilog-sinks-file |
| LibreHardwareMonitorLib | MPL-2.0 | https://github.com/LibreHardwareMonitor/LibreHardwareMonitor |
| Microsoft.Web.WebView2 | Microsoft Software License Terms (redistributable) | https://developer.microsoft.com/microsoft-edge/webview2/ |

## Notes

- **MPL-2.0 (LibreHardwareMonitorLib):** the Mozilla Public License 2.0 is a file-level copyleft —
  PC Manager links the library unmodified, so its terms attach only to the library's own source.
  The corresponding source is available at the project link above.
- **Apache-2.0 (Serilog):** redistribution preserves the copyright, license, and any NOTICE text
  per the license terms.
- **Microsoft.Web.WebView2:** distributed under Microsoft's license terms, which permit
  redistribution as part of an application. The WebView2 Runtime is © Microsoft.

Build-time-only dependencies (xUnit, coverlet, the Roslynator / Meziantou / VisualStudio.Threading
analyzers, Microsoft.NET.Test.Sdk) are not redistributed in the shipped app and are not listed here.
