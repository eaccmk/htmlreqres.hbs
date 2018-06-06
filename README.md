# htmlreqres.hbs
template for creating Report after API (CLI) run

Save this as a part of your project and add this under `templates` folder e.g: `templates/htmlreqres.hbs`

run it as a part of newman CLI :

```newman run your_collection.json -d test-data-file.csv -e environment-file.json --global-var "if_any" --reporters cli,html --reporter-html-template templates/htmlreqres.hbs --reporter-html-export new-test-results-REPORT.html```
