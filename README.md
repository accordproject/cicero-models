<p align="center">
  <a href="https://www.accordproject.org/">
    <img src="assets/images/APLogo.png" alt="Accord Project Logo" width="400" />
  </a>
</p>  

<h1 align="center">Accord Project Model Catalog</h1>
<p align="center">
  <a href="https://github.com/accordproject/models/blob/master/LICENSE"><img src="https://img.shields.io/github/license/accordproject/models" alt="GitHub license"></a>
  <a href="https://accord-project-slack-signup.herokuapp.com/"><img src="https://img.shields.io/badge/Slack-Join%20Slack-blue" alt="slack"></a>
  <br>
</p>

This repository hosts all Accord Project models. Model's are captured using the [Concerto][concerto] modeling language; a platform and runtime neutral typed schema language.

The build system for this repository publishes the models to: https://models.accordproject.org

Environment Variables used by the build system:

- SERVER_ROOT : the root URL for the server. Used when generating absolute hyperlinks.
- FORCE_PUBLISH : disabled the download of external models and model validation. Should be used with care!

---

Accord Project is an open source, non-profit, initiative working to transform contract management and contract automation by digitizing contracts. Accord Project operates under the umbrella of the [Linux Foundation][linuxfound]. The technical charter for the Accord Project can be found [here][charter].

## Learn More About Accord Project

### Overview
* [Accord Project][apmain]
* [Accord Project News][apnews]
* [Accord Project Blog][apblog]
* [Accord Project Slack][apslack]
* [Accord Project Technical Documentation][apdoc]
* [Accord Project GitHub][apgit]


### Documentation
* [Getting Started with Accord Project][docwelcome]
* [Concepts and High-level Architecture][dochighlevel]
* [How to use the Cicero Templating System][doccicero]
* [How to Author Accord Project Templates][docstudio]
* [Ergo Language Guide][docergo]

## Contributing

The Accord Project technology is being developed as open source. All the software packages are being actively maintained on GitHub and we encourage organizations and individuals to contribute requirements, documentation, issues, new templates, and code.

Find out what’s happening on our [blog][apblog].

Join the Accord Project Technology Working Group [Slack channel][apslack] to get involved!

For code contributions, read our [CONTRIBUTING guide][contributing] and information for [DEVELOPERS][developers].

## License <a name="license"></a>

Accord Project source code files are made available under the [Apache License, Version 2.0][apache].
Accord Project documentation files are made available under the [Creative Commons Attribution 4.0 International License][creativecommons] (CC-BY-4.0).

[concerto]: https://github.com/accordproject/concerto

[linuxfound]: https://www.linuxfoundation.org
[charter]: https://github.com/accordproject/models/blob/master/CHARTER.md
[apmain]: https://accordproject.org/ 
[apworkgroup]: https://calendar.google.com/calendar/event?action=TEMPLATE&tmeid=MjZvYzIzZHVrYnI1aDVzbjZnMHJqYmtwaGlfMjAxNzExMTVUMjEwMDAwWiBkYW5AY2xhdXNlLmlv&tmsrc=dan%40clause.io
[apblog]: https://medium.com/@accordhq
[apnews]: https://www.accordproject.org/news/
[apgit]:  https://github.com/accordproject/
[apdoc]: https://docs.accordproject.org/
[apslack]: https://accord-project-slack-signup.herokuapp.com

[docspec]: https://docs.accordproject.org/docs/spec-overview.html
[docwelcome]: https://docs.accordproject.org/docs/accordproject.html
[dochighlevel]: https://docs.accordproject.org/docs/spec-concepts.html
[docergo]: https://docs.accordproject.org/docs/logic-ergo.html
[docstart]: https://docs.accordproject.org/docs/accordproject.html
[doccicero]: https://docs.accordproject.org/docs/basic-use.html
[docstudio]: https://docs.accordproject.org/docs/advanced-latedelivery.html

[contributing]: https://github.com/accordproject/models/blob/master/CONTRIBUTING.md
[developers]: https://github.com/accordproject/models/blob/master/DEVELOPERS.md

[apache]: https://github.com/accordproject/template-studio-v2/blob/master/LICENSE
[creativecommons]: http://creativecommons.org/licenses/by/4.0/
