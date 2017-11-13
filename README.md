# gci-csv-validator

CSV validator for the [Google Code-in Web API](https://developers.google.com/open-source/gci/api)

### Installation

```
pip install gci-validator
```

### Usage
```gci-validator.
Usage: 
    gci-validator (FILE) [options]

Options:
    -h --help    Show help text.
    -v --version Show program version.
    -b=<bvals>   Define boolean values. Separated by commas [default: yes, no].

```

### Todo
- [ ] Add more flexible command-line options
	- [ ] Verbose validation output
	- [x] Custom boolean flags
	- [ ] Custom selection of tags
	- [ ] Custom meta-data validator
- [x] Add validation logic to 'status' field so that it can only be set to "Published" (2) if the below fields are entered validly:
	- 'name'
	- 'description'
	- 'max_instances'
	- 'categories'
	- 'time_to_complete_in_days'
	- 'mentors'