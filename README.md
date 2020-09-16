# myrepo
[![seflaherty](https://circleci.com/gh/seflaherty/myrepo.svg?style=shield)](https://circleci.com/gh/seflaherty/myrepo)

⚡ This artifact is based on an automation call to action from *"Cloud Computing for Data Analysis"* by Noah Gift, Ch. 1 **How to ship high-quality software that works and is on-time**.

This is an demonstration repo of a how to create a _Data Science focused Python project_.
There is a video on the setup of this demonstration repo here:

[![Data Science Build Project](http://img.youtube.com/vi/xYX7n5bZw-w/hqdefault.jpg)](http://www.youtube.com/watch?v=xYX7n5bZw-w)

This video does a full breakdown of how to use and create a Makefile:

[![How to use Pylint, Nbval and Coverage to test Jupyter Notebooks](https://img.youtube.com/vi/ABaPWYF_Tl8/hqdefault.jpg)](https://www.youtube.com/watch?v=ABaPWYF_Tl8)

A few things to do with this project:

* install software: ```make install```
* test code: ```make test```
* lint code: ```make lint```
* run commandline tool:  

```bash
./cli.py --name john 
john-apple
```

* run jupyter notebook:

```
jupyter notebook notebook.ipynb
```

* test jupyter notebook:

```
python -m pytest --nbval notebook.ipynb
```

Get more information on this topic at [Functional, Data Science Intro To Python](https://github.com/noahgift/functional_intro_to_python)
