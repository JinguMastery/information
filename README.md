# [Semantics Course](http://wadme.unige.ch:3149/pls/opprg/w_det_cours.debut?p_code_cours=12X008&p_plan_is=0&p_langue=1&p_frame=N&p_mode=PGC&p_annee=2016&p_suffixe=&p_grtri=) @ [University of Geneva](http://www.unige.ch)

This repository contains important information about this course.
**Do not forget to watch it** as it will allow us to send notifications for events,
such as new exercises, homework, slides or fixes.

## Important Information and Links

* [Page on Moodle](https://moodle.unige.ch/course/view.php?id=182)
* [Page on GitHub](https://github.com/unige-semantics-2017/information)
* Courses are Tuesday 10:00 - 12:00
* Exercises are Monday 16:00 - 18:00

## Environment

This course requires the following **mandatory** environment.
We have taken great care to make it as simple as possible.

* [GitHub](https://github.com) is a source code hosting platform;
  that we will for the exercises and homework.
  Create an account, and do not forget to fill your profile with your full name.
  Watch the [information](https://github.com/unige-semantics-2017/information)
  repository to get notifications about the course.
* [Atom](https://atom.io) is a text editor,
  that we will use to type the sources.
  Install it.
* [Docker](https://www.docker.com) is a platform for software containers;
  that we will use for the Swift compiler.
  Install it.
* [Swift](https://developer.apple.com/swift/) is a modern programming language;
  that we will use in exercises and homework;
  We use the [official docker image](https://hub.docker.com/_/swift/).

Test your environment by launching the Swift interpreter:

```sh
$ docker run --cap-add sys_ptrace -it --rm swift swift
```

## Source Code

All your homework will be stored within [this organization](https://github.com/unige-semantics-2017),
that will be deleted later.
If you want to keep your precious work, feel free to fork it in your own account.

## Tutorial

This [Swift Tutorial](https://kyouko-taiga.github.io/swift-thoughts/tutorial/)
will teach you everything needed for this course.
