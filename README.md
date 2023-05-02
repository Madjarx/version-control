## Version Control convention

### Commit messages:

Type:
- `docs` - changes regarding documentation of any kind
- `chore` - changes regarding chores
- `cleanup` - changes regarding any code cleanup (deletions)
- `refactor` - changes regarding any code refactoring (not changing the features)
- `feature` - changes regarding any new features to the codebase
- `bugfix` - changes regarding any fixes of bugs in the code
- `hotfix` - changes regarding any hack to fix the app asap
- any self explanatory custom type could be added and should be `in-kebab-case`

Types shouldn't start with uppercase letter.

Commit messages should follow this format: `type: short explanation`

If commit messages have any kind of reference, such as github issue, they will be stored in the parentheses in the following manner:
`bugfix (#123): Fixed the memory leak`


### Branches:

Type:
- `master` - master branch that will be used as a build source
- `staging` - rolling branch that will be used to track changes
- `develop` - branch where all the stuff goes at
- `feature/feature-name` - branch regarding the specific feature
- `docs` - if i ever live long enough to see this, focused on documentation, maybe even docusaurus generated docs website, but i prefer separate repo for that one

### Pull Requests:
- Titles will be self explanatory
- I tend to provide as much info as i can in the descriptions and comments

### Issues
- I will try to make issues readable with the `(__Issue Category__) Issue-Name: Short description`

## Lifecycle

`feature_specific_branch`---> `develop` ---minor-version---> `staging` ---major-version--->  `master` 
