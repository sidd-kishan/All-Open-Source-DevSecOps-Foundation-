# All Open Source DevSecOps Foundation

Dev + Sec and Ops + Sec

All free and opensource for startups and enterprises alike automated Source code and infrastructure configuration management.

## DEV + Sec (SecTAP [Secuirty Tool Assisted Patching Utility])

### Manual Stack (paranoid 9000):-

Developer code commit ( SVN, GitHub, etc.) -> Manual latest checkout provided to SECTAP (Security Tool assisted patching Utillity) -> new patched code rendered and comitted back to the source repo -> Manual Code Diff by developer for code review and dry run validations -> Manual Sanity test of buisness use cases -> now the new code can be promoted to the production.

### Full Auto (Light Speed Secuirty):-

Developer code commit ( SVN, GitHub, etc.) -> jenkins/puppet/chef/Ancible play book takes the checkout provides SECTAP (Security Tool assisted patching Utillity) -> new patched code rendered and comitted back to the source repo by jenkins/puppet/chef/Ancible play book -> Automated Sanity test suites can be fired from Maven/Selinium/postman -> all scuueeds the new code can be promoted to to the production with secuirty patches without developer interventions or QA interventions.

## Sec + OPS (MLAF [Machine Learning based multi level Application firewall], Regex turtle (a genetic algorithm based Regex generation), Database Abstraction Layer to layer to Learn Queries landing to the Database)

### Manual (paranoid 9000):-

Manual 

### Full Auto ( Light Speed Secuirty) :-




## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```python
import foobar

foobar.pluralize('word') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
