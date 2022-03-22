<div align="center">

# Manfred Awesomic CV

The MAC (or Manfred Awesomic CV) is a(nother) naive attempt to create **a standard open source format to define and share CVs**. The format is defined as a JSON Schema to validate CVs stored as JSON files.
 
 <a href='https://github.com/getmanfred/mac/releases'>
  <img src='https://img.shields.io/github/v/release/getmanfred/mac?color=%23FDD835&label=version&style=for-the-badge&logo=JSON'>
</a>
<br />
<br />
 
[Why using it](#-why-using-it) •
[How to use it](#-how-to-use-it) •
[Who uses it](#-who-uses-it) •
[About us](#-about-us) •
[How to contribute](#%EF%B8%8F-how-to-contribute) •
[License](#%EF%B8%8F-license) •
[Spread the word!](#-spread-the-word)  
<br />
<br />
<br />
!["JSON Schema"](https://github.com/getmanfred/mac/blob/master/assets/readme/schema_screen_capture.png?raw=true "JSON Schema")
<br />
 <br />
!["MAC Sample"](https://github.com/getmanfred/mac/blob/master/assets/readme/MAC_sample.gif?raw=true "MAC Sample")
  
</div>  

## 🥘 Why using it

There are A LOT of CV formats, and some of them are a nice try to define a universal CV format, but we think that **a CV should include not only what candidates are or know, but also what they are interested in and what they want to become**.

Like most open-source projects, the first use case was found in the company where the first contributors worked. Manfred is committed to the idea that **every person should keep control over their personal and professional data**. This means that they should be able to export their data from any platform in a machine-readable format with **a Model Definition to process that data efficiently**. This is how the MAC was born.

<div align="center">
  <img src='https://github.com/getmanfred/mac/blob/master/assets/readme/MAC_Structure.png?raw=true' width='600px'>
 </div>


## 🖱️ How to use it

You just need to copy, download or reference [the schema](https://github.com/getmanfred/mac/blob/master/schema/schema.json) to validate a new CV, built as a JSON file from scratch, or a JSON generated previously (for example, [this sample](https://github.com/getmanfred/mac/blob/master/samples/deafult_sample.json)).

To get started, you can copy both schema and sample in an **online validator** like [jsonschemavalidator.net](https://www.jsonschemavalidator.net/) or [liquid-technologies.com/online-json-schema-validator](https://www.liquid-technologies.com/online-json-schema-validator).

!["JSON Schema"](https://github.com/getmanfred/mac/blob/master/assets/readme/MAC_online_validator_example.png?raw=true "JSON Schema")

You also have implementations to validate a JSON file programmatically in almost every coding language:

* [AVJ (JavaScript)](https://ajv.js.org/)
* [Snow (Java)](https://github.com/ssilverman/snowy-json)
* [jschon (Python)](https://jschon.readthedocs.io/en/latest/)
* ... and [many more](https://json-schema.org/implementations.html)

> :warning: **The current MAC Schema has been designed using the 2019-09 Specification Draft**: when choosing a validator, please, check if it's compliant with the 2019-09 Draft. You can get much more information about the JSON Schema Specification in [json-schema.org](https://json-schema.org/).

You can check **examples of how to use code to create and validate MAC files** in the [MAC/scripts](https://github.com/getmanfred/mac/tree/master/scripts) directory.

---

The Schema is documented by itself, but it's much easier to get "the big picture" with [a graphical representation].(https://github.com/getmanfred/mac/blob/master/assets/readme/MAC_diagram.png)
<br />
<br />

## 🎨 Who uses it

A bunch of Tech Startups, IT Consulting Companies and Recruiting Platforms already use the MAC as an interchangeable format **to unlock the data of their users, candidates and employees and give them back the power to use it wherever they want**.

<a href="https://www.getmanfred.com/" target="_blank"><img alt="Manfred" src="https://pbs.twimg.com/profile_images/946845160004112384/ap8_xjIa_400x400.jpg" width="170"/></a> <a href="https://www.sngular.com/" target="_blank"><img alt="SNGULAR" src="https://res.cloudinary.com/crunchbase-production/image/upload/c_lpad,h_170,w_170,f_auto,b_white,q_auto:eco,dpr_1/ympwkuxhx9lusfwrfbbb" width="170"/></a> <a href="https://mobivery.com/" target="_blank"><img alt="MOBIVERY" src="https://pbs.twimg.com/profile_images/1494757617859760135/Cs05qCrQ_400x400.png" width="170"/></a> <a href="https://spartacommodities.com/" target="_blank"><img alt="SPARTA" src="https://pbs.twimg.com/profile_images/1437686297666142211/7MaD2mmP_400x400.png" width="170"/></a>

## 🤓 About us

The MAC was made with ❤️ and sentidiño in Galicia, Spain.

As common in new projects, the individual or group who started the project also administers the project, establishes its vision, and controls permissions to merge code into it. **We have appointed a starting Council to manage the MAC**, formed by 2 people from Manfred and 2 independent members, but the plan is to hold formal elections, where contributors will vote for candidates for the Council as soon as the project gets a minimum maturity and adoption.

Right now the Council is formed by:

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/dbonillaf"><img src="https://avatars.githubusercontent.com/u/293330?v=4?s=100" width="100px;" alt="David Bonilla"/><br /><sub><b>David Bonilla</b></sub></a></td>
    <td align="center"><a href="https://github.com/blanaspa"><img src="https://avatars.githubusercontent.com/u/30079172?v=4?s=100" width="100px;" alt="Blanca Lanaspa"/><br /><sub><b>Blanca Lanaspa</b></sub></a></a></td>
    <td align="center"><a href="https://github.com/molpe"><img src="https://avatars.githubusercontent.com/u/7792?v=4?s=100" width="100px;" alt="Alberto Molpeceres"/><br /><sub><b>Alberto Molpeceres</b></sub></a></td>
    <td align="center"><a href="https://github.com/jerolba"><img src="https://avatars.githubusercontent.com/u/709055?v=4?s=100" width="100px;" alt="Jerónimo López"/><br /><sub><b>Jerónimo López</b></sub></a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

## ⚙️ How to contribute

The MAC is an open-source project. We are committed to a fully transparent development process and highly appreciate any contributions. Whether you help us fixing bugs, proposing new features, improving our documentation or spreading the word - we would love to have you as part of the MAC community.

Please refer to our [Contribution Guidelines](https://github.com/getmanfred/mac/blob/master/CONTRIBUTING.md) and [Code of Conduct](https://github.com/getmanfred/mac/blob/master/code_of_conduct.md).

## ⚖️ License

The MAC is a free and open-source software licensed and distributed under the Creative Commons Attribution Share Alike 4.0 International (CC BY-SA 4.0 International).

## 🌟 Spread the word!

If you want to say thank you and/or support active development of the MAC:

- Add a GitHub Star to the project!
- Post about the project on Twitter!
  - Tag [@getmanfred](https://twitter.com/getmanfred) and/or `#AwesomicCV`

Thanks so much for your interest in expanding the reach of the MAC!
