# OpenTimelineIO ALE Adapter
[![Build Status](https://github.com/OpenTimelineIO/otio-ale-adapter/actions/workflows/ci.yaml/badge.svg)](https://github.com/OpenTimelineIO/otio-ale-adapter/actions/workflows/ci.yaml)
![Dynamic YAML Badge](https://img.shields.io/badge/dynamic/yaml?url=https%3A%2F%2Fraw.githubusercontent.com%2FOpenTimelineIO%2Fotio-ale-adapter%2Fmain%2F.github%2Fworkflows%2Fci.yaml&query=%24.jobs%5B%22test-plugin%22%5D.strategy.matrix%5B%22python-version%22%5D&label=Python)
![Dynamic YAML Badge](https://img.shields.io/badge/dynamic/yaml?url=https%3A%2F%2Fraw.githubusercontent.com%2FOpenTimelineIO%2Fotio-ale-adapter%2Fmain%2F.github%2Fworkflows%2Fci.yaml&query=%24.jobs%5B%22test-plugin%22%5D.strategy.matrix%5B%22otio-version%22%5D&label=OpenTimelineIO)




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
