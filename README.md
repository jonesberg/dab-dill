# dab-dill: a fresh take on defining Databricks Asset Bundles

dab-dill is a pre-processor for [Databricks Asset Bundles](https://docs.databricks.com/en/dev-tools/bundles/index.html) (DAB) that leverage the [Pkl configuration language](https://pkl-lang.org/) for ease of authoring, extension, and maintainance.

Compared to the YAML approach, dab-dill in my opinion provides

* A friendlier, object-oriented-*(ish)* definition for bundles.
* Strong typing and value validation through the pre-processor (when applicable)
* Better re-usability across bundle defition through cleaner imports and variable expansion (when applicable).

Most of the advantages are provided by the Pkl configuration language directly.

dab-dill is **not** a replacement for the Databricks CLI. It simply takes your configuration files in `pkl` format and generates the `databricks.yml` that is used for assets bundle definition.

## How to use

*Right now, I do not recommend you use this just yet for your `databricks.yml` generation.*

**TODO**: Instructions

## What works?

Currently, this project is in its infancy. I am still working through the best way to express the bundle definition, and I am adding fields as I need them for my day job. Contributions and debates are welcome.

<!-- For a field-by-field progress can be tracked under PROGRESS.md -->

## About the name

In Manitoba, we have a mustard company called [Smak Dab](https://smakdab.ca/pages/about) who makes a delicious hot & sweet dill mustard. The DAB abbreviation systematically reminds me of this mustard. Because dill is a popular flavour of pickles (Pkl) is also everywhere in Manitoba's cuisine, I felt like naming the project dab-dill.

