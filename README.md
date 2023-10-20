# OpenTimelineIO ALE Adapter
![Supported Versions](https://img.shields.io/badge/OpenTimelineIO->=0.17.0-blue)
[![Build Status](https://github.com/OpenTimelineIO/otio-ale-adapter/actions/workflows/ci.yaml/badge.svg)](https://github.com/OpenTimelineIO/otio-ale-adapter/actions/workflows/ci.yaml)

The `ale` adapter is part of OpenTimelineIO's contrib adapter plugins.


# Adapter Feature Matrix

The following features of OTIO are supported by the `ale` adapter:

|Feature                  | Support |
|-------------------------|:-------:|
|Single Track of Clips    | ✔       |
|Multiple Video Tracks    | ✔       |
|Audio Tracks & Clips     | ✔       |
|Gap/Filler               | ✖       |
|Markers                  | ✖       |
|Nesting                  | ✔       |
|Transitions              | ✖       |
|Audio/Video Effects      | ✖       |
|Linear Speed Effects     | ✖       |
|Fancy Speed Effects      | ✖       |
|Color Decision List      | N/A     |
|Image Sequence Reference | ✖       |

# Adapter specific arguments
The ALE adapter adds a couple of optional arguments to the `read_from_string()` function
>read_from_string(input_str, **fps=24**, **ale_name_column_key='Name'**)  

The ALE adapter adds a couple of optional arguments to the `write_to_string()` function
>write_to_string(input_otio, **columns=None**, **fps=None**, **video_format=None**)

# License

OpenTimelineIO and the "ale" adapter are open source software.
Please see the [LICENSE](LICENSE) for details.

Nothing in the license file or this project grants any right to use Pixar or
any other contributor’s trade names, trademarks, service marks, or product names.

# Contributions

If you want to contribute to the project,
please see: https://opentimelineio.readthedocs.io/en/latest/tutorials/contributing.html

# Contact

For more information, please visit http://opentimeline.io/
or https://github.com/AcademySoftwareFoundation/OpenTimelineIO
or join our discussion forum: https://lists.aswf.io/g/otio-discussion
