# gci-csv-validator

CSV validator for the [Google Code-in Web API](https://developers.google.com/open-source/gci/api)

### Installation

```
pip install gci-validator
```

### Todo
- [ ] Add more flexible command-line options
	- [ ] Verbose validation output
	- [ ] Custom boolean flags
	- [ ] Custom selection of tags
	- [ ] Custom meta-data validator
- [ ] Add validation logic to 'status' field so that it can only be set to "Published" (1) if the below fields are entered validly:
	- 'name'
	- 'description'
	- 'max_instances'
	- 'categories'
	- 'time_to_complete_in_days'
	- 'mentors'