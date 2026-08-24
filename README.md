# GPS

VB.NET 2005 WinForms sample (`High-Precision GPS Application (VB.NET).sln`, assembly CodeProject Examples for Part 2) whose Form1 (title High-Precision GPS Example) parses NMEA text or COM2 serial at 4800 baud. `ParseButton` and `Serial_DataReceived` run `NmeaInterpreter.Parse` for `$GPRMC`/`$GPGSV`/`$GPGSA`; HDOP versus Maximum Allowed HDOP (default 6, metres as DOP*6) decides whether `PositionReceived` is treated as precise. `NmeaInterpreter` is Jon Person's GPS.NET interpreter (www.gpsdotnet.com). This is third-party CodeProject source, not VaderConsulting-authored; keep original terms and `THIRD_PARTY_NOTICES.md`.

**Source last updated:** 2006-07-03  
**Language:** VB.NET  
**Target:** not recorded  
**Output:** WinExe

## What it is

VB.NET 2005 WinForms sample (`High-Precision GPS Application (VB.NET).sln`, assembly CodeProject Examples for Part 2) whose Form1 (title High-Precision GPS Example) parses NMEA text or COM2 serial at 4800 baud. `ParseButton` and `Serial_DataReceived` run `NmeaInterpreter.Parse` for `$GPRMC`/`$GPGSV`/`$GPGSA`; HDOP versus Maximum Allowed HDOP (default 6, metres as DOP*6) decides whether `PositionReceived` is treated as precise. `NmeaInterpreter` is Jon Person's GPS.NET interpreter (www.gpsdotnet.com). This is third-party CodeProject source, not VaderConsulting-authored; keep original terms and `THIRD_PARTY_NOTICES.md`.

## Solution structure

| Project | Language | Path |
|---------|----------|------|
| `High-Precision GPS Application (VB.NET)` | VB.NET | `High-Precision GPS Application (VB.NET).vbproj` |

## How to open

Open `High-Precision GPS Application (VB.NET).sln` in Visual Studio.

## Attribution and provenance

- No third-party source-code attribution markers were identified in assembly/package metadata.

## License

Original license terms apply where recorded in the tree or package metadata. This repository does not claim authorship. See `THIRD_PARTY_NOTICES.md`.
