# Contributing to a Project of @freaktechnik

> This is a generic information file for all of my projects, so information may be missing or incomplete for the specific project that led you to this file.

## Code Contributions

I reserve the right to reject code contributions without any further explanation. However, I will try to let you know why I disagree with a change or addition.
In general, if you want to avoid wasting your time, it's probably best to pick something that has an issue on, that I've confirmed interest on (assigning a label
is confirmed interest).

If you want to make sure, feel free to contact me via the following messaging channels:

- By mail at martin@humanoids.be
- On matrix to [@freaktechnik:humanoids.be](https://matrix.to/#/@freaktechnik:humanoids.be)
- In the fediverse at [@freaktechnik@chaos.social](https://chaos.social/@freaktechnik)

I usually have rudimentary setup instructions in the README. If that shouldn't be the case (since it seems like wasted time for some small 2 hour project), please
also feel free to contact me, and most importantly, please contribute the information that you felt was key for you back to the project. The best documentation is
written by many people with different perspectives.

Should there be tests in the project (often ran with `npm test` and `npm run lint`), please try to make them pass before submitting a pull request. Usually the repository will have CI that will fail, too. If you can't figure out a failing test or are intimidated by the test infrastructure, feel free to ignore them and explicitly note so. However, linting should always pass.

I tend to have my own unique brand of code formatting. Please try to follow the exisiting format, especially when enforced by a linter. I'm not looking to change what I like, sorry.

Lastly, always feel free to fork the project if you disagree with my decision! It's open source software and all you have to do is respect the license.
I do ask kidnly that you rebrand, in order to avoid any confusion that may arise from a fork.

## Bug Reports

First off, thank you for finding a bug in the project and wanting to report it! Now for the hard part, writing a good report.

### The Title

Please try to choose a descriptive title of your issue, but don't think about it too hard, I will edit the title if necessary. "X doesn't work" is not
descriptive of an issue, whereas "X returns no results with Y", "X shows error Y" is.

### The Content

The most important parts of a bug report are what exactly is your environment (OS, project version, language etc.), steps to reproduce, actual behavior and
expected behavior.

For the steps to reproduce (STR), try to be as granular as possible, while still making something I could possibly follow on my own. Of course that's not always possible,
but having clear STR leads to much swifter issue isolation, and thus fixing.

For the actual behavior, consider including a screenshot or video when appropriate.

### The Bug You've Found was Already Reported

Neat, that means I'm already aware of it. Unless you have new information to add, please just thumbs up the issue and don't post a comment. More notifications means less time for coding and the comment will also lead to more work to find the relevant information in an issue. I'm also sorry if I don't think the bug
you're hitting is world shakingly important or can't figure out why it happens.

### My Response

I will likely not respond much, if I understand the bug report and can immediately reproduce. In a perfect world I'd pretty quickly respond with a code fix and
close the issue. I will close the issue before releasing the fix, but if I remember I'll post a comment on the issue once I've released the fix, to let you know.

## Feature Suggestions

In general feature suggestions are always welcome. But please don't be disappointed if I don't agree with your ideas of what a project should do. Sometimes it will
be because I don't think it takes the project in the right direction, and sometimes it will just be that I don't see the effort for the feature being worth the
result. Lastly, every now and then it will be impossible for me to implement a feature as part of a project, due to obligations I have from API usage agreements or
similar.

## Translations

Some of my projects will have the possibility of translations. Usually those will be gathered at an external service and included at build time and not be part of
the repository. You should find a link to the service in the README.

## Documentation

Same rules as code contributions apply. In general, if there is no user documentation a discussion about how user documentation should work should happen first.
Technical/code documentation is always welcome. If it gets too big for the README and there's no dedicated place yet, a `docs` folder in the root is a safe bet.

## Social/Recommendations/Reviews

You really enjoy the project but don't know how to help out? Starring the repo, sharing it with your friends, sharing it on social media or even blogging about it is always a help. Some projects will also appear in places that allow leaving ratings, so consider leaving one! Thank you in advance for spreading the word.
