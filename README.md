# rdf-property-table
Transform a RDF file into property class tables.

See [A survey of RDF storage approaches](https://hal.inria.fr/hal-01299496/document) for more informations on property table.

# Installation

Assuming you already have `python 3`, `pip`, `java jdk (openjdk will do)`,

Download [jena](https://jena.apache.org/download/index.cgi) and update classpath:

```bash
export CLASSPATH=${CLASSPATH}:YOUR-JENA-DIR-PATH/lib/*
```

Installation in a virtualenv is strongly recommended

install Cython

```bash
python -m pip install --upgrade cython
```

Install dependencies with pip:

```bash
pip install -r requirements.txt
```

# Run it !

```bash
python property_table.py [filepath]
```

Example to convert two RDF fils in the current directory:

```bash
python property_table.py rdf_file.ttl rdf_file2.ttl
```
