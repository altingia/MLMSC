# IxDTL Simulator

IxDTL simulates the gene family evolution within a species tree, that accounts for population-level processes (resulting in incomplete lineage sorting), and gene duplications, transfers,and losses. 

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

python3

## Installing and testing

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Qiuyi Li** - *Initial work*

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc







To run, type: 

python3 ixdtl.py -i data/tree_sample_0.txt

the code will then run with default settings, if you want to change parameters by yourself:

-c coalescent rate			e.g. -c 0.5 (default)
  
-r recombination        e.g. -r 0.5 (no need to use under current version)
  
-d duplication rate     e.g. -d 0.2 (default)
  
-t transfer rate      	e.g. -t 0 (default)
  
-l loss rate      			e.g. -l 0.1 (default)
  
-u unlink probability 	e.g. -u 0.8 (no need to use under current version)
  
-h hemiplasy option 		e.g. -h True (default)
  
-v verbose option 			e.g. -v False (defalt)
  
For more options, check ixdtl.py


Suggested order of reading:

speciesTree.py

haplotypeTree.py & locusTree.py

ixdtl_model.py


Tree structure:

tree_table.py


Input options:

ixdtl.py
