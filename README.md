# RACurated

Curated list of ReactiveCocoa projects. 

## How to contribute

This list is only relevant if it keeps growing. Please feel free to open a pull
request to suggest an app or a framework using ReactiveCocoa. Although please 
note that even if we loved hitting those square-bracket keys thousands of times
a day writting code using ReactiveCocoa in Objective-C, we are trying to 
curate a list of projects using the most recent version of the framework.

1. Fork the repository
2. Create a branch
3. Edit the _data/projects.yml, see below for an example project
4. Commit and open a pull request against the *gh-pages* branch

Sample project row: 

```yaml
- name: Project name
  description: Description of the project, mostly what it does
  type: tool # possible values are ios, mac, tool and framework
  highlights: [Command line] # What's important in this project (MVVM, special pattern...)
  rac_version: 4
  repo_url: https://github.com/carthage/carthage
```

## License

Creative Commons. Set [License file](License).
