# tren.my Data

![CC BY-SA badge](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)

# FAQ

## Why this project?

At the time of writing this:
- There are neither public API nor open data officially from both Prasarana and KTM Berhad.
- There is an immense lack of accessibility information and station maps online, to the point that you need to be in the station physically, and even that is not a guarantee. This also includes popular destinations near these stations.ations.

As such, this project is developed with the following intentions:
- It prioritizes any information that a commuter may need during their commute. While it's possible to add extra information such as a name sponsor of a station (e.g. KL Sentral-**redONE**), those will not be the focus.
- The license is picked with the intent to allow any interested developers, commercial or not, to use the data and content for as long as they properly credit the contributors of this project *and* contribute back to the project, either directly, or by releasing their own modified datasets with their contributions and a compatible license. By pure coincidence, Wikipedia has the exact same license, meaning certain unofficial data e.g. Chinese translations of station names and unofficial station codes are readily available to us with an existing standard.
- Thus, this project aims to eventually be *a* crowdsourced central open data hub specifically for public transport in Malaysia, starting with the Klang Valley rail services, as well as getting both Prasarana and KTM Berhad to open up their APIs and data for public use.

## Why use YAML (and CSV) over other formats?

While the choice for CSV format is obvious for timetables, time taken between stations, as well as other related data that can only be cleanly represented in a tabular format, the choice of YAML over JSON or XML requires a bit more explaining.

One of the objectives is not just to provide data for developers to use, but to allow anyone to be able to read the data directly at a glance. The only way to meet both of these requirements is to use a readable format, i.e. YAML.

For anyone considering contributing, a style guide (alongside a contributing guide) will be written up in the future.