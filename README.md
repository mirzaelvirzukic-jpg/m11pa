# Module 11 — Localization and try-with-resources

The solution selects German, adds the four required German translations, and uses try-with-resources for configuration file input.

## Finish in IntelliJ

1. Open `LocalizedDemo/pom.xml` as a project with JDK 17 or newer.
2. Run `LocalizedDemoApp.java`. Set the run configuration working directory to the `LocalizedDemo` folder, which contains `config.properties`.
3. Take a screenshot of the IntelliJ window showing the successful German output. Save it as `Screenshot.png` in this repository root.

Expected output:

```text
Hallo!
Auf Wiedersehen!
Anwendungsname: Localization Demo Application
```

## Submit with Git

Create your fork using the Fork button at https://github.com/FSCJ-COP3330C/m11pa . Then run these commands from this folder:

```sh
git remote set-url origin https://github.com/mirzaelvirzukic-jpg/m11pa.git
git add Screenshot.png
git commit -m "Add IntelliJ German execution screenshot"
git push -u origin main
```

The solution changes are already committed locally. These commands push those changes and your screenshot. Do not use GitHub's file upload feature. Compiled files and build folders are ignored.
