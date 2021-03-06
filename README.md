# Project Name (C# Console Application)

#### A console-based application to simulate ... where the user can ... hosted on [GitHub](https://github.com/KristaRutz/). _Last Updated 03.03.2020._

#### By _**Krista Rutz, [other contributors]**_

## Description

This application lets the user... and does...
It might even be hosted on hosted on [GitHub](https://github.com/KristaRutz/). It does so using this and this technology or concept.

## Installation / Set-up

Download or clone the repository to run this program locally! _This program requires .NET Core SDK to run. [Here is a free tutorial](https://www.learnhowtoprogram.com/c-and-net/getting-started-with-c/installing-c-and-net) for installing .NET on Mac or Windows 10._

- Download or clone this repo.
  - **To Download ZIP:**
    - Select "Download" on the [GitHub Repository](https://github.com/KristaRutz/) site
    - Once downloaded, open the ZIP and extract files. The new folder will be created as 'ProjectName.Solution'.
  - **To Clone:**
    - Clone from command line into your Desktop: `$ git clone https://github.com/KristaRutz/...`
    - The new directory will be created as 'Desktop/ProjectName.Solution'.
- Once you have stored the files locally, execute the following commands.
  - Navigate to the application directory: `$ cd ProjectName.Solution/ProjectName`
  - `dotnet build`
  - `dotnet run`
- Upon success, the program will begin running in your console.

## Technologies Used

- C#
- .NET Core 2.2

## Specs

<details>
  <summary>Expand specs for this project</summary>

| Spec                                                                                 | Example Input           | Expected Output                      |
| :----------------------------------------------------------------------------------- | :---------------------- | :----------------------------------- |
| Program prints out the inputted string with no numbers                               | "hello"                 | "hello"                              |
| Program replaces "0" with zero                                                       | "I am 0 years old"      | "I am zero years old"                |
| Program replaces "1" with one                                                        | "I am 1 years old"      | "I am 1 years old"                   |
| Program replaces any single digit number with the correct text                       | "I am 6 years old"      | "I am six years old"                 |
| Program can identify a two digit number, but ignores leading zeros                   | "I am 06 years old"     | "I am six years old"                 |
| Program can identify a two digit multiple of ten (20-90), but ignores trailing zeros | "I am 20 years old"     | "I am twenty years old"              |
| Program replaces any two digit number with the correct text                          | "I am 66 years old"     | "I am sixty-six years old"           |
| Program can parse 10-19 correctly                                                    | "I am 13 years old"     | "I am thirteen years old"            |
| Program can identify a three digit multiple of 100 (100-900) as a "hundred"          | "I am 100 years old"    | "I am one hundred years old"         |
| Program replaces any three digit number, and includes "and"                          | "I am 110 years old"    | "I am one hundred and ten years old" |
| Program can identify numbers 1000 and above with a "thousand"                        | "I am 1000 years old"   | "I am one thousand years old"        |
| Program can identify numbers 1000 and above with a "thousand", and parse commas      | "I am 1,000 years old"  | "I am one thousand years old"        |
| Program can identify multiples of 1000 and above with a "thousand"                   | "I am 45,000 years old" | "I am forty-five thousand years old" |

</details>
<details>
  <summary>Expand user stories for this project</summary>

| As a _User-Type_, | I want... | so that... |
| :---------------- | :-------- | :--------- |


</details>

## Known Bugs

- No known bugs

## Support and contact details

Please contact me if you run into any issues or have questions, ideas or concerns. Krista can be contacted at <krista.rutz@pomona.edu>. Feel free to create a pull request for updates - _contributions to the code are encouraged!_

### License

Copyright (c) 2020 **_Krista Rutz, [Others]_**

_This software is licensed under the MIT license._

<details>
  <summary>View license details</summary>

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

</details>
