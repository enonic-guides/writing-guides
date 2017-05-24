# Writing Enonic Guides

* Content for this guide is in Asciidoc format and the entry file is `docs/index.adoc`.
* Place new images under `docs/images`.
* To build documentation run `./gradlew asciidoctor` and find the results in `build/html5`.
* To push documentation run `./gradlew publishGhPages`.

If the guide has code:

* Add testable code snippets to `src` folder as appropriate for this guide.
* To test code snippets run `./gradlew check`.
