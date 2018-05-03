[中文版本的 README](README.zh-Hans.md)
------------------------------

# Chinese models for SpaCy

SpaCy (version > 2) models for Chinese language. Those models are rough and still work in prograss. But "Something is Better Than Nothing".

## Getting Started

Models are released as binary file, users should know basic knowledge of using SpaCy version 2+.

### Prerequisites

Python 3 (maybe python2, but currently not well tested)

### Installing

Download relased model from `releases`.

```
wget -c https://github.com/howl-anderson/Chinese_models_for_SpaCy/releases/download/v2.0.1/zh_core_web_sm-2.0.1.tar.gz
```

then install model

```
pip install zh_core_web_sm-2.0.1.tar.gz
```


## Running demo code

`test.py` contains demo codes. After install the model, user can download or clone this repo then execute:

```bash
python3 ./test.py
```

then, open web browser to `http://127.0.0.1:5000`, user will see image simllar to this:

![Dependency of doc](.images/dependency_of_doc.png)

## How to re-produce model

See [workflow](workflow.md)

## Built With

* TODO

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the `tags` on this repository.

## Authors

* **Xiaoquan Kong** - *Initial work* - [howl-anderson](https://github.com/howl-anderson)

See also the list of `contributors` who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* TODO
