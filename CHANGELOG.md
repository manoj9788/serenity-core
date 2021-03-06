## Release Notes

### upcoming (2014/11/17 09:16 +00:00)
- [50c45e3](https://github.com/serenity-bdd/serenity-core/commit/50c45e31c5432cde0067be0df0b458c3a908137e) Adding an automatically generated change log to the build (@wakaleo)

### v1.0.7 (2014/11/17 08:02 +00:00)
- [00de150](https://github.com/serenity-bdd/serenity-core/commit/00de150f4da3aab7b6d281e7a261d5378c656d49) Refactored the gradle plugin (@wakaleo)
- [7e62f61](https://github.com/serenity-bdd/serenity-core/commit/7e62f6107b803b732123df0cc7eedf9211911f3e) Merge branch 'master' of github.com:serenity-bdd/serenity-core (@wakaleo)
- [#2](https://github.com/serenity-bdd/serenity-core/pull/2) Merge pull request #2 from ptillemans/pti_hamcrest_1_1 (@ptillemans)
- [66556bb](https://github.com/serenity-bdd/serenity-core/commit/66556bb4e71cf652362fbedca72788ac5b0eb1ce) Fixed a bug where error messages were incorrectly displayed in the step details (@wakaleo)
- [6d0f8ee](https://github.com/serenity-bdd/serenity-core/commit/6d0f8ee7d7ee3c266af742c0e930c9ed5c7107e2) jbehave was pulling in hamcrest 1.1. Excluded hamcrest from the jbehave dependency. (@ptillemans)
- [4494dee](https://github.com/serenity-bdd/serenity-core/commit/4494dee65ac0b1fb24803ca4baf2d9241ac88e3c) If javadoc is not told to expect UTF-8 in the strings it uses can generate ASCII errors on at least the Mac. (@ptillemans)

### v1.0.6 (2014/11/14 06:51 +00:00)
- [2f58c3b](https://github.com/serenity-bdd/serenity-core/commit/2f58c3b419c5330bab8eb141d5a354a57bb12a07) Fixed some formatting and navigation issues in the reports (@wakaleo)

### v1.0.5 (2014/11/13 13:57 +00:00)
- [6780200](https://github.com/serenity-bdd/serenity-core/commit/6780200d8b74535f6d1e8b092c8953a249d5889e) Added the Serenity helper class, as a replacement for the legacy 'Thucydides' class (@wakaleo)
- [08b5502](https://github.com/serenity-bdd/serenity-core/commit/08b5502af44c08fe401f3ca9e140c13d85da9da7) Fixed a bug in the reporting where duplicate story tags were displayed in the screenshot screens. (@wakaleo)
- [805dbf1](https://github.com/serenity-bdd/serenity-core/commit/805dbf1a9bf72b6f67eb739a8de251e885daeba7) Logs a message indicating the path of the generated reports after report aggregation. (@wakaleo)
- [fe1c3c5](https://github.com/serenity-bdd/serenity-core/commit/fe1c3c5eb2cee95bcc3fc17f0008589f80b16dd0) Added the Serenity utility class, which exposes and delegates to methods of the legacy Thucydides class. (@wakaleo)
- [4138f89](https://github.com/serenity-bdd/serenity-core/commit/4138f8900eb6259f9c64bcfb75f713a29cc6eae8) Check if a resized file for a given screenshot already exists, and if so don't perform the resizing (@wakaleo)
- [0e9d614](https://github.com/serenity-bdd/serenity-core/commit/0e9d614b462448a994614470c2fb9a3eb21cca96) Moved most uses of FileUtils to the Java 7 Files class, in order to remove sporadic issues when resizing screenshots (@wakaleo)

### v1.0.4 (2014/11/11 17:01 +00:00)
- [7a65f64](https://github.com/serenity-bdd/serenity-core/commit/7a65f64d3bd4d6fe1ab6a798265e0a3729f9df1e) Fixed a failing test (@wakaleo)
- [b42d58b](https://github.com/serenity-bdd/serenity-core/commit/b42d58b33af6ea34b2155a2f6b30c1634b323799) Fine-tuning the reports (@wakaleo)
- [f07879c](https://github.com/serenity-bdd/serenity-core/commit/f07879ca4b9418342d144ba78200c76f2a8d323a) Refactored some tests (@wakaleo)
- [d5511b6](https://github.com/serenity-bdd/serenity-core/commit/d5511b6706701d49a361192e5a8752e273c23ebe) Cater for rare cases where the driver returns null when an element is not found (@wakaleo)
- [36d471f](https://github.com/serenity-bdd/serenity-core/commit/36d471f7c2acdbd9d33dd54c99b33c1df503b964) Repositioned the report timestamp (@wakaleo)
- [80e1ef0](https://github.com/serenity-bdd/serenity-core/commit/80e1ef06258e1e5f17487731641eaec8434776b7) Repositioned the report timestamp (@wakaleo)
- [c8fd3b9](https://github.com/serenity-bdd/serenity-core/commit/c8fd3b94c1bd867c8d79fe6554b4e36a267c7648) Added bootstrap tabs (@wakaleo)
- [4a132ad](https://github.com/serenity-bdd/serenity-core/commit/4a132ad31b57d7fd42db1bc78770a57e2414f7f4) Added tests to the gradle plugin (@wakaleo)
- [98073bd](https://github.com/serenity-bdd/serenity-core/commit/98073bdbe5ff127561ea662aa6b8ea7eba514e09) Added SerenityRunner and SerenityParameterizedRunner classes as alternative names for ThucydidesRunner and ThucydidesParameterizedRunner, more in line with the new naming schema. (@wakaleo)
- [4c953d8](https://github.com/serenity-bdd/serenity-core/commit/4c953d868707e2cf59ea7edde1a85008966d5e2e) Moved the serenity-maven-plugin to a separate project (@wakaleo)
- [ad4800e](https://github.com/serenity-bdd/serenity-core/commit/ad4800ebcf39afdf66abb76a28d9290f29fd3ad7) Getting the maven plugin build working (@wakaleo)
- [74df029](https://github.com/serenity-bdd/serenity-core/commit/74df0296738f380196774513f93e725690233975) Fine-tuning the release tagging (@wakaleo)

### v1.0.2 (2014/11/06 21:48 +00:00)
- [527387e](https://github.com/serenity-bdd/serenity-core/commit/527387e98a503f08e74ede8790156cfcf6ae8b3b) Initial release version (@wakaleo)
- [4a119f5](https://github.com/serenity-bdd/serenity-core/commit/4a119f5eb78613da322bc3a69d548e859b2d597e) Added a selector to find buttons by their label, e.g. find(By.buttonText('Add to cart')); (@wakaleo)
- [8ba6aeb](https://github.com/serenity-bdd/serenity-core/commit/8ba6aeb194a96bbcaad15918632d57d88aeb0b5b) Honor both 'thucydides.properties' and 'serenity.properties' files for local project configuration (@wakaleo)
- [b5732dc](https://github.com/serenity-bdd/serenity-core/commit/b5732dc3a744246365f512d30484aae735f0f636) Let the bintray keys be defined by the build server (@wakaleo)
- [f2322d4](https://github.com/serenity-bdd/serenity-core/commit/f2322d488bb19e970bc0e60f8dce015f4e713e69) Minor fix to work around an incompatiblity with IBM JDB 1.7 (@wakaleo)
- [5caf4a2](https://github.com/serenity-bdd/serenity-core/commit/5caf4a28cbcb818b7642ce5d4b5614ce188f9b22) Changed group to serenity-bdd to make syncing with Maven Central easier (@wakaleo)
- [5d3f58a](https://github.com/serenity-bdd/serenity-core/commit/5d3f58a217827dd31050f2d1b79237cc86f245f3) Changed group to serenity-bdd to make syncing with Maven Central easier (@wakaleo)
- [1d7740d](https://github.com/serenity-bdd/serenity-core/commit/1d7740dc9d007c0e84470f30137bb611e9f74336) Fixed an issue in the BinTray deployment (@wakaleo)
- [3620bc2](https://github.com/serenity-bdd/serenity-core/commit/3620bc2af882c4309783aee127d0dff9a9984833) Fine-tuning the release pipeline (@wakaleo)
- [bc0e078](https://github.com/serenity-bdd/serenity-core/commit/bc0e078f187ae7fdd0c7889180b09d4fe51778fb) Added more info to the README file (@wakaleo)
- [3049d14](https://github.com/serenity-bdd/serenity-core/commit/3049d1465732d6c384a0a9019b70c1e6366a5328) Initial move over to Serenity from Thucydides (@wakaleo)