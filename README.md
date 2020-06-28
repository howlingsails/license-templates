Forked From [Lice Repo](https://github.com/licenses/lice) for the purpose of exmaple in the manufacturing process

# License Templates

These files are designed to be used by `lice`, a command-line license generator
for software projects. 

## Format/Structure

The template uses variables as placeholders to substitute values specified by
`lice`.

* `{{ year }}`: the year of the software's copyright.
* `{{ organization }}`: the name of the organization or individual who holds
the copyright to the software.
* `{{ project }}`: the name of the software project.

## Copyright

All licenses in this repository are copyrighted by their respective authors.
Everything else is released under CC0. See `LICENSE` for details.


## Using lice


Installation of lice assuming you have python at the command line

```bash
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python get-pip.py //TODO: Find Python3 example
pip install lice
```

Generating Licenses

```bash
echo "Generate an MIT License for my open source project "Hollwing Sails Studio" project in 2020. "
echo "Example:"
echo "    lice mit -y 2020 -o \"Hollowing Sails Studio\""

lice mit -y 2020 -o "Hollowing Sails Studio"

```


