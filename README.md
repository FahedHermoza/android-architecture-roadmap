<h1 align="center">Android Architecture Roadmap 🏢</h1>

<div align="center">
        <img width="60%" src="screenshots/badge.svg" alt="About screen" title="About screen"</img>
        <img height="0" width="5px">
</div>

Welcome to Android Architecture Roadmap

The main goal of this roadmap is to help someone who gains knowledge of Android architecture.
This roadmap was an idea after giving a talk to the GDG Cusco community about Android Architecture 
in the real world, resources used are shared below:
- **[Talk: Android Architecture in the real world](https://docs.google.com/presentation/d/1zhMWp0l3Xzxt324TwmSncworTvLwiuTX_Tenj51vTnk/edit?usp=sharing)**

This contains all topics to help you find what you are looking for quickly. I hope I can help you.

## 🗺 Roadmap
<div align="center">
        <img width="100%" src="screenshots/AndroidArquitectureRoadmap.jpg" alt="About screen" title="About screen"</img>
        <img height="0" width="16px">
</div>

## Contents
- 👍 Good and bad practices
    * [Clean Code](https://medium.com/storyblocks-engineering/these-four-clean-code-tips-will-dramatically-improve-your-engineering-teams-productivity-b5bd121dd150)
    * [KISS, DRY, YAGNI](https://medium.com/@dioxmio/7-software-development-principles-that-should-be-embraced-daily-c26a94ec4ecc)
    * [SOLID Principles](https://medium.com/backticks-tildes/the-s-o-l-i-d-principles-in-pictures-b34ce2f1e898)
    * [Avoid STUPID Principles](https://williamdurand.fr/2013/07/30/from-stupid-to-solid-code/)
    * [Naming Test](https://www.codurance.com/publications/2014/12/13/naming-test-classes-and-methods)
    * [Code Smells](https://refactoring.guru/es/refactoring/smells)
* 🏛️ Architecture pattern (presentation pattern or UI pattern)
    * [️MVP](https://github.com/antoniolg/androidmvp)
    * MVVM
    * MVI
* 🧱 Architecture components
    * [Android jetpack](https://developer.android.com/jetpack?gclid=CjwKCAjwo7iiBhAEEiwAsIxQEQjRcV1OAX1ExRKSe-zvmtUOawU2oJrLYXxa3crR473Si6zssnfkihoCjeAQAvD_BwE&gclsrc=aw.ds)
    * External libraries
* 🧩 Design patterns
    * [Creational](https://refactoring.guru/es/design-patterns/creational-patterns)
        - [Singleton](https://refactoring.guru/es/design-patterns/singleton)
        - [Builder](https://refactoring.guru/es/design-patterns/builder)
    * [Structural](https://refactoring.guru/es/design-patterns/structural-patterns)
        - [Adapter](https://refactoring.guru/es/design-patterns/adapter)
        - [Composite](https://refactoring.guru/es/design-patterns/composite)
    * [Behavioral](https://refactoring.guru/es/design-patterns/behavioral-patterns)
        - [Observer](https://refactoring.guru/es/design-patterns/observer)
* 🏢 Architecture of system
    * [Clean Arquitecture](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)  (layered architecture)
        - Domian layer
        - Data layer
            - [Patron repository](https://svatasimara.medium.com/domain-driven-design-part-5-repository-d5ad32b2e06f)
        - Presentation layer
        - Handle dependencies
            - [Dependency Injection](https://medium.com/free-code-camp/a-quick-intro-to-dependency-injection-what-it-is-and-when-to-use-it-7578c84fa88f)
            - [Service locator pattern](https://medium.com/inloopx/service-locator-pattern-in-android-af3830924c69)
* ✅ Quality Assurance
    * [Testing](https://developer.android.com/training/testing)
        - [Unit Test](https://developer.android.com/training/testing/local-tests)
        - [Integration Test](https://developer.android.com/training/testing/fundamentals/test-doubles)
        - [UI Test](https://developer.android.com/training/testing/instrumented-tests/ui-tests)
    * [️Linters](https://en.wikipedia.org/wiki/Lint_(software))
        - [Android Lint](https://developer.android.com/studio/write/lint)
        - [Checkstyle](https://github.com/checkstyle/checkstyle)
        - [PMD](https://pmd.github.io/)
        - [SpotBugs (FindBugs)](https://spotbugs.github.io/)
    * [️Code Coverage](https://en.wikipedia.org/wiki/Code_coverage)
        - [SonarQube](https://www.sonarsource.com/products/sonarqube/)
        - [JaCoCo](https://www.baeldung.com/jacoco)
        - [Android Test Orchestrator](https://medium.com/stepstone-tech/android-test-orchestrator-unmasked-83b8879928fa)
* 🚀 Multi-Module Apps
    * [️Modularization](https://developer.android.com/topic/modularization)
        - App modules
        - Library modules
        - Kotlin and Java modules
        - Dynamic feature modules
    * [Package structure](https://proandroiddev.com/package-by-type-by-layer-by-feature-vs-package-by-layered-feature-e59921a4dffa)
        - [Package by type](https://proandroiddev.com/package-by-type-by-layer-by-feature-vs-package-by-layered-feature-e59921a4dffa)
        - [Package by feature](https://proandroiddev.com/package-by-type-by-layer-by-feature-vs-package-by-layered-feature-e59921a4dffa)
        - [Package by layer](https://proandroiddev.com/package-by-type-by-layer-by-feature-vs-package-by-layered-feature-e59921a4dffa)
        - [Package by module](https://proandroiddev.com/package-by-type-by-layer-by-feature-vs-package-by-layered-feature-e59921a4dffa)
        - [Hybrid Package:](https://proandroiddev.com/package-by-type-by-layer-by-feature-vs-package-by-layered-feature-e59921a4dffa) Package by feature on the exterior, and package by layer on the interior. (recomended for apps medium or big)
    *  🤖 Modularization + Package Structure
        - App Module   
        - Features Modules 
            - Package by feature on the exterior, and package layer on the interior
        - Commons Modules

## ✍️ Resources
The talk "Android Architecture
in the real world" is based on the following resources:
- **[Book: Real-World Android by Tutorials](https://www.kodeco.com/books/real-world-android-by-tutorials)**
- **[Book: Android Test-Driven Development by Tutorials](https://www.kodeco.com/books/android-test-driven-development-by-tutorials)**
- **[Book: Advanced Android App Architecture](https://www.kodeco.com/books/advanced-android-app-architecture)**

Some books recommended:
- **[Book: Clean Code](https://www.amazon.com/Clean-Code-Handbook-Software-Craftsmanship/dp/0132350882)**
- **[Book: Clean Architecture](https://www.amazon.com/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164/ref=pd_bxgy_vft_none_img_sccl_1/144-6523082-0304818?pd_rd_w=6YdbC&content-id=amzn1.sym.26a5c67f-1a30-486b-bb90-b523ad38d5a0&pf_rd_p=26a5c67f-1a30-486b-bb90-b523ad38d5a0&pf_rd_r=DGTME3D60N6MRQ80YW5V&pd_rd_wg=AztZL&pd_rd_r=6c5279f8-4a86-4be6-ba96-394d5808140b&pd_rd_i=0134494164&psc=1)**
- **[Book: Design Patterns by Refactoring Guru](https://refactoring.guru/design-patterns/book)**

## 💡 Inspiration
This project is inspired by [Mobile Developer Security Roadmap ](https://github.com/rviannaoliveira/mobile-developer-security-roadmap), [Android Developer Roadmap 2022](https://github.com/skydoves/android-developer-roadmap). So thank you for the authors providing the roadmap ideas. Also, you can learn a lot of knowledge from the repositories.

## 🚦 Wrap Up
If you have an idea to improve the map, feel free to discuss it in the issues.

## ⚠️  Disclamer
This information is focused on semi-senior and senior engineers. Use your own judgement and use with caution.

## Find this project useful? :heart:

Support it by joining __[stargazers](https://github.com/FahedHermoza/android-architecture-roadmap/stargazers)__ for this repository. :star: <br>
And __[follow](https://www.linkedin.com/in/fahedhermoza/)__ me for my next creations! 🤩

License
-------

    Copyright 2023 Fahed Hermoza

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.